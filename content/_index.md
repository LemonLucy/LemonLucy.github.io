---
# Leave the homepage title empty to use the site title
title: LemonLucy
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: <br><br><span style="font-size:150%; font-weight:bold; "> Eungyo World </span>
      text: <br><br>
        {{% cta cta_link="./experience/" cta_text="See Research Field ↑" %}}
    design:
      background:
        image:
          filename: bg.jpg
        spacing:
          padding: ['100px', '0', '100px', '0']

- block: collection
  content:
    title: Research & Development
    items:
      - name: Artificial Intelligence (AI)
        icon: code-branch
        description: AI 연구 및 프로젝트.
      - name: Mathematics (Math)
        icon: calculator
        description: 수학적 연구 및 AI 적용.
      - name: Development
        icon: laptop
        description: 풀스택 개발 프로젝트.
      - name: Programming Languages
        icon: code
        description: Python, JavaScript 등.
      - name: Data Analysis Tools
        icon: database
        description: SQL, Pandas, Excel.
      - name: Cloud Platforms
        icon: cloud
        description: AWS, Azure 등 클라우드 기술.
      - name: LG Project
        icon: briefcase
        description: 데이터 분석 및 시각화 프로젝트.
      - name: JBNU Leadership
        icon: user-tie
        description: 팀 리더로 수행한 AI 및 UI/UX 프로젝트.
      - name: SmartFarm Development
        icon: leaf
        description: 스마트팜 관련 앱 개발 프로젝트.
  design:
    view: community/custom_card
    columns: '3'


  - block: features
    content:
      title: <span style="font-size:75%">My Interests</span>
      text: I am interested in the following research and development fields.<br><br>
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

    design:
      background:
        image:
          filename: interest.jpg
          filters:
            brightness: 0.8
        text_color_light: true
        spacing:
          padding: ['100px', '0', '100px', '0']


  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%;font-weight:bold; ">Cloud Computing</span>
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

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
      spacing:
        padding: ['100px', '0', '0', '0']

  - block: collection
    content:
      title: Notifications & News
      subtitle:
      text:
      count: 2
      offset: 0
      order: desc
      filters:
        folders:
          - notification
          - post
    design:
      view: community/custom_card
      columns: '2'

---
