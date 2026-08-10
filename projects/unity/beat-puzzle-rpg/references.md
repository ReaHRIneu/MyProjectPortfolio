# 레퍼런스 리서치

- **작성일**: 2026-08-10
- **버전**: v0.4.0
- **연관 문서**: [01-concept.md](./01-concept.md)
- **참고**: 여기 정리한 게임들은 직접 플레이가 아닌 웹 리서치 기반 자료입니다. 직접 플레이한 타 게임 리뷰는 [`library/타게임리뷰분석/`](../../../library/타게임리뷰분석/)에 별도로 기록합니다.

## 유사 게임 목록 (요약)

| 게임 | 장르 조합 | beat-puzzle-rpg와 유사한 점 | beat-puzzle-rpg와 다른 점 |
| --- | --- | --- | --- |
| Lumines / Lumines Arise | 퍼즐 × 리듬 | 블록 조작 + 비트 동기화 | RPG 성장 요소 없음 |
| Tetris Effect: Connected | 퍼즐 × 리듬(연출) | 단순 퍼즐 로직 + 감각적 비트 연출 | 로직에 리듬 판정이 직접 개입하지 않음(연출 위주), RPG 없음 |
| QQQbeats!!! (Taito, 2025) | 퍼즐(버블슈터) × 리듬 | 같은 색 맞추기 퍼즐 + 버튼을 비트에 맞춰 입력하는 이중 판정 구조 | RPG 성장 없음. 3사 중 퍼즐+리듬 결합 방식이 beat-puzzle-rpg와 가장 근접한 사례 |
| Thumper | 리듬 × 액션 | 단순 입력 + 미니멀 비주얼로 판정에 집중 | 퍼즐/RPG 요소 없음, 트랙 러너형 |
| Muse Dash | 리듬 × 액션 | 비트 노트 판정 + 캐릭터/코스튬 수집·성장 | 퍼즐 요소 없음, 진행이 성장에 종속되지 않음(스코어 위주) |
| Crypt of the NecroDancer | 리듬 × 로그라이크 RPG | "박자 정확도 → 배율 → 보상" 단일 규칙, 캐릭터별 스탯 다양화 | 퍼즐(피스 배치) 요소 없음, 던전 탐험형 |
| Cadence of Hyrule | 리듬 × 액션 RPG | 박자 유지 시 배율 상승/실패 시 패널티, 장비·성장 요소 존재 | 퍼즐 요소 없음, 오픈월드 탐험형 |
| Theatrhythm Final Fantasy | 리듬 × RPG(파티 성장) | 곡 클리어로 캐릭터 XP 획득 후 레벨업하는 구조 — beat-puzzle-rpg의 "라운드 종료 후 성장 재화 환산"과 유사 | 퍼즐 요소 없음, 성장치가 실제 성과에 거의 영향 없음(치장에 가까움) |
| Patapon | 리듬 × 전략 RPG | 정확한 박자 입력 성공 시 "피버 모드"로 전체 효율 상승 — 콤보 배율 아이디어와 유사 | 퍼즐 요소 없음, 부대 지휘 전략 장르 |

**시사점**: 퍼즐+리듬 결합(Lumines, Tetris Effect, QQQbeats!!!)과 리듬+RPG 결합(Crypt of the NecroDancer, Cadence of Hyrule, Theatrhythm, Patapon) 사례는 각각 존재하지만, 세 축(퍼즐×리듬×RPG)을 동시에 핵심 루프에 넣은 사례는 리서치 범위에서 확인되지 않음. 특히 QQQbeats!!!(2025)가 "퍼즐 판정 + 리듬 입력"을 가장 가깝게 결합했다는 점에서, 여기에 RPG 성장 루프를 더하는 것이 beat-puzzle-rpg의 실질적 차별점.

## 퍼즐×리듬 계열

### Lumines (시리즈 / Lumines Arise)

- **핵심 루프**: 2×2 블록을 회전/이동시켜 같은 색 블록을 모으면, 음악 BPM에 맞춰 좌우로 훑는 "타임라인"이 지나갈 때 완성된 블록이 클리어됨
- **리듬 연동**: 타임라인 속도가 곡의 BPM에 종속 — 판정이 아니라 "클리어 타이밍"이 음악과 묶여 있는 방식
- **비주얼**: 블록/이펙트가 비트에 맞춰 색과 형태로 반응하는 미니멀 지오메트릭 스타일. 최신작 *Lumines Arise*는 "버스트 게이지"를 모아 타임라인 진행을 지연시키고 대형 콤보를 만드는 Burst Mode 추가
- **참고할 점**: "판정 타이밍"과 "클리어(정산) 타이밍"을 분리하는 아이디어 — beat-puzzle-rpg는 배치 타이밍 자체를 판정하지만, Lumines처럼 콤보를 모았다가 한 번에 터뜨리는 버스트형 메커니즘을 성장 재화 배율 이벤트로 응용 가능

### Tetris Effect: Connected

- **핵심 루프**: 테트리스 기본 룰(라인 클리어) + 스테이지별로 음악/배경/이펙트가 실시간으로 진화
- **리듬 연동**: 라인을 지울 때마다 클리어 단수에 따라 다른 사운드가 재생되고 배경 음악과 동기화 — "판정→사운드 피드백"이 즉각적
- **비주얼**: 30개 이상의 스테이지가 각각 다른 음악/그래픽 스타일과 배경을 가지며, 플레이에 반응해 배경이 변형됨 (Rez Infinite, Lumines 제작자 미즈구치 테츠야 작품)
- **참고할 점**: 게임 로직(테트리스)은 단순하게 유지하면서 감각적 연출(사운드+비주얼 동기화)만으로 몰입감을 극대화하는 방식 — beat-puzzle-rpg의 "미니멀 비주얼 + 비트 집중" 방향과 가장 가까운 레퍼런스

### QQQbeats!!! (Taito, 2025)

- **핵심 루프**: 버블슈터형 퍼즐(같은 색 구슬 맞추기)과 배경 음악의 비트에 맞춰 버튼을 입력하는 리듬 판정이 동시에 진행되는 이중 판정 구조
- **참고할 점**: 퍼즐 판정(색/패턴 매칭)과 리듬 판정(입력 타이밍)을 별개 축으로 동시에 요구하는 가장 최근(2025) 사례 — beat-puzzle-rpg의 "비트에 맞춰 퍼즐 피스를 배치"하는 단일 판정(정확도가 곧 타이밍) 방식과 비교했을 때, QQQbeats!!!처럼 두 판정을 분리할지 beat-puzzle-rpg처럼 하나로 합칠지가 핵심 차별화 지점이 됨을 확인시켜줌

## 리듬×액션 계열

### Thumper

- **핵심 루프**: 컨트롤 스틱 + 버튼 2개 입력만으로 트랙 위 빛나는 구간을 정확한 타이밍에 통과. 진행할수록 새 기믹(장애물, 회전, 보스 패턴) 추가
- **비주얼**: 80년대 SF 모티프 + 러브크래프트풍 사이키델릭. 게임플레이에 불필요한 시각 정보는 전부 덜어내는 "빼기(subtractive)" 방식의 미니멀리즘
- **참고할 점**: 입력을 극도로 단순하게 유지(2버튼)하면서 난이도는 새로운 기믹 추가로 확장하는 구조 — beat-puzzle-rpg의 "조작은 단순, 난이도는 패턴/BPM으로 확장" 설계와 방향이 일치. 시각 노이즈를 최소화해 리듬 판정에 집중시키는 미니멀리즘 원칙도 그대로 적용 가능

### Muse Dash

- **핵심 루프**: 2버튼(지상/공중)으로 좌우 두 레인의 적을 비트에 맞춰 처치. 노트/하트 수집, 스파이크 회피
- **성장 시스템**: 플레이로 얻은 재화로 새 캐릭터·엘핀(보조 능력)·코스튬을 해금. 캐릭터/코스튬마다 고유 능력이 스코어에 영향
- **참고할 점**: 리듬 판정 성과와 별개로 "수집 → 캐릭터 해금"이라는 성장 루프가 붙어있지만, 성장치가 다음 판정 난이도에 되먹임되지는 않음 — beat-puzzle-rpg는 성장(스탯)이 다음 스테이지 난이도 대응력에 실제로 영향을 주도록 설계해 Muse Dash보다 성장의 체감을 강화할 여지가 있음

## 리듬×RPG/로그라이크 계열

### Crypt of the NecroDancer

- **핵심 루프**: 비트마다 한 턴씩 진행되는 로그라이크 던전 크롤러. 이동/공격/루팅이 모두 박자에 맞아야 하며, 박자를 놓치지 않고 연속 처치하면 코인 배율이 오름
- **성장 시스템**: 다이아몬드를 모아 영구 강화(체력, 장비)를 해금하고, 캐릭터별로 스탯/스킬이 다른 다수의 플레이 가능 캐릭터 존재
- **참고할 점**: "박자를 못 맞추면 페널티, 잘 맞추면 배율 상승"이라는 단순한 규칙 하나로 리듬과 전투(RPG 액션)를 자연스럽게 묶은 사례. beat-puzzle-rpg에서도 퍼즐 배치 정확도-콤보 배율-성장 재화 획득량을 하나의 규칙으로 엮는 데 참고 가능

### Cadence of Hyrule

- **핵심 루프**: Crypt of the NecroDancer 엔진 기반 — 박자에 맞춰 이동/공격하면 배율 상승, 박자를 놓치면 페널티 및 적의 무료 공격 허용
- **성장 시스템**: 장비/아이템 수급으로 전투력 강화, 절차적으로 생성되는 던전 탐험
- **참고할 점**: "박자 유지=배율 상승, 실패=페널티"라는 규칙이 액션 RPG 톤에서도 그대로 통한다는 사례 — beat-puzzle-rpg의 퍼즐 배치 정확도에도 동일한 상벌 구조(정확→배율, 실패→패널티)를 적용할 근거가 됨

### Theatrhythm Final Fantasy

- **핵심 루프**: 노트를 탭/스와이프/홀드로 처리해 곡을 클리어. Field/Battle/Event 세 가지 모드로 리듬 입력의 맥락만 바뀜
- **성장 시스템**: 곡 클리어마다 파티 캐릭터가 경험치를 얻어 레벨업하지만, 스탯 구성이 실제 클리어 성패에는 거의 영향을 주지 않음(연출/치장에 가까움)
- **참고할 점**: 정반대 반면교사 사례 — 성장 시스템이 실제 코어 루프의 난이도/전략에 영향을 주지 못하면 RPG 요소가 장식으로 전락함. beat-puzzle-rpg는 스탯 성장이 실제로 다음 스테이지 공략에 유의미한 영향을 주도록 설계해야 한다는 반면교사

### Patapon

- **핵심 루프**: 4개의 리듬 커맨드(PATA/PON/CHAKA/DON)를 정박에 입력해 부대에게 이동/공격 등을 명령. 연속 성공 시 "피버 모드"로 전체 효율 상승
- **성장 시스템**: 병과(창병/궁병/기병 등)를 해금하고 전투 상황에 맞게 배치하는 전략적 성장
- **참고할 점**: "정확한 박자 입력 연속 성공 → 전체 효율 상승(피버)"이라는 구조가 beat-puzzle-rpg의 콤보 시스템에 직접 적용 가능한 형태 — 일정 콤보 이상 유지 시 짧은 시간 동안 성장 재화 획득량을 배로 늘리는 피버 타임 도입을 검토할 만함

## 일상 감성 × 현대 사회 계열 (테마 전환 대응 리서치)

> 2026-08-11 테마 전환(추상적 미니멀 SF → 현대 사회·일상적 감성) 이후, 위 퍼즐×리듬×RPG 계열 게임들은 **메커니즘 참고용**으로 유지하고, 이 절에서는 **아트/톤/서사 전달 방식 참고용**으로 별도 조사했다. 모바일(Android) 실사례와 "퍼즐 메커니즘×감정 서사" 결합 사례를 우선했다.

### 요약

| 게임 | Android 출시 여부 | 퍼즐×감정 결합 정도 | beat-puzzle-rpg와 가장 가까운 지점 |
| --- | --- | --- | --- |
| Florence (Mountains, 2018) | O (2018-03-14) | 매우 높음 — 퍼즐 난이도 자체가 감정 상태의 은유 | "퍼즐=감정 정리" 컨셉의 직접적 선례 |
| Old Man's Journey (Broken Rules, 2017) | O | 중간 — 대사 없는 회상+환경 퍼즐 | 모바일 터치 네이티브 조작 + 무대사 정서 전달 |
| Unpacking (Witch Beam, 2021 / 모바일 2023) | O (2023-08-24) | 중간 — 오브젝트 배치로 인생 챕터 암시 | 대사 없이 소품/색으로 장면(하루 속 순간) 암시 |
| Coffee Talk (Toge Productions, 2020 / 모바일 2026) | O (2026-03-20) | 낮음~중간 — 음료 제조가 대화 분기에 영향 | 판타지 표면 아래 현실적 현대 고민을 다루는 방식 |
| TOEM (Something We Made, 2021 / 모바일 Snapbreak 포트) | O (Google Play 확인) | 낮음 — 사진 찍기가 공감의 매개 | 흑백/미니멀 컬러로도 온기 전달 가능함을 보여주는 반례 |
| Behind the Frame: The Finest Scenery (Silver Lining Studio, 2021) | O (Crunchyroll 앱 경유) | 매우 높음 — 그림 퍼즐 완성=기억 회복 | Florence와 함께 "퍼즐 완성=감정 회복" 메타포의 핵심 선례 |
| A Short Hike (Adam Robinson-Yu, 2019) | **X (모바일 미출시, 확인 필요 아님 — 공식 미출시 확정)** | 낮음 | 파스텔 힐링 무드만 참고, 모바일 사례로는 인용 부적절 |
| Chicory: A Colorful Tale (Greg Lobanov, 2021) | **X (모바일 미출시)** | 높음이나 우울/불안 등 헤비 톤 | 톤이 무거워 이번 기준(캐주얼~미드코어)에서 제외 |
| Alba: A Wildlife Adventure (ustwo games, 2020) | **X (Apple Arcade iOS 전용, Android 정식 출시 미확인)** | 낮음 | Android 타겟에 부적합, 참고만 |
| A Little to the Left (Secret Mode, 2022 / 모바일 2024) | O (2024-11-28) | 낮음(스토리 거의 없음, 순수 정리 퍼즐) | 아늑한 톤+터치 정리 퍼즐의 보조 참고 사례 |

### Florence (Mountains, 2018)

- **배경/설정**: 25세 여성 Florence Yeoh의 현대 도시 일상. 무기력한 반복 업무 속에서 공원에서 첼리스트 Krish를 만나 연애가 시작되고, 갈등을 거쳐 결별하는 과정을 20개 챕터·약 30분 분량으로 그린다.
- **비주얼 스타일**: 손그림 만화책(코믹북) 스타일의 컷/프레임 구조. 장면의 감정에 따라 컬러 팔레트가 바뀐다(설렘=밝고 선명한 색, 갈등=탁하고 어두운 색).
- **감정/서사 전달 방식**: 텍스트 대사가 거의 없이 미니게임(퍼즐)만으로 진행. 대표적으로 "대화 퍼즐"에서 관계가 편해질수록 조각 수가 줄어 퍼즐이 쉬워지고, 다툼이 심해지면 조각이 늘고 서로 안 맞아 어긋난다. 첼로(Krish)와 피아노(Florence) 라이트모티프로 인물을 음악적으로 구분.
- **참고할 점**: "퍼즐 난이도 = 감정 상태"를 직접 매핑하는 방식은 beat-puzzle-rpg의 "비트에 맞춰 퍼즐을 배치 = 그 순간의 감정을 정리"라는 컨셉과 가장 근접한 선행 사례. 스테이지(하루의 장면)별로 판정 난이도·패턴을 그 장면의 감정(설렘=쉽고 유려한 배치, 피로=복잡하고 불규칙한 배치, 안도=클리어 후 자연스럽게 정렬)에 맞춰 디자인하는 구체적 근거로 인용 가능.
- **출처**: [Florence (video game) - Wikipedia](https://en.wikipedia.org/wiki/Florence_(video_game)) · [Review: Florence – Destructoid](https://www.destructoid.com/reviews/review-florence/) · [Florence - App Store](https://apps.apple.com/us/app/florence/id1297430468)

### Old Man's Journey (Broken Rules, 2017)

- **배경/설정**: 노인이 한 통의 편지를 받은 뒤 여정을 떠나고, 이동 중 짧은 회상으로 그의 인생(가족과의 갈등과 화해)이 드러난다.
- **비주얼 스타일**: 손그림 수채화풍의 다채로운 풍경, 파스텔 톤. 시간대·계절에 따라 배경 색이 변화.
- **감정/서사 전달 방식**: 대사를 완전히 배제하고(dialogue-free), 짧은 단일 컷 애니메이션(예: 빗속에서 집을 바라보는 남자)과 지형 조작만으로 정서를 전달. 회상 장면이 노인의 인생사를 서정적으로 암시.
- **게임플레이**: 언덕 지형을 드래그해 높낮이를 조절하여 캐릭터가 걷고 오를 길을 만드는 환경 퍼즐. 모바일 터치에 최적화된 실제 사례.
- **참고할 점**: 터치 한 번으로 지형/환경을 조작하는 모바일 네이티브 조작감과, 대사 없이 애니메이션+음악만으로 감정을 전달하는 방식을 참고. beat-puzzle-rpg의 짧은 장면(하루 속 순간) 구성에도 대사 대신 비주얼+음악만으로 정서를 전달하는 원칙을 강화하는 근거가 됨.
- **출처**: [Old Man's Journey - Wikipedia](https://en.wikipedia.org/wiki/Old_Man%27s_Journey) · [공식 사이트](http://www.oldmansjourney.com/) · [Google Play](https://play.google.com/store/apps/details?id=es.brokenrul.oldmansjourney&hl=en_IN)

### Unpacking (Witch Beam, 2021 / 모바일 포트 2023)

- **배경/설정**: 1997~2018년까지, 한 여성의 인생을 8번의 이사(연도별 단계)로 그린다. 총 35개 방을 배경으로 상자를 풀어 방을 채우는 행위 자체가 인생의 챕터가 된다.
- **비주얼 스타일**: 순수 픽셀아트, 차분하고 미니멀한 톤. IGDA 어워드 "2D Animation"·"2D Environment Art" 부문 수상.
- **감정/서사 전달 방식**: 대사가 전혀 없는(wordless) 경험. 졸업장, 이혼 후 사라진 물건, 새로운 반려동물 등 배치되는 오브젝트 자체가 인물의 삶과 관계 변화를 암시하는 "오브젝트 스토리텔링".
- **게임플레이**: 상자 속 물건을 꺼내 방에 배치하는 퍼즐. 일부는 정해진 자리가 있고 일부는 자유 배치.
- **모바일**: 2023년 8월 24일 iOS/Android 동시 출시, $10 프리미엄.
- **참고할 점**: 대사 없이 "오브젝트/공간 배치"만으로 인생의 한 챕터를 전달하는 방식이 beat-puzzle-rpg가 스테이지(출근길/회의실 등)마다 텍스트 없이 배경 소품·컬러만으로 상황을 암시하는 데 실질적으로 참고됨. 드래그 배치 조작이 iOS/Android 양쪽에서 잘 작동한 사례이기도 함.
- **출처**: [Unpacking (video game) - Wikipedia](https://en.wikipedia.org/wiki/Unpacking_(video_game)) · [Engadget: 모바일 출시 발표](https://www.engadget.com/zen-moving-game-unpacking-comes-to-android-and-ios-on-august-24th-214513079.html) · [TouchArcade](https://toucharcade.com/2023/08/01/unpacking-iphone-ipad-android-release-date/) · [Pocket Gamer](https://www.pocketgamer.com/unpacking/out-now/)

### Coffee Talk (Toge Productions, 2020 / 모바일 2026-03-20)

- **배경/설정**: 현대(2020년대) 시애틀을 무대로 한 "얼터너티브 현실"(엘프·오크·인어 등 판타지 종족이 인간과 함께 사는 도시)이지만, 다루는 갈등은 이민, 커리어 고민, 인간관계, 자기정체성 등 매우 현실적인 현대 사회 이슈. 심야 카페에서 손님들의 사연을 듣는 구조.
- **비주얼 스타일**: 1990년대 아니메(카우보이 비밥, 공각기동대)·PC-98 비주얼노벨 감성의 도트그래픽. 아늑한 분위기를 위한 갈색(브라운) 계열 팔레트. 로파이 칠합 OST.
- **감정/서사 전달 방식**: 대화(텍스트) 중심의 비주얼노벨. 음료 제조가 단순 장식이 아니라 대화의 분기·결과에 실제로 영향을 주는 경량 퍼즐(레시피 조합)로 기능 — "행위(만들기)가 감정적 결과에 영향"을 주는 구조.
- **참고할 점**: 판타지 껍데기를 쓰고 있지만 실질적으로 "현대 사회의 소소한 고민"을 다루는 방식(설정은 비틀되 감정은 현실적)과, 대화 사이에 넣는 가벼운 행위형 미니게임이 서사에 영향을 주는 설계. 밤/도시 분위기를 색감으로 압축한 브라운 팔레트 활용법을 참고할 만함.
- **출처**: [Coffee Talk (video game) - Wikipedia](https://en.wikipedia.org/wiki/Coffee_Talk_(video_game)) · [DroidGamers](https://www.droidgamers.com/news/coffee-talk-episode-1/) · [Prism News: 모바일 출시](https://www.prismnews.com/hobbies/mobile-gaming/coffee-talk-arrives-on-ios-and-android-bringing-cozy-caf)

### TOEM (Something We Made, 2021 / 모바일 Snapbreak 포트)

- **배경/설정**: 스칸디나비아풍 도시·마을들을 여행하며 "토엠"이라는 자연 현상을 보러 산에 오르는 사진작가 청년의 여정. 마을 주민들의 소소한 부탁을 들어주는 옴니버스식 구성.
- **비주얼 스타일**: 흑백 손그림, 팝업북/종이공예에서 영감받은 입체감 있는 2D+3D 혼합 스타일.
- **감정/서사 전달 방식**: 텍스트(말풍선·편지)로 짧은 대화를 전달하되, 핵심은 NPC의 사소한 부탁을 사진으로 해결하는 행위 — "사진 찍기"가 관찰과 공감의 매개가 됨.
- **모바일**: Snapbreak Games를 통해 iOS/Android로 출시(Google Play `com.snapbreak.toem`), 데모 무료+약 $7.99 언락 방식. **주의**: 영문 Wikipedia 문서에는 이 모바일 포트가 아직 반영되지 않아 "모바일 미출시"로 오기되어 있음 — Google Play 스토어 리스팅과 Games Press 보도로 실제 출시를 별도 확인함.
- **참고할 점**: 흑백+최소한의 포인트 컬러로도 "따뜻함"을 전달할 수 있음을 보여주는 역발상 사례 — beat-puzzle-rpg의 미니멀리즘 원칙(Thumper, 기존 종합 3번)과 결합 가능. 옴니버스식 소소한 에피소드 구성은 "하루 속 순간들" 스테이지 구성과 구조적으로 유사.
- **출처**: [TOEM - Wikipedia](https://en.wikipedia.org/wiki/TOEM) (모바일 정보 누락 주의) · [TOEM - Google Play](https://play.google.com/store/apps/details?id=com.snapbreak.toem) · [Games Press 보도](https://www.gamespress.com/TOEM-A-Photo-Adventure-Now-Available-on-iOS-Android) · [Existential Magazine 리뷰](https://www.existentialmagazine.net/entertainment/review-toem)

### Behind the Frame: The Finest Scenery (Silver Lining Studio, 2021)

- **배경/설정**: 현대 대도시(뉴욕 갤러리 공모)를 배경으로, 갤러리 출품을 앞둔 화가가 마지막 그림을 완성하는 과정에서 자신의 기억(관계, 상실)을 마주하는 이야기.
- **비주얼 스타일**: 여러 리뷰어가 "지브리풍"으로 묘사하는 수채화/색연필 톤의 따뜻한 그림체.
- **감정/서사 전달 방식**: 대사는 있지만 핵심은 "그림 퍼즐" 자체다. 방탈출형 오브젝트 찾기 + 색칠북 방식의 그림 완성 퍼즐을 풀 때마다 과거 장면이 하나씩 드러난다 — 퍼즐 완성이 곧 기억 회복이라는 은유 구조.
- **모바일**: Crunchyroll Game Vault 앱을 통해 iOS/Android 제공(Crunchyroll 구독 필요) — Google Play에 "Crunchyroll: Behind the Frame" 리스팅으로 확인.
- **참고할 점**: "퍼즐을 완성하는 행위 = 기억/감정을 되찾는 행위"라는 은유 구조가 Florence와 함께 beat-puzzle-rpg의 핵심 컨셉("비트에 맞춰 퍼즐을 배치 = 그 순간의 감정을 정리")에 직접 대응하는 강력한 선례. 다만 이 게임은 후반에 무거운 반전 서사가 있어, 이번 기획의 "잔잔한 일상 감성" 기준에는 **톤 자체보다 "퍼즐=감정 회복" 메타포 구조만** 선별적으로 참고할 것.
- **출처**: [Behind the Frame: The Finest Scenery - Wikipedia](https://en.wikipedia.org/wiki/Behind_the_Frame:_The_Finest_Scenery) · [Silver Lining Studio 공식 사이트](https://silverliningstudio.co/Behindtheframe/) · [Crunchyroll 앱 - Google Play](https://play.google.com/store/apps/details?id=com.crunchyroll.gv.btf&hl=en_US) · [NYX Game Awards](https://nyxgameawards.com/winner-info.php?id=389)

### 참고만 하고 사례로는 배제한 후보 (확인 필요 표시 포함)

- **A Short Hike** (Adam Robinson-Yu, 2019): Windows/macOS/Linux/Switch/PS4/Xbox에만 출시, **Android 출시 없음(확인함)**. 파스텔톤의 산·바다 색감과 단순한 도형 캐릭터로 표현되는 편안한 일상 무드는 여전히 유효한 아트 레퍼런스지만, "모바일 실사례"로 인용하는 것은 부정확하므로 01-concept.md에서도 "무드 레퍼런스 한정, 모바일 미출시" 단서가 필요함. 출처: [A Short Hike - Wikipedia](https://en.wikipedia.org/wiki/A_Short_Hike)
- **Chicory: A Colorful Tale** (Greg Lobanov, 2021): PC/콘솔에만 출시, **Android 출시 없음(확인함)**. 색칠 퍼즐과 정서 결합도는 매우 높지만, 우울증·자기혐의 등 상당히 무거운 정신건강 서사를 정면으로 다뤄 이번 기획의 "캐주얼~미드코어, 잔잔한 감성" 기준에서는 제외 대상. 출처: [Chicory: A Colorful Tale - Wikipedia](https://en.wikipedia.org/wiki/Chicory:_A_Colorful_Tale)
- **Alba: A Wildlife Adventure** (ustwo games, 2020): Apple Arcade(iOS) 전용으로 출시, **Android 정식 출시는 확인되지 않음**(공식 출시 계획이 있었는지 여부도 검색 범위에서 확인 안 됨 — 확인 필요). Android 타겟인 beat-puzzle-rpg에는 참고 우선순위가 낮음. 출처: [Android Authority](https://www.androidauthority.com/ustwo-alba-a-wildlife-adventure-1139629/), [Alba: A Wildlife Adventure - Wikipedia](https://en.wikipedia.org/wiki/Alba:_A_Wildlife_Adventure)
- **A Little to the Left** (Secret Mode, 2022 / 모바일 2024-11-28): Android 정식 출시 확인(Google Play). 다만 스토리가 거의 없는 순수 정리·정돈 퍼즐로, "일상 감성 서사" 결합도는 낮음. 아늑한 스케치북 톤의 비주얼과 터치 정리 퍼즐 조작감만 보조적으로 참고할 만함. 출처: [Secret Mode 보도](https://wearesecretmode.com/news/a-little-to-the-left-sweeps-onto-android-today), [Google Play](https://play.google.com/store/apps/details?id=com.SecretModeLimited.ALittletotheLeft&hl=en_US)

## 종합 — 일상 감성 계열 공통 패턴 & 적용점

### 공통 패턴

1. **대사 최소화·비언어적 전달**: Florence, Old Man's Journey, Unpacking은 텍스트 대사를 거의/전혀 쓰지 않고 퍼즐·오브젝트·애니메이션만으로 감정을 전달. Coffee Talk·Behind the Frame은 대사가 있지만 핵심 정서는 "행위"(음료 제조/그림 완성)가 담당.
2. **퍼즐 구조 자체가 감정의 은유**: Florence(조각 수=관계의 편안함), Behind the Frame(퍼즐 완성=기억 회복)처럼, 퍼즐 난이도·완성 상태가 곧 감정 상태를 상징.
3. **제한된 팔레트로 정서를 압축**: 흑백(TOEM), 갈색 계열(Coffee Talk), 감정별 팔레트 전환(Florence) 등 "색을 줄이는 것"이 오히려 정서 전달을 명확하게 함.
4. **손그림/수채화/파스텔의 아날로그 질감**: 디지털적으로 매끈한 대신 종이·붓 질감을 남기는 비주얼(Old Man's Journey, Behind the Frame, TOEM의 팝업북 느낌)이 공통적.
5. **옴니버스식 챕터 구조**: 거대한 서사 대신 "일상의 한 챕터/하루/한 장면"을 쌓아가는 구조(Unpacking의 연도별 이사, TOEM의 마을별 에피소드, Florence의 챕터) — beat-puzzle-rpg의 "하루 속 순간들" 구성과 정확히 일치.
6. **캐주얼~미드코어 조작 + 짧은 세션**: 드래그/탭 위주 조작과 짧은 총 플레이타임(Florence 약 30분 등)이 많아 모바일 세션에 적합.

### beat-puzzle-rpg 적용점

1. **퍼즐 난이도를 감정 상태에 직접 매핑** (Florence): 설렘 장면=피스 수 적고 여유로운 배치, 피로 장면=복잡하고 조밀한 배치, 안도 장면=클리어 후 피스가 자연스럽게 정렬되는 연출을 스테이지별로 설계.
2. **대사 없이 배경 소품·컬러만으로 장소를 암시** (Unpacking, Old Man's Journey): 각 스테이지(출근길/회의실/지하철/밤)를 텍스트 설명 없이 색 팔레트+소품 실루엣만으로 구분.
3. **팔레트 제한 전략** (TOEM, Coffee Talk): 스테이지별로 2~3색 팔레트만 허용해 미니멀리즘(Thumper 원칙, 위 종합 3번)과 감정 표현을 동시에 달성 — 예: 출근길=차갑고 탁한 블루그레이, 밤=따뜻한 브라운/오렌지.
4. **"퍼즐 완성=감정 회복" 메타포를 명문화** (Behind the Frame, Florence): 콤보/정확도 판정 성공 시 화면이 정돈되거나 색이 채워지는 연출로 "정리됐다"는 감각을 시각적으로 직접 드러낼 것.
5. **옴니버스식 챕터 라벨링** (Unpacking, TOEM): 스테이지를 "레벨 1, 2, 3" 대신 "출근길", "회의실"처럼 하루의 장면 이름으로 라벨링하고, 각 장면 클리어를 짧은 무언극 컷씬(대사 없이 10~20초)으로 마무리.
6. **모바일 네이티브 조작 우선** (Old Man's Journey, Unpacking): 드래그/탭 기반의 단순 조작을 유지하고, 판정은 손끝의 정밀도가 아니라 타이밍/리듬에 두는 기존 설계를 재확인.
7. **참고 배제 사례를 명확히 구분** (A Short Hike, Chicory, Alba): 무드는 좋지만 Android 미출시거나 톤이 무거운 경우, `01-concept.md`의 아트 레퍼런스 표에도 "무드 레퍼런스 한정, 모바일 미출시" 등의 단서를 달아 혼동을 방지할 것.

## 시장 맥락

- 모바일에서는 "퍼즐+RPG" 하이브리드(예: 퍼즐앤드래곤 계열 — 매치 퍼즐로 전투하고 캐릭터를 성장시키는 구조)가 이미 검증된 성공 공식으로 자리잡았지만, 여기에 "리듬" 축까지 더한 3중 하이브리드 사례는 검색 범위 내에서 뚜렷한 선례를 찾지 못함 → beat-puzzle-rpg의 장르 융합 자체가 차별점이 될 수 있음
- 순수 리듬 액션(Beat Saber, 오투 등)은 이미 포화된 카테고리이므로, RPG 성장 루프를 결합해 "짧은 세션 반복 플레이"에 동기를 부여하는 방향이 유효해 보임

## 종합 — beat-puzzle-rpg에 적용할 점

1. **판정과 정산의 분리** (Lumines): 배치 타이밍 판정과는 별개로, 모아둔 콤보를 터뜨려 성장 재화를 배율로 정산하는 이벤트를 넣으면 "한 판 더" 동기를 강화할 수 있음
2. **단순한 로직 + 감각적 연출** (Tetris Effect): 퍼즐 로직 자체는 단순하게 유지하고, 판정 성공/실패에 따른 사운드·비주얼 피드백에 리소스를 집중
3. **미니멀 시각 원칙** (Thumper): 리듬 판정에 방해되는 시각 정보를 배제하는 "빼기" 원칙을 아트 스타일 가이드에 명문화할 것
4. **단일 규칙으로 리듬×RPG 결합** (Crypt of the NecroDancer, Cadence of Hyrule): "정확도 → 배율 → 성장 재화"와 "정확도 → 배율, 실패 → 패널티"의 상벌 구조를 최대한 단순하게 설계
5. **판정 축을 하나로 합칠 것** (QQQbeats!!!): 퍼즐 판정과 리듬 판정을 분리한 QQQbeats!!!와 달리, beat-puzzle-rpg는 "배치 타이밍 자체가 곧 판정"인 단일 축을 유지해 차별화
6. **성장이 실제 공략에 영향을 주게 할 것** (Theatrhythm Final Fantasy 반면교사): 성장 스탯이 코어 루프의 난이도 대응에 실질적 영향을 주지 못하면 RPG 요소가 장식으로 전락 — beat-puzzle-rpg는 스탯이 실제 다음 스테이지 난이도(BPM/패턴 복잡도) 대응력에 반영되도록 설계
7. **콤보 연속 성공 시 피버 타임** (Patapon): 일정 콤보 이상 유지 시 짧게 성장 재화 획득량을 배로 늘리는 피버 구간 도입 검토

## 시스템 구현 레퍼런스 (2차 기획서용)

`02-system-content.md` 작성을 위해 판정 구간·오디오 레이턴시·콤보 배율·퍼즐 난이도·퍼즐RPG 성장 구조를 웹 리서치한 결과. 확인 안 된 수치는 "추정"으로 표시.

### 리듬 판정(Timing Window)

- **StepMania**(Judge 4 기준): Marvelous(최상급) ±22.5ms, Perfect ±45ms, Great ±90ms — 등급이 올라갈수록 허용 오차가 2배씩 벌어지는 구조.
- **osu!mania**: Perfect/Great/Good/OK/Meh/Miss 6단계, 허용 오차는 비트맵의 難度(Overall Difficulty, OD) 값에 따라 가변적.
- **StepManiaX**: PERFECT!!/PERFECT/EARLY/LATE/MISS 5단계 — "빠름/늦음"을 등급명에 노출해 유저가 스스로 보정하게 유도.
- **적용점**: beat-puzzle-rpg도 3~4단계 판정(예: Perfect/Good/Miss)을 두고, 최상급 판정은 ±20~30ms 수준의 좁은 창으로 시작해 플레이테스트로 조정하는 것을 권장(추정치, 확정 아님). BPM이 오르면 노트 간격이 좁아지므로 판정 구간을 BPM에 비례해 자동 축소할지 고정할지는 밸런스 문서(`03-detail/balance.md`)에서 결정.
- 출처: [Timing windows in osu! - ppy forum](https://osu.ppy.sh/community/forums/topics/54535), [osu!mania judgement system - wiki](https://osu.ppy.sh/wiki/en/Gameplay/Judgement/osu!mania), [StepManiaX - Wikipedia](https://en.wikipedia.org/wiki/StepManiaX)

### 모바일 오디오 레이턴시 / 캘리브레이션

- Android 기기의 오디오 출력 지연은 기기마다 **0.01초~0.2초(10~200ms)** 로 편차가 커서, 판정 구간이 수십 ms 단위인 리듬 게임에서는 무시할 수 없는 오차임.
- Unity의 `AudioSettings.dspTime`은 게임 프레임 시간(Time.time)이 아닌 오디오 시스템 기준 시간을 반환하므로, `AudioSource.PlayScheduled`와 함께 써서 배경 음악을 정확한 DSP 시각에 예약 재생하는 방식이 표준적으로 권장됨. 단, dspTime도 이산적(discrete) 단계로 갱신되므로 완벽히 연속적이지 않다는 점을 캘리브레이션 설계 시 감안해야 함.
- Unity 기본 오디오 파이프라인은 Android에서 지연이 크다는 지적이 많아, DSP 버퍼 크기를 "Best latency"로, 오디오 클립 Load Type을 "Decompress On Load"로 설정하는 것이 최소 대응책이며, 근본적으로는 Android 네이티브 오디오 사용이 더 낫다는 의견도 있음(확인 필요 — 이 프로젝트 규모에서 네이티브 오디오까지 도입할지는 추후 판단).
- **적용점**: 01-concept.md 리스크 섹션에 이미 명시된 "최초 실행 시 기기별 오디오/터치 지연 자동 보정 캘리브레이션"이 리서치로 뒷받침됨. 구현은 `AudioSettings.dspTime` + `PlayScheduled` 조합을 기본으로 하고, 캘리브레이션 단계에서 유저에게 일정 박자를 여러 번 탭하게 해 평균 오차를 측정하는 방식을 권장.
- 출처: [Rhythm game with Unity3D: achieve latency free sync - Medium](https://medium.com/@thibautdumont/rhythm-game-with-unity3d-achieve-latency-free-sync-android-and-other-platforms-c05fa8e2718b), [Noticeable Audio Delay on Android - Unity Discussions](https://discussions.unity.com/t/noticeable-audio-delay-on-android-how-to-reduce-latency/1620003), [Bonus: Synchronizing with dspTime - Native Audio](https://exceed7.com/native-audio/rhythm-game-crash-course/dsp-sync.html), [Rhythm Quest Devlog 10 - latency calibration](https://ddrkirbyisq.medium.com/rhythm-quest-devlog-10-latency-calibration-fb6f1a56395c)

### 콤보 배율 / 피버 타임

- 전통적인 리듬 게임 콤보 배율은 **1x → 2x → 4x → 8x**처럼 일정 콤보 수마다 배로 뛰는 계단식 구조가 흔함.
- 모바일 퍼즐×리듬 하이브리드 사례(RhythmMatch)는 "모멘텀" 개념으로 **5단계 배율(1x~5x, 각 단계에 "Soundcheck"~"Encore" 같은 이름 부여)** 을 씀 — 등급에 이름을 붙여 성장감을 연출하는 방식.
- "풀 콤보(Full Combo)"는 노래 끝까지 최고 배율을 유지한 상태를 뜻하며, 많은 리듬 게임에서 별도의 성취/보상으로 취급됨.
- **적용점**: beat-puzzle-rpg의 콤보 배율은 계단식(예: 5/10/20/40콤보마다 배율 상승)으로 설계하고, 각 배율 구간에 테마(하루 속 순간)에 어울리는 이름을 붙이는 것을 검토. Patapon류 피버 타임은 "일정 콤보 이상 유지 시 짧은 시간 동안 성장 재화 획득량 2배" 같은 형태로 콤보 배율과는 별도 레이어로 설계.
- 출처: [How To Make a Rhythm Game #3 - Score and Multipliers - YouTube](https://www.youtube.com/watch?v=dV9rdTlMHxs), [RhythmMatch Demo - itch.io](https://zottware.itch.io/rhythmmatch), [Rhythm Game Scoring Systems Explained](https://rhythm-games.com/guides/rhythm-game-scoring-system-explained)

### 퍼즐 보드 / 난이도 파라미터

- **테트리스 7-bag 랜덤화**: 7종 피스를 한 "가방"에 담아 무작위로 섞어 하나씩 꺼내고, 가방이 비면 다시 채우는 방식. 특정 피스가 12개 이상 연속으로 안 나오는 일이 없도록 보장하는 "공정한 랜덤"의 표준 기법.
- 난이도를 올리는 파라미터로 일반적으로 쓰이는 것: 낙하/진행 속도, 피스(패턴) 종류 수, 보드 크기, 방해 요소 추가. 이번 리서치에서는 장르 전반의 일반 원칙만 확인했고, beat-puzzle-rpg처럼 "배치 타이밍=판정"인 하이브리드 장르의 구체적 난이도 곡선 수치 사례는 찾지 못함(확인 필요 — 프로토타입 플레이테스트로 직접 도출 필요).
- **적용점**: 피스 생성에 7-bag류의 공정한 랜덤화를 적용해 특정 패턴이 몰리거나 안 나오는 상황을 방지. 난이도는 BPM(속도)과 패턴 복잡도(피스 종류/방해 요소) 두 축으로 올리되, 01-concept.md 리스크 섹션에 이미 정한 대로 "퍼즐 축을 기준으로 먼저 밸런싱" 원칙을 유지.
- 출처: [How Tetris Randomizers Work - Dinogame GG](https://dinogame.gg/blog/how-tetris-randomizers-work/), [Random Generator - TetrisWiki](https://tetris.wiki/Random_Generator)

### 퍼즐×RPG 성장 구조

- **퍼즐앤드래곤(Puzzle & Dragons)**: 팀 전체의 HP/RCV(회복)/ATK 스탯이 소속 몬스터 스탯의 합 + 리더 스킬 배율로 계산됨. 매치한 오브 색깔에 대응하는 스탯이 대미지/회복량에 직접 반영되는 구조 — "무엇을 매치했는가"가 "어떤 스탯이 발동하는가"와 1:1로 연결됨.
- 액티브 스킬은 일정 턴(쿨타임) 경과 후 사용 가능한 구조로, 스탯 성장과는 별도 레이어로 존재.
- **적용점**: beat-puzzle-rpg의 캐릭터 스탯도 "무엇을 성장시키면 무엇이 쉬워지는가"를 1:1에 가깝게 연결하는 것을 권장 — 예: 정확도 스탯→판정 구간 확장, 콤보 유지력 스탯→콤보 배율 감쇠 완화, 속도 대응 스탯→고BPM 스테이지에서의 노트 표시 시간 증가 등(구체적 대응 관계는 `02-system-content.md`에서 확정). 이는 01-concept.md에 이미 명시한 "성장이 실제 다음 스테이지 난이도 대응력에 영향을 줘야 한다"는 원칙(Theatrhythm 반면교사)을 구체적인 스탯 설계로 연결하는 근거가 됨.
- 출처: [Game Mechanics - Puzzle & Dragons Wiki](https://pad.fandom.com/wiki/Game_Mechanics), [What Makes a Good Leader in Puzzle and Dragons - Mantastic](https://mantasticpad.com/2017/01/17/what-makes-a-good-leader-in-puzzle-and-dragons/)

## 참고 링크

- [Lumines Arise Review - Checkpoint](https://checkpointgaming.net/reviews/2025/11/lumines-arise-review-mesmerising-euphoria/)
- [Lumines | Lumines Wiki | Fandom](https://lumines.fandom.com/wiki/Lumines)
- [Tetris Effect: Connected 공식 사이트](https://www.tetriseffect.game/)
- [Tetris Effect - Enhancing gameplay with synesthesia](https://www.nicholassinger.com/blog/tetriseffect)
- [QQQbeats!!! - Wikipedia](https://en.wikipedia.org/wiki/QQQbeats!!!)
- [Review: Thumper – Nintendo Wire](https://nintendowire.com/news/2017/05/18/review-thumper/)
- [Thumper — Grokipedia](https://grokipedia.com/page/Thumper_(video_game))
- [Muse Dash - Wikipedia](https://en.wikipedia.org/wiki/Muse_Dash)
- [Muse Dash Review - Noisy Pixel](https://noisypixel.net/muse-dash-review-pc-switch/)
- [Crypt of the NecroDancer - Guide: Gameplay Basics](https://necrodancer.miraheze.org/wiki/Gameplay_Basics)
- [Crypt of the NecroDancer - Wikipedia](https://en.wikipedia.org/wiki/Crypt_of_the_NecroDancer)
- [Cadence of Hyrule - Wikipedia](https://en.wikipedia.org/wiki/Cadence_of_Hyrule)
- [Cadence of Hyrule Review | RPG Site](https://www.rpgsite.net/review/8662-cadence-of-hyrule-review)
- [Theatrhythm Final Fantasy - Wikipedia](https://en.wikipedia.org/wiki/Theatrhythm_Final_Fantasy)
- [Theatrhythm Final Bar Line Review - GameSkinny](https://www.gameskinny.com/3uaom/theatrhythm-final-bar-line-review-the-ultimate-final-fantasy-celebration)
- [Patapon - Wikipedia](https://en.wikipedia.org/wiki/Patapon)
- [Review: Patapon 2 - Push Square](https://www.pushsquare.com/reviews/psp/patapon_2)
- [Hybrid-Puzzle Games: Blending Brains With Business](https://medium.com/loopix-lab/hybrid-puzzle-games-blending-brains-with-business-cd1f4e1daca5)
- [Florence (video game) - Wikipedia](https://en.wikipedia.org/wiki/Florence_(video_game))
- [Review: Florence – Destructoid](https://www.destructoid.com/reviews/review-florence/)
- [Florence - App Store](https://apps.apple.com/us/app/florence/id1297430468)
- [Old Man's Journey - Wikipedia](https://en.wikipedia.org/wiki/Old_Man%27s_Journey)
- [Old Man's Journey 공식 사이트](http://www.oldmansjourney.com/)
- [Old Man's Journey - Google Play](https://play.google.com/store/apps/details?id=es.brokenrul.oldmansjourney&hl=en_IN)
- [Unpacking (video game) - Wikipedia](https://en.wikipedia.org/wiki/Unpacking_(video_game))
- [Unpacking 모바일 출시 - Engadget](https://www.engadget.com/zen-moving-game-unpacking-comes-to-android-and-ios-on-august-24th-214513079.html)
- [Unpacking 모바일 - TouchArcade](https://toucharcade.com/2023/08/01/unpacking-iphone-ipad-android-release-date/)
- [Unpacking - Pocket Gamer](https://www.pocketgamer.com/unpacking/out-now/)
- [Coffee Talk (video game) - Wikipedia](https://en.wikipedia.org/wiki/Coffee_Talk_(video_game))
- [Coffee Talk 모바일 - DroidGamers](https://www.droidgamers.com/news/coffee-talk-episode-1/)
- [Coffee Talk 모바일 출시 - Prism News](https://www.prismnews.com/hobbies/mobile-gaming/coffee-talk-arrives-on-ios-and-android-bringing-cozy-caf)
- [TOEM - Wikipedia](https://en.wikipedia.org/wiki/TOEM)
- [TOEM - Google Play](https://play.google.com/store/apps/details?id=com.snapbreak.toem)
- [TOEM 모바일 출시 - Games Press](https://www.gamespress.com/TOEM-A-Photo-Adventure-Now-Available-on-iOS-Android)
- [TOEM 리뷰 - Existential Magazine](https://www.existentialmagazine.net/entertainment/review-toem)
- [Behind the Frame: The Finest Scenery - Wikipedia](https://en.wikipedia.org/wiki/Behind_the_Frame:_The_Finest_Scenery)
- [Silver Lining Studio 공식 사이트](https://silverliningstudio.co/Behindtheframe/)
- [Crunchyroll: Behind the Frame - Google Play](https://play.google.com/store/apps/details?id=com.crunchyroll.gv.btf&hl=en_US)
- [Behind the Frame - NYX Game Awards](https://nyxgameawards.com/winner-info.php?id=389)
- [A Short Hike - Wikipedia](https://en.wikipedia.org/wiki/A_Short_Hike)
- [Chicory: A Colorful Tale - Wikipedia](https://en.wikipedia.org/wiki/Chicory:_A_Colorful_Tale)
- [Alba: A Wildlife Adventure - Wikipedia](https://en.wikipedia.org/wiki/Alba:_A_Wildlife_Adventure)
- [Alba Android 미출시 관련 - Android Authority](https://www.androidauthority.com/ustwo-alba-a-wildlife-adventure-1139629/)
- [A Little to the Left Android 출시 - Secret Mode](https://wearesecretmode.com/news/a-little-to-the-left-sweeps-onto-android-today)
- [A Little to the Left - Google Play](https://play.google.com/store/apps/details?id=com.SecretModeLimited.ALittletotheLeft&hl=en_US)
- [Timing windows in osu! - ppy forum](https://osu.ppy.sh/community/forums/topics/54535)
- [osu!mania judgement system - wiki](https://osu.ppy.sh/wiki/en/Gameplay/Judgement/osu!mania)
- [StepManiaX - Wikipedia](https://en.wikipedia.org/wiki/StepManiaX)
- [Rhythm game with Unity3D: achieve latency free sync - Medium](https://medium.com/@thibautdumont/rhythm-game-with-unity3d-achieve-latency-free-sync-android-and-other-platforms-c05fa8e2718b)
- [Noticeable Audio Delay on Android - Unity Discussions](https://discussions.unity.com/t/noticeable-audio-delay-on-android-how-to-reduce-latency/1620003)
- [Bonus: Synchronizing with dspTime - Native Audio](https://exceed7.com/native-audio/rhythm-game-crash-course/dsp-sync.html)
- [Rhythm Quest Devlog 10 - latency calibration](https://ddrkirbyisq.medium.com/rhythm-quest-devlog-10-latency-calibration-fb6f1a56395c)
- [How To Make a Rhythm Game #3 - Score and Multipliers - YouTube](https://www.youtube.com/watch?v=dV9rdTlMHxs)
- [RhythmMatch Demo - itch.io](https://zottware.itch.io/rhythmmatch)
- [Rhythm Game Scoring Systems Explained](https://rhythm-games.com/guides/rhythm-game-scoring-system-explained)
- [How Tetris Randomizers Work - Dinogame GG](https://dinogame.gg/blog/how-tetris-randomizers-work/)
- [Random Generator - TetrisWiki](https://tetris.wiki/Random_Generator)
- [Game Mechanics - Puzzle & Dragons Wiki](https://pad.fandom.com/wiki/Game_Mechanics)
- [What Makes a Good Leader in Puzzle and Dragons - Mantastic](https://mantasticpad.com/2017/01/17/what-makes-a-good-leader-in-puzzle-and-dragons/)

## 개정 이력

| 버전 | 날짜 | 변경 내용 |
| --- | --- | --- |
| v0.1.0 | 2026-08-10 | 최초 작성 — Lumines/Tetris Effect/Thumper/Crypt of the NecroDancer 리서치 |
| v0.2.0 | 2026-08-10 | 유사 게임 목록 요약표 추가, QQQbeats!!!/Muse Dash/Cadence of Hyrule/Theatrhythm Final Fantasy/Patapon 리서치 및 적용점 보강 |
| v0.3.0 | 2026-08-11 | 테마 전환(현대 사회·일상적 감성) 대응 — "일상 감성 × 현대 사회 계열" 섹션 추가. Florence/Old Man's Journey/Unpacking/Coffee Talk/TOEM/Behind the Frame 리서치, A Short Hike·Chicory·Alba 등 Android 미출시/톤 부적합 사례 확인 및 배제, 공통 패턴·적용점 보강 |
| v0.3.1 | 2026-08-11 | 버전 표기를 MAJOR.MINOR.PATCH 3단계 형식으로 전환 (과거 버전 표기 전체 소급 변환, 내용 변경 없음) |
| v0.4.0 | 2026-08-11 | "시스템 구현 레퍼런스" 섹션 신설 — 리듬 판정 구간(ms), 모바일 오디오 레이턴시/캘리브레이션, 콤보 배율/피버 타임, 퍼즐 보드 난이도 파라미터, 퍼즐×RPG 성장 구조 리서치. `02-system-content.md` 작성 근거 |
