---
# Contact 위젯의 인스턴스.
# 문서: https://docs.hugoblox.com/getting-started/page-builder/
widget: contact

# 이 파일은 페이지 섹션을 나타냅니다.
headless: true

# 페이지에 이 섹션이 나타나는 순서.
weight: 50

title: 문의하기
subtitle:

content:
  # 이메일과 전화번호를 자동으로 링크하거나 텍스트로 표시할까요?
  autolink: true

  # 이메일 폼 제공자
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # 스팸을 줄이기 위해 CAPTCHA 도전 활성화?
      captcha: false

design:
  columns: '1'
---
