# Claude Code x GitHub 실습

> Claude Code와 GitHub를 연동하여 AI 기반 개발 워크플로우를 경험하는 실습 프로젝트입니다.

## 실습 목표

- Claude Code CLI를 활용한 코드 작성 및 수정 자동화
- GitHub 저장소와의 연동 (commit, PR, issue) 실습
- AI 기반 코드 리뷰 및 문서화 워크플로우 이해

## 사전 요구사항

- [Claude Code](https://claude.ai/code) 설치 및 로그인
- Git 설치 및 GitHub 계정
- GitHub CLI (`gh`) 설치 (선택)

```bash
# Claude Code 설치 확인
claude --version

# GitHub CLI 설치 (macOS)
brew install gh

# GitHub 로그인
gh auth login
```

## 실습 구성

### 1단계 — 환경 설정
- Claude Code 설치 및 인증
- GitHub 저장소 연결
- `CLAUDE.md` 파일로 프로젝트 컨텍스트 설정

### 2단계 — 기본 워크플로우
- Claude Code로 코드 생성 및 편집
- `git commit` 메시지 자동 작성
- Pull Request 초안 생성

### 3단계 — 고급 활용
- Issue 기반 기능 개발
- 코드 리뷰 자동화 (`/review` 커맨드)
- CI/CD 파이프라인과 연동

## 빠른 시작

```bash
# 저장소 클론
git clone https://github.com/<your-username>/my-first-project.git
cd my-first-project

# Claude Code 실행
claude

# 실습 시작 — Claude에게 요청 예시
# "이 프로젝트에 Hello World 함수를 추가하고 커밋해줘"
```

## 주요 Claude Code 커맨드

| 커맨드 | 설명 |
|--------|------|
| `/init` | CLAUDE.md 초기화 |
| `/review` | PR 코드 리뷰 |
| `/commit` | 변경사항 커밋 |
| `! gh pr create` | PR 생성 |

## 참고 자료

- [Claude Code 공식 문서](https://docs.anthropic.com/claude/docs/claude-code)
- [GitHub CLI 문서](https://cli.github.com/manual/)

## 라이선스

MIT
