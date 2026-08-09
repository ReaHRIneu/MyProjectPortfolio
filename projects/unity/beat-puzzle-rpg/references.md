# 레퍼런스 리서치

- **작성일**: 2026-08-10
- **버전**: v0.2
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

## 개정 이력

| 버전 | 날짜 | 변경 내용 |
| --- | --- | --- |
| v0.1 | 2026-08-10 | 최초 작성 — Lumines/Tetris Effect/Thumper/Crypt of the NecroDancer 리서치 |
| v0.2 | 2026-08-10 | 유사 게임 목록 요약표 추가, QQQbeats!!!/Muse Dash/Cadence of Hyrule/Theatrhythm Final Fantasy/Patapon 리서치 및 적용점 보강 |
