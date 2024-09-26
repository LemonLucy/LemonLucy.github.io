---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing


sections:

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">At MacsLAB, we conduct research utilizing AI and deep learning across various fields including healthcare, EMR, Vision, aerospace, and defense, alongside research in medical mathematics and AI-based studies. Furthermore, we are also focused on practical areas such as full-stack development and application development leveraging AI.</span>

  - block: slider
    content:
      slides:

      - title: <span style="font-size:90%">Smart Farm</span>
        content: <span style="font-size:90%">Development of apps related to smart farming</span>
        align: center
        background:
          image:
            filename: smartfarm.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Cloud Computing</span>
        content: <span style="font-size:90%">Cloud Computing with AWS</span>
        align: center
        background:
          image:
            filename: aws.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Mathematics</span>
        content: <span style="font-size:90%">Mathematics related to AI</span>
        align: center
        background:
          image:
            filename: mathematics.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Development</span>
        content: <span style="font-size:90%">Full-Stack application development</span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  # - block: hero
  #   content:
  #     title: |
  #       <span style="font-size:75%">Medical AI & Computational Science (MACS) Lab</span>
  #     image:
  #       filename: welcome.jpg
  #     text: |
  #       <br>
  #
  #       <span style="font-size:75%">Welcome to the homepage of the Medical AI and Computational Science (MACS) Lab at Jeonbuk National University. At MACS, we conduct research utilizing AI and deep learning in healthcare, aerospace, and defense, alongside medical mathematics and AI-based studies. Furthermore, we focus on practical areas such as full-stack development and application development utilizing AI.</span>

---
