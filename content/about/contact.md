--- 
# 연락처 위젯의 인스턴스입니다.
# 문서: https://docs.hugoblox.com/getting-started/page-builder/
widget: contact

# 이 파일은 페이지 섹션을 나타냅니다.
headless: true

# 이 섹션이 페이지에 나타나는 순서입니다.
weight: 50

title: 연락하기
subtitle:

content:
  # 이메일과 전화번호를 자동으로 링크할지 또는 텍스트로 표시할지?
  autolink: true

  # 이메일 양식 제공자
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # 스팸을 줄이기 위해 CAPTCHA 챌린지를 활성화할지?
      captcha: false

design:
  columns: '1'
---
