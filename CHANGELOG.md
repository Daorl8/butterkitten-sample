# CHANGELOG — Butter Kitten (버터키튼 · @butterkitten.bakery)

## v0.1 — 2026-09-28 (최초 시안 · 9.9 원페이지)
- **브리프(다올)**: 따뜻한 치유의 디저트 가게 · 고양이 컨셉 · 영어 위주 · 사장님 IG 캐릭터 활용 · 링크 3개(스마트스토어·유튜브·카카오) · 영문 폰트 Enfantine 유사 · 한글 한림명조/리디바탕/마루부리 계열 · 포장지처럼 흰 바탕+블랙, 포인트 베이지/아이보리 · 고양이 최대 활용 · 배경에 작은 발자국 군데군데.
- **폰트**: 영문 필기체 = **Playwrite FR Moderne**(프랑스 학교 필기체 계열 = Enfantine과 같은 장르, OFL; 로고 워드마크와도 결 일치) wght 350 인스턴스 서브셋 51KB. 영문 본문·라벨 = **Ubuntu**(포장지 "MENU·Best·Plain" 글자와 같은 계열, UFL) 400/500 서브셋. 한글 = **마루 부리**(네이버 공식 CDN · OFL · 시안). 폰트 체인 폴백 전부 산세리프(궁서 트랩 없음).
- **이미지**: IG 원본 113장(중복 1) 중 로고 2종(#3·#94) 흰 배경 언믹싱 알파화(눈 보존), 버터 안은 고양이 일러스트(#90) 블루 키잉 + 워드마크 위에서 절단, 발 일러스트(#99), 제품 사진 14컷 webp. 리포스트(obos·이룸미당·샌디버터·YP·가능지모 포스터) 제외. favicon·og-butterkitten.jpg(1200×630).
- **디자인**: 흰 바탕+잉크 #262626+아이보리 #F6F2E6+베이지 #E4D7BE. 고양이 모티프 = 포장지 MENU 모양 **고양이 머리 배지**(STORY/MENU/GIFT/FILM/VISIT) · **고양이 귀 버튼** · 히어로 사진 **고양이 머리 마스크** · Financier Plain에 **Best 고양이 배지**(포장지 그대로) · 버터 고양이가 선 위에 앉아 흔들흔들 · 배경 **베이지 발자국 타일**(460px에 5개, 크기·각도 다르게). 사진 모서리 직각·그림자 없음.
- **구성**: 헤더(Story·Menu·Gift·Film·Visit + Order) → 히어로(로고·"A warm little dessert shop, baked with heart."·스토어/카카오) → Story(작은 가게·제철 재료·재료 3종 라벨) → Menu(Kitten Dacquoise·Financier[Plain Best·Black Sesame]·Seasonal Cake + 이번 시즌 Dubai Chocolate·White Lemon Galette + 시기별 변동 안내, 가격 없음) → Gift(발바닥 포장) → Gallery 6 → Film(유튜브 nocookie 임베드) → Visit(주소 영/한·공릉역 2번 477m·월–토 12–20·일 휴무·전화·카카오 예약·구글 지도·네이버 지도 링크) → 블랙 푸터.
- **데이터 출처**: 소개·재료·주소·영업·전화 = 네이버 플레이스(다올 제공). Financier Plain(Best)·Black Sesame = 포장지 메뉴 사진. Dacquoise·Dubai Chocolate·White Lemon Galette = IG 게시물 문구. 유튜브 = oEmbed 확인("공릉동 베이커리 버터키튼" / 공릉동 장사하는 사람들).
- **QA**: 로컬 참조 누락 0 · JSON-LD 유효 · 태그/CSS 균형 · 앵커 5/5 · alt 17/17 · 이모지 0 · JS 문법 OK · AA(보조 텍스트 흰 7.2·아이보리 6.4). 라틴 서브셋 누락 = "→"만(마루부리/시스템 폴백). 모션 강제 재생·rAF 스크롤. ⚠️헤드리스 렌더 불가 → 배포 후 확인.
- **레포**: wrangler.toml(butterkitten-sample)·.assetsignore(img·문서·미사용 bk-cake3·bk-dacq-mint·ubuntu-700 제외).

### 보류/확인
- **후기 섹션 없음** — 실제 네이버 방문자 리뷰 원문 받으면 추가(9.9 구성 완성).
- 네이버에 "수(9/30) 휴무" 표기 — 날짜 붙은 임시 휴무로 보고 정기휴무는 일요일만 반영. 사장님 확인.
- 메뉴 품목명(Kitten Dacquoise 등 영문 표기)은 사진·IG 기준 작명 → 사장님 공식 영문명 확인.
- 마루 부리 CDN = 전체 폰트 로드(무거움) → 납품 시 서브셋 self-host.
