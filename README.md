# Blabla Korea — 한국어 수업 사이트

현재 임시 주소: https://mangocurly.github.io/blablakorea-cours/
최종 주소(예정): https://www.blablakorea.fr

## 구조
- `pages/fr`, `pages/en` — 페이지 본문. 원본 Squarespace의 칸 배치(격자 좌표)를 그대로 옮긴 HTML.
- `_articles_fr` — 블로그 글 14개.
- `_data/site.yml` — 메뉴·꼬리말 문구.
- `assets/css/site.css` — 공통 스타일(색·글꼴·글자 크기는 원본 계측값).
- `assets/fonts` — Almarai, Libre Baskerville (SIL Open Font License).

## 결제·예약·테스트 연결
- Stripe 결제 링크 6개는 원본과 동일.
- 예약: https://reserver.blablakorea.fr (원본 삽입 코드 그대로)
- 레벨테스트: https://mangocurly.github.io/blabla-korean-level-test/ (원본 삽입 코드 그대로)

## blablakorea.fr 로 옮길 때
1. `_config.yml`의 `url`을 `https://www.blablakorea.fr`로, `baseurl`을 `""`로 바꾼다.
2. 저장소 루트에 `CNAME` 파일을 만들고 `www.blablakorea.fr` 한 줄을 넣는다.
3. 도메인 연결은 메일(MX) 레코드를 건드리지 않는다.

## 문의 양식
`_config.yml`의 `form_endpoint`가 비어 있으면 메일 링크(contact@blablakorea.com)를 보여 준다.
