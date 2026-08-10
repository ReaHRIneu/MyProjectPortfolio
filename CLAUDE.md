# Claude Code Project Guide

## 🌐 Language & Tone
- **Language**: Always respond and write code comments in Korean (한국어로 답변 및 주석 작성).
- **Tone**: Professional, concise, and helpful (전문적이고 간결하며 친절한 어조).

## 📝 커밋 규칙
- **Commit Format**: Conventional Commits(`docs: ...`, `chore: ...` 등)를 따릅니다. 별도 브랜치 없이 `main`에 직접 커밋하는 방식으로 운영합니다.
- **로컬 커밋**(git add/commit, push 이전)은 되돌리기 쉬운 저위험 작업이므로 사용자 확인 없이 바로 진행합니다.
- **git push, force-push, 저장소 공개범위 변경** 등 외부에 영향을 주거나 되돌리기 어려운 작업은 사용자의 명시적 요청이 있을 때만 진행합니다.

## 📄 문서 형식 규칙

- 모든 문서 파일은 기본적으로 **Markdown(`.md`)**으로 작성합니다.
- 발표/공유 등 목적으로 **별도 요청이 들어온 경우에만** [`templates/pptx-design-guide.md`](./templates/pptx-design-guide.md)에 정의된 디자인(블루퍼플 포인트 컬러, Pretendard 폰트, 슬라이드 구조)으로 `.pptx`를 제작합니다.
- `.pptx`는 항상 원본 `.md` 문서를 바탕으로 만든 산출물로 취급하며, `.pptx` 자체가 원본이 되지 않도록 원본 `.md`는 계속 유지/갱신합니다.
- **버전을 표기하는 문서**는 `MAJOR.MINOR.PATCH`(예: `v1.2.0`) 형식으로 세부 관리합니다. 각 자리의 의미는 문서 종류별 규칙 문서에서 정의합니다(게임 기획서는 [`templates/game-design/README.md`](./templates/game-design/README.md) 2번 참고).

## 🔐 저장소 공개/보안 설정

- 이 저장소는 **Public**으로 유지합니다. GitHub 무료 플랜에서는 Private 저장소에 브랜치 보호·Secret scanning을 적용할 수 없어(GitHub Pro 이상 필요) 두 보호 기능을 무료로 쓰기 위해 Public을 선택했습니다 (2026-08-10 결정).
- `main` 브랜치: 강제 푸시(force-push)·삭제 차단 (최소 보호 — 혼자 작업하므로 PR 필수는 아님).
- Secret scanning + push protection 활성화 — 커밋에 API 키 등 민감정보가 포함되면 GitHub가 감지/차단합니다.
- Public 저장소이므로 `personal/` 등에 개인정보(연락처, 위치, 재무 정보 등 식별 가능한 민감 정보)는 넣지 않습니다.
- Private 전환이 다시 요청되면, 브랜치 보호와 Secret scanning이 자동으로 비활성화된다는 점을 먼저 안내합니다.

## 🗓️ 작업 기록 (History)

- 작업 세션에서 의미 있는 변경(문서 추가/수정, 기획, 세팅 등)을 진행하면 `history/<YYYY-MM>.md`에 기록을 남깁니다.
- 해당 월 파일이 없으면 새로 만들고 `history/README.md` 목록에 추가합니다.
- 형식: `## YYYY-MM-DD` 날짜 섹션 아래에 그날 진행한 작업을 불릿으로 요약합니다.

### 다음 세션 메모 (`history/next-session.md`)

- 위 월별 기록과는 별개로, `history/next-session.md`는 **다음 세션 시작 시 참고할 임시 작업 메모**입니다.
- 작업일 또는 작업 시간 종료 시점에 갱신합니다.
- 월별 기록(`history/<YYYY-MM>.md`)처럼 누적(append)하지 않고, **매번 최신 상태로 덮어씁니다(overwrite)**.
- 내용에는 마지막 세션 요약과 다음에 이어서 할 작업(미해결/확인 필요 사항 위주)만 간결하게 남깁니다.

## 📚 폴더별 작성 규칙

- 게임 기획서(`projects/unity/*`, `templates/game-design/`): [`templates/game-design/README.md`](./templates/game-design/README.md)의 "제작 규칙"(단계 진행 조건, 버전/개정 이력, 커밋 연동, 새 프로젝트 생성 절차, 파일 생성 규칙)을 따릅니다.
- 타 게임 리뷰 분석(`library/타게임리뷰분석/`): 해당 폴더 [`README.md`](./library/타게임리뷰분석/README.md)의 작성 규칙(파일명, 메타 정보, 행사별 하위 폴더)을 따릅니다.

## 📁 저장소 구조

이 저장소는 앱/서비스 코드가 아니라 **개인 종합 wiki**(순수 마크다운 폴더 구조)입니다.

```
projects/           # 프로젝트 포트폴리오 (완료/진행 중 프로젝트 소개)
  unity/             # Unity/게임 개발 프로젝트 문서
notes/              # 일반 프로그래밍 노트 / TIL
personal/           # 기타 개인 노트
library/            # Notion 등 외부에서 가져온 참고자료 (평판 파일 나열)
templates/          # 새 문서 작성용 템플릿 (project-note.md, til.md, game-design/)
```

새 프로젝트/노트를 추가할 땐 위 폴더 중 성격에 맞는 곳에 넣고, 해당 폴더의 `README.md` 목록에 링크를 추가합니다.
