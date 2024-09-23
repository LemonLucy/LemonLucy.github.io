---
# Experience 위젯의 인스턴스.
# 문서: https://docs.hugoblox.com/page-builder/
widget: experience

# 이 파일은 페이지 섹션을 나타냅니다.
headless: true

# 페이지에 이 섹션이 나타나는 순서.
weight: 20

title: 경력
subtitle:

# 경력의 날짜 형식
#   https://docs.hugoblox.com/customization/#date-format 를 참조하세요.
date_format: 2024년 9월

# 경력 사항
#   아래 `experience` 항목을 원하는 만큼 추가/삭제하세요.
#   필수 항목은 `title`, `company`, 및 `date_start`입니다.
#   현재 직장인 경우 `date_end`를 비워 두세요.
#   여러 줄 설명을 작성할 때는 YAML의 `|2-` 접두사를 사용하세요.
experience:
  - title: LGaimers
    company: GenCoin
    company_url: ''
    company_logo: org-gc
    location: 캘리포니아
    date_start: '2023-07-01'
    date_end: ''
    description: |2-
        담당 업무:
        
        * 분석
        * 모델링
        * 배포

  - title: 반도체 물리학 교수
    company: University X
    company_url: ''
    company_logo: org-x
    location: 캘리포니아
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: 전자 공학 강의 및 반도체 물리 연구를 수행하였습니다.

design:
  columns: '1'
---
