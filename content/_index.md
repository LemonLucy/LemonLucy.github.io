---
# Leave the homepage title empty to use the site title
title: LemonLucy
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: <span style="font-size:130%; font-weight:bold; color:black;"> Eungyo's Website </span>
      
        {{% cta cta_link="./field/" cta_text="See Research Field →" %}}

    design:
      background:
        image:
          filename: bg.jpg


  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Cloud Computing</span>
        content: <span style="font-size:70%">Cloud Computing</span>
        align: center
        background:
          image:
            filename: aws.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">SmartFarm</span>
        content: <span style="font-size:70%">App Development for SmartFarm Applications</span>
        align: center
        background:
          image:
            filename: smartfarm.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Mathematics</span>
        content: <span style="font-size:70%">Mathematics related to AI</span>
        align: center
        background:
          image:
            filename: mathematics.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">Full-Stack Application Development using Core Technologies</span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">Lab's Interests</span>
      text: I am interested in the following research and development fields.<br><br><br><br>
      items:
        - name: Artificial Intelligence (AI)
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">Applying adaptive AI technologies to specialized areas such as SmartFarm.</span><br><br>
        - name: Mathematics (Math)
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">Probability, statistics, linear algebra, and discrete mathematics used in AI.</span><br><br>
        - name: Development
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">Full-Stack based application development.</span><br><br>
        - name: Solution
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">Developing integrated solutions through the application of AI core technologies and related applications!</span><br><br>


  - block: collection
    content:
      id: section-1
      title: Notifications & News
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - notification
          - post
          - event
    design:
      view: community/custom_card
      columns: '2'

---
