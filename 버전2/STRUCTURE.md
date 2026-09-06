# STRUCTURE — 카페 비미 버전2 (미니멀+한옥)

## 파일
- `index.html` — 단일 페이지(인라인 CSS/JS).
- `bimi-word.png` — bimi 워드마크(V1 재사용).
- `favicon.png`·`apple-touch-icon.png` — 팜 마크(V1 재사용).
- `v2-*.webp` — 지점 실사진 대형 12컷(hero·lounge·counter·interior·shelf·drip·dessert·window·chairs·gw-sign·jj-ext / calm=미사용).
- `og-bimi-v2.jpg` — 1200×630 공유 썸네일(한옥 창밖+워드마크).
- `.assetsignore` — .git/문서/미사용(calm) 제외.

## 섹션 순서
1. Header(#hdr) — 워드마크 + 얇은 nav(Philosophy/Space/Menu/Location)
2. Hero — 명조 헤드라인 "미니멀 위에 전통을 얹다" + 한옥 창밖 대형사진
3. 창살 디바이더(.lattice)
4. Philosophy(#philosophy) — 비미 디자인 스토리 + 라운지 사진
5. Space(#space) — 2열 대형 미니멀 갤러리 7컷(span2 피처 1 + 6, 지점 캡션)
6. 창살 디바이더
7. Menu(#menu) — 타이포 리스트(핸드드립·음료·디저트, 사진 없음)
8. Location(#location) — 광주·전주 2지점 카드(사진+실데이터)
9. 다크 푸터 + 모바일 퀵바(전화·네이버)

## 디자인 키
- 팔레트: paper#FAF8F3·paper2#F1EDE3·ink#262320·oak#C7A87C·oak-d#836638·clay#A85C43(극절제)·line#E5DFD1.
- 폰트: 헤딩=Fraunces+Noto Serif KR(명조), 라벨/nav=Inter, 본문=Pretendard.
- 모티프: 창살(.lattice) 격자 라인 = repeating-linear-gradient 세로살 + 상하 창틀 헤어라인.

## 교체 대상 (납품/확정 시)
- 폰트 CDN → self-host subset.
- 도메인 bimi-v2-sample.lgt3232.workers.dev → 확정 도메인(og·canonical·JSON-LD).

## 데이터 출처
- V1과 동일(사용자 제공 네이버 광주 place 1404651453 / 전주 place 2017645174).
- 사진: img/gwangju·img/Jeonju(사용자 제공).
