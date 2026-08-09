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
