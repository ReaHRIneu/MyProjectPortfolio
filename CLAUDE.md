# Claude Code Project Guide

## 🌐 Language & Tone
- **Language**: Always respond and write code comments in Korean (한국어로 답변 및 주석 작성).
- **Tone**: Professional, concise, and helpful (전문적이고 간결하며 친절한 어조).

## 🚀 Build, Test, and Run Commands
- **Install Dependencies**: `npm install` (또는 프로젝트에 맞는 명령어 입력)
- **Run Application**: `npm start`
- **Build Project**: `npm run build`
- **Run Tests**: `npm test`

## 🛠️ Code Style & Standards
- Follow standard JavaScript/TypeScript style guidelines.
- Use explicit type definitions instead of `any`.
- Keep functions modular, small, and single-purpose.

## 📝 Commit & Branch Strategy
- **Commit Format**: Follow Conventional Commits (`feat: ...`, `fix: ...`).
- **Branch Naming**: `feature/feature-name` or `bugfix/issue-name`.

## 📄 문서 형식 규칙

- 모든 문서 파일은 기본적으로 **Markdown(`.md`)**으로 작성합니다.
- 발표/공유 등 목적으로 **별도 요청이 들어온 경우에만** [`templates/pptx-design-guide.md`](./templates/pptx-design-guide.md)에 정의된 디자인(블루퍼플 포인트 컬러, Pretendard 폰트, 슬라이드 구조)으로 `.pptx`를 제작합니다.
- `.pptx`는 항상 원본 `.md` 문서를 바탕으로 만든 산출물로 취급하며, `.pptx` 자체가 원본이 되지 않도록 원본 `.md`는 계속 유지/갱신합니다.

## 🗓️ 작업 기록 (History)

- 작업 세션에서 의미 있는 변경(문서 추가/수정, 기획, 세팅 등)을 진행하면 `history/<YYYY-MM>.md`에 기록을 남깁니다.
- 해당 월 파일이 없으면 새로 만들고 `history/README.md` 목록에 추가합니다.
- 형식: `## YYYY-MM-DD` 날짜 섹션 아래에 그날 진행한 작업을 불릿으로 요약합니다.
- 게임 기획서(`projects/unity/*`, `templates/game-design/`) 작업 시에는 [`templates/game-design/README.md`](./templates/game-design/README.md)의 "제작 규칙"(단계 진행 조건, 버전/개정 이력, 커밋 연동, 새 프로젝트 생성 절차, 파일 생성 규칙)을 따릅니다.

## 📁 저장소 구조

이 저장소는 앱/서비스 코드가 아니라 **개인 종합 wiki**(순수 마크다운 폴더 구조)입니다. 위의 Build/Test 명령어(`npm install` 등)는 이 저장소 자체에는 해당하지 않는 범용 예시입니다.

```
projects/           # 프로젝트 포트폴리오 (완료/진행 중 프로젝트 소개)
  unity/             # Unity/게임 개발 프로젝트 문서
notes/              # 일반 프로그래밍 노트 / TIL
personal/           # 기타 개인 노트
library/            # Notion 등 외부에서 가져온 참고자료 (평판 파일 나열)
templates/          # 새 문서 작성용 템플릿 (project-note.md, til.md, game-design/)
```

새 프로젝트/노트를 추가할 땐 위 폴더 중 성격에 맞는 곳에 넣고, 해당 폴더의 `README.md` 목록에 링크를 추가합니다.
