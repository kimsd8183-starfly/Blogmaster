# Naver Blog Strategist Skill Module

BlogMaster AI에서 네이버 블로그 콘텐츠 제작 Workflow가 사용할 수 있도록 `naver-blog-strategist` 스킬을 모듈화한 영역이다.

## Operations

- `keyword_strategy`: 메인/롱테일 키워드와 검색 의도 정의
- `title_thumbnail_hook`: 제목·썸네일·도입 후킹 생성
- `draft`: 본문 초안 생성
- `viraltest`: 발행 전 품질 자가점검
- `revise`: 점검 결과를 반영한 보완
- `publish_package`: 본문·이미지 가이드·CTA·태그·출처를 묶은 발행 패키지 생성

## 품질 게이트

기본 Workflow는 VIRALTEST 95점 미만을 보완 대상으로 처리한다. VIRALTEST는 실제 네이버 검색 알고리즘 점수가 아니다.

## 원칙

- 검색 순위·조회수·팔로워 증가를 보장하지 않는다.
- 검색 알고리즘 우회나 조작을 목적으로 하지 않는다.
- 최신 정보는 출처를 확인한다.
- 경험하지 않은 내용을 직접 경험한 것처럼 작성하지 않는다.
- 광고·협찬·제휴는 명시한다.
