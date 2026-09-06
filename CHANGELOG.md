# CHANGELOG — 카페 비미 BIMI · 버전2 (미니멀리즘+한옥)

## v2.3 (2026-09-05) 손글씨 폐기 → 정제 세리프(정갈 우선·한국적 차선)
- 다올: 붓글씨/손글씨 느낌 완전 폐기. "한국적"보다 **정갈함 우선**. → 명조 방향 채택.
- **제목 폰트**: Caveat(손글씨) → **Fraunces(라이트 300)** + 한글 폴백 **Noto Serif KR** 명조. 영문 큰제목은 정제 세리프로, 한글이 오면 명조로. 헤딩 자간 -.015em·라이트 웨이트로 정갈하게(크기도 하향).
- **무늬**: 붓 스트로크(一) → **창살(문살) 격자 디바이더** 복귀(기하학·한국 전통·비손글씨).
- 팔레트(순백+블랙+인장red)·영어 헤딩·공간 지점분리 유지. em=tradition(seal). (대안: 제목폰트 자체를 한국 명조 Gowun Batang/Nanum Myeongjo로 바꾸는 것도 가능—라틴은 더 담백.)

## v2.2 (2026-09-05) 제목폰트 정갈하게 + 헤딩 영어 + 공간 지점분리
- **메인 제목 폰트**: Nanum Brush Script(너무 날림) → **Caveat**(정갈한 손글씨). 헤딩만 교체, 나머지(Inter·Pretendard) 유지.
- **큰 제목 전부 영어화**: 히어로 "Minimal, layered with tradition." / Philosophy "Emptied space, filled with tradition." / Space "A room to empty, and to stay." / Menu "A cup of the basics, a plate of care." / Location "Two spaces, one bimi." (em=tradition, seal red). 본문·라벨 한글은 유지, og/footer 브랜드 카피 한글도 유지(제목 아님).
- **공간 갤러리 지점 분리**: 혼합 그리드 → **Gwangju(4컷: counter·calm·interior·shelf) / Jeonju(4컷: drip·dessert·window·chairs)** 두 그룹으로, 각 그룹 라벨. v2-calm 재사용(assetsignore 해제).

## v2.1 (2026-09-05) 순백+블랙 모던 + 붓글씨 전통
- 다올: 배경 **완전 순백(#FFFFFF)** + **블랙**으로 모던하게, 폰트/무늬를 **손글씨(붓글씨)**로 전통 분위기. **베이지·아이보리·오크 전면 제거**.
- 팔레트 재정의: paper #FFFFFF·paper2 #F7F7F7(뉴트럴 그레이)·ink #141414·ink2 #565656·line #E7E7E7 + 인장 red(#B4392C, 시그니처·em 극절제). 오크/클레이/베이지 토큰 삭제.
- 폰트: 헤딩 명조(Fraunces+NotoSerifKR) → **붓글씨 Nanum Brush Script**(한글 헤드라인). 라벨/nav/가격/지점명=Inter(모던 블랙), 본문=Pretendard. 붓글씨는 크기↑·자간0·이탤릭 제거(한글 가짜슬랜트 방지), em=인장red.
- 무늬: **창살(격자) 디바이더 → 붓 스트로크(一) SVG** 디바이더로 교체.
- og 밴드 흰색 재생성. AA: ink 18.4·ink2 7.3·seal 5.9(시그니처)·흰/먹버튼 18.4.

## v2.0 (2026-09-05) 미니멀리즘 위에 한옥 — 별도 버전
- **컨셉**: 다올 요청 — 인테리어 스튜디오 '비미 디자인'의 IKEA풍 미니멀리즘 위에 한옥 전통을 얹은 결. V1(감성/색연필톤)은 그대로 두고 **완전 별도 버전**으로 `bimi-sample/버전2/` 에 제작. GitHub 레포는 사용자가 새로 생성.
- **톤**: 한지 화이트(#FAF8F3)+오크우드(#C7A87C/#836638)+먹(#262320), 여백 중심, 하드라인·박스 최소. 포인트=**창살(격자) 라인 디바이더**(repeating-linear-gradient 세로 살 + 창틀 헤어라인). 클레이(#A85C43)는 시그니처 라벨에만 극절제.
- **폰트**: 헤딩=**명조**(Fraunces 라틴 + Noto Serif KR 한글, weight 300 라이트) — 전통·정제. 라벨/nav=Inter(대문자 레터스페이싱, 스칸디 미니멀). 본문=Pretendard. 3폰트지만 역할 분리(디스플레이 명조/UI 산세/본문).
- **구성**: 헤더(워드마크+얇은 nav) → 히어로(명조 헤드라인 "미니멀 위에 전통을 얹다" + 한옥 창밖 대형사진) → 창살 디바이더 → Philosophy(비미 디자인 스토리) → Space(2열 대형 미니멀 갤러리 7컷, 지점 캡션) → 창살 디바이더 → Menu(타이포 리스트, 사진 없음) → Location(광주·전주 2지점 실데이터) → 다크 푸터 + 모바일 퀵바.
- **이미지**: 지점 폴더(img/gwangju·img/Jeonju)에서 미니멀·한옥 톤 대형 webp 12컷(v2-*, cap 1600, 917KB). v2-calm 미사용→assetsignore. 워드마크·favicon은 V1 재사용.
- **실데이터**: V1과 동일(광주 place 1404651453·070-7537-0480 / 전주 place 2017645174·0507-1456-7787·목휴무). 메뉴 동일.
- **마감/안전**: color-scheme·keep-all·overflow-x, 리빌 html.js 게이팅+데스크톱전용+2.2s폴백+noscript, 앵커 rAF, reduced-motion 리빌 강제(하우스룰), a11y(aria·focus-visible·alt), JSON-LD. AA: ink/bg 14.7·ink2 5.4·oak-d 5.0(라벨)·clay 4.6·흰글씨/먹버튼 14.7.
- **도메인**: og·canonical·JSON-LD = bimi-v2-sample.lgt3232.workers.dev(임시). 사용자 새 레포·도메인 확정 시 치환.
- ⚠️미결: 폰트 self-host(납품), 라이브 육안검증(명조·창살·모바일), 사용자 GitHub 레포 생성·업로드.
