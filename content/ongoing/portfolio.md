---
# Portfolio 위젯을 사용하여 생성된 섹션입니다.
# 이 섹션은 `content/project/`에서 콘텐츠를 표시합니다.
# 자세한 내용은 https://docs.hugoblox.com/widget/portfolio/를 참조하세요.
widget: portfolio

# 이 파일은 페이지 섹션을 나타냅니다.
headless: true

# 이 섹션이 페이지에서 나타나는 순서입니다.
weight: 30

title: ''
subtitle: ''

content:
  # 표시할 페이지 유형. 예: ongoingproject.
  page_type: ongoingproject

  # 기본 필터 인덱스 (예: 0은 아래의 첫 번째 `filter_button` 항목에 해당).
  filter_default: 0

  # 필터 툴바 (선택 사항).
  # 원하는 만큼 필터 (`filter_button` 항목)를 추가하거나 제거할 수 있습니다.
  # 모든 항목을 표시하려면 `tag`를 "*"로 설정하십시오.
  # 특정 태그로 필터링하려면 `tag`를 기존 태그 이름으로 설정하십시오.
  # 툴바를 제거하려면 전체 `filter_button` 블록을 삭제하십시오.
  filter_button:
    - name: 모두
      tag: '*'
    - name: 클라우드 컴퓨팅
      tag: CC
    - name: 스마트팜 애플리케이션
      tag: SF

design:
  columns: '1'
  view: masonry
  flip_alt_rows: true
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---
