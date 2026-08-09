# 레퍼런스 리서치

- **작성일**: 2026-08-10
- **버전**: v0.1
- **연관 문서**: [01-concept.md](./01-concept.md)
- **참고**: 여기 정리한 게임들은 직접 플레이가 아닌 웹 리서치 기반 자료입니다. 직접 플레이한 타 게임 리뷰는 [`library/타게임리뷰분석/`](../../../library/타게임리뷰분석/)에 별도로 기록합니다.

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

## 리듬×액션 계열

### Thumper

- **핵심 루프**: 컨트롤 스틱 + 버튼 2개 입력만으로 트랙 위 빛나는 구간을 정확한 타이밍에 통과. 진행할수록 새 기믹(장애물, 회전, 보스 패턴) 추가
- **비주얼**: 80년대 SF 모티프 + 러브크래프트풍 사이키델릭. 게임플레이에 불필요한 시각 정보는 전부 덜어내는 "빼기(subtractive)" 방식의 미니멀리즘
- **참고할 점**: 입력을 극도로 단순하게 유지(2버튼)하면서 난이도는 새로운 기믹 추가로 확장하는 구조 — beat-puzzle-rpg의 "조작은 단순, 난이도는 패턴/BPM으로 확장" 설계와 방향이 일치. 시각 노이즈를 최소화해 리듬 판정에 집중시키는 미니멀리즘 원칙도 그대로 적용 가능

## 리듬×RPG/로그라이크 계열

### Crypt of the NecroDancer

- **핵심 루프**: 비트마다 한 턴씩 진행되는 로그라이크 던전 크롤러. 이동/공격/루팅이 모두 박자에 맞아야 하며, 박자를 놓치지 않고 연속 처치하면 코인 배율이 오름
- **성장 시스템**: 다이아몬드를 모아 영구 강화(체력, 장비)를 해금하고, 캐릭터별로 스탯/스킬이 다른 다수의 플레이 가능 캐릭터 존재
- **참고할 점**: "박자를 못 맞추면 페널티, 잘 맞추면 배율 상승"이라는 단순한 규칙 하나로 리듬과 전투(RPG 액션)를 자연스럽게 묶은 사례. beat-puzzle-rpg에서도 퍼즐 배치 정확도-콤보 배율-성장 재화 획득량을 하나의 규칙으로 엮는 데 참고 가능

## 시장 맥락

- 모바일에서는 "퍼즐+RPG" 하이브리드(예: 퍼즐앤드래곤 계열 — 매치 퍼즐로 전투하고 캐릭터를 성장시키는 구조)가 이미 검증된 성공 공식으로 자리잡았지만, 여기에 "리듬" 축까지 더한 3중 하이브리드 사례는 검색 범위 내에서 뚜렷한 선례를 찾지 못함 → beat-puzzle-rpg의 장르 융합 자체가 차별점이 될 수 있음
- 순수 리듬 액션(Beat Saber, 오투 등)은 이미 포화된 카테고리이므로, RPG 성장 루프를 결합해 "짧은 세션 반복 플레이"에 동기를 부여하는 방향이 유효해 보임

## 종합 — beat-puzzle-rpg에 적용할 점

1. **판정과 정산의 분리** (Lumines): 배치 타이밍 판정과는 별개로, 모아둔 콤보를 터뜨려 성장 재화를 배율로 정산하는 이벤트를 넣으면 "한 판 더" 동기를 강화할 수 있음
2. **단순한 로직 + 감각적 연출** (Tetris Effect): 퍼즐 로직 자체는 단순하게 유지하고, 판정 성공/실패에 따른 사운드·비주얼 피드백에 리소스를 집중
3. **미니멀 시각 원칙** (Thumper): 리듬 판정에 방해되는 시각 정보를 배제하는 "빼기" 원칙을 아트 스타일 가이드에 명문화할 것
4. **단일 규칙으로 리듬×RPG 결합** (Crypt of the NecroDancer): "정확도 → 배율 → 성장 재화"로 이어지는 규칙을 최대한 단순하게 설계

## 참고 링크

- [Lumines Arise Review - Checkpoint](https://checkpointgaming.net/reviews/2025/11/lumines-arise-review-mesmerising-euphoria/)
- [Lumines | Lumines Wiki | Fandom](https://lumines.fandom.com/wiki/Lumines)
- [Tetris Effect: Connected 공식 사이트](https://www.tetriseffect.game/)
- [Tetris Effect - Enhancing gameplay with synesthesia](https://www.nicholassinger.com/blog/tetriseffect)
- [Review: Thumper – Nintendo Wire](https://nintendowire.com/news/2017/05/18/review-thumper/)
- [Thumper — Grokipedia](https://grokipedia.com/page/Thumper_(video_game))
- [Crypt of the NecroDancer - Guide: Gameplay Basics](https://necrodancer.miraheze.org/wiki/Gameplay_Basics)
- [Crypt of the NecroDancer - Wikipedia](https://en.wikipedia.org/wiki/Crypt_of_the_NecroDancer)
- [Hybrid-Puzzle Games: Blending Brains With Business](https://medium.com/loopix-lab/hybrid-puzzle-games-blending-brains-with-business-cd1f4e1daca5)

## 개정 이력

| 버전 | 날짜 | 변경 내용 |
| --- | --- | --- |
| v0.1 | 2026-08-10 | 최초 작성 — Lumines/Tetris Effect/Thumper/Crypt of the NecroDancer 리서치 |
