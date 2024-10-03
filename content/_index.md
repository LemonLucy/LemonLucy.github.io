---
# 홈페이지 제목을 비워두면 사이트 제목을 사용합니다.
title: LemonLucy
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: <span style="font-size:150%; font-weight:bold; "> Eungyo World  </span>
      text: <br><br>
        {{% cta cta_link="./experience/" cta_text="연구 분야 보기 ↑" %}}
    design:
      background:
        image:
          filename: bg.jpg
        spacing:
          padding: ['100px', '0', '100px', '0']

  - block: collection
    content:
      title: 약력
      subtitle:
      text:
      count: 1
      offset: 0
      order: desc
      filters:
        folders:
          - bio
    design:
      view: community/custom_compact
      columns: '2'

  - block: collection
    content:
      title: 내 작업
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - project
    design:
      view: community/card
      columns: '3'
      flip_alt_rows: true
      

  - block: features
    content:
      title: <span style="font-size:75%">내 관심사</span>
      text: 저는 다음 연구 및 개발 분야에 관심이 있습니다.<br><br>
      items:
        - name: 인공지능 (AI)
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">스마트팜과 같은 특화된 분야에 적응형 AI 기술 적용.</span><br><br>
        - name: 수학 (Math)
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">AI에서 사용되는 확률, 통계, 선형대수 및 이산수학.</span><br><br>
        - name: 개발 (Development)
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">풀스택 기반 애플리케이션 개발.</span><br><br>

    design:
      background:
        image:
          filename: interest.jpg
          filters:
            brightness: 0.8
        text_color_light: true
        spacing:
          padding: ['100px', '0', '100px', '0']

  - block: collection
    content:
      title: 나는 공부 중 ...
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - ongoingproject
    design:
      view: community/gorgeous_card
      columns: '2'
      flip_alt_rows: true


  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%;font-weight:bold; ">클라우드 컴퓨팅</span>
        content: <span style="font-size:70%">클라우드 컴퓨팅</span>
        align: center
        background:
          image:
            filename: aws.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">스마트팜</span>
        content: <span style="font-size:70%">스마트팜 애플리케이션 개발</span>
        align: center
        background:
          image:
            filename: smartfarm.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">수학</span>
        content: <span style="font-size:70%">AI와 관련된 수학</span>
        align: center
        background:
          image:
            filename: mathematics.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">개발</span>
        content: <span style="font-size:70%">핵심 기술을 이용한 풀스택 애플리케이션 개발</span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # 슬라이드 높이는 자동이나, 특정 높이로 강제할 수 있음 (예: '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # 슬라이드를 자동으로 전환할까요?
      loop: true
      # 슬라이드 전환 시간 (밀리초)
      interval: 3000
      spacing:
        padding: ['100px', '0', '0', '0']

  - block: collection
    content:
      title: 알림 및 소식
      subtitle:
      text:
      count: 3
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
