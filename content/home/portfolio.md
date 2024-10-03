---
# 포트폴리오 위젯으로 생성된 섹션입니다.
# 이 섹션은 `content/project/`의 내용을 표시합니다.
# 자세한 내용은 https://docs.hugoblox.com/widget/portfolio/에서 확인하세요.
widget: portfolio

# 이 파일은 페이지 섹션을 나타냅니다.
headless: true

# 이 섹션이 페이지에 나타나는 순서입니다.
weight: 30

title: ''
subtitle: ''

content:
  # 표시할 페이지 유형. 예: project.
  page_type: project

  # 기본 필터 인덱스 (예: 0은 아래의 첫 번째 `filter_button` 인스턴스에 해당).
  filter_default: 0

  # 필터 도구 모음 (선택 사항).
  # 원하는 만큼 필터(`filter_button` 인스턴스)를 추가하거나 제거할 수 있습니다.
  # 모든 항목을 표시하려면 `tag`를 "*"로 설정하세요.
  # 특정 태그로 필터링하려면 기존 태그 이름을 설정하세요.
  # 도구 모음을 제거하려면 전체 `filter_button` 블록을 삭제하세요.
  filter_button:
    - name: 전체
      tag: '*'
    - name: 머신 러닝
      tag: ML
    - name: 운영 체제
      tag: OS
    - name: 리눅스
      tag: Linux

design:
  columns: '1'
  view: masonry
  flip_alt_rows: true
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---
