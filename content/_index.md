---
# Leave the homepage title empty to use the site title
title:
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
        

  - block: features
    content:
      title: <span style="font-size:75%; font-weight:bold; ">관심 분야</span>
      text: 저는 다음과 같은 연구 및 개발 분야에 관심이 있습니다.<br><br>
      items:
        - name: 인공지능 (AI)
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">스마트팜과 같은 특수 분야에 적응형 AI 기술을 적용합니다.</span><br><br>
        - name: 수학 (Math)
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">AI에 사용되는 확률, 통계, 선형 대수, 이산 수학.</span><br><br>
        - name: 개발 (Development)
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">풀스택 기반 애플리케이션 개발.</span><br><br>
        - name: 솔루션 (Solution)
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">AI 핵심 기술을 적용한 통합 솔루션 개발!</span><br><br>

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

      - title: <span style="font-size:70%">Cloud Computing</span>
        content: <span style="font-size:70%">클라우드 컴퓨팅<span style="font-size:70%">
        align: center
        background:
          image:
            filename: aws.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">SmartFarm</span>
        content: <span style="font-size:70%">스마트팜 분야에 적용 가능한 앱 개발</span>
        align: center
        background:
          image:
            filename: smartfarm.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Mathematics</span>
        content: <span style="font-size:70%">AI와 관련된 수학</span>
        align: center
        background:
          image:
            filename: mathematics.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">기반 기술을 활용한 Full-Stack 어플리케이션 개발</span>
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
      
author: admin
---