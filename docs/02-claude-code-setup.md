# Claude Code 설치 가이드

> macOS에서 5분 완성

## 1단계: 설치

```bash
# Homebrew로 설치 (권장)
brew install claude-code

# 또는 npm
npm install -g @anthropic-ai/claude-code
```

## 2단계: 인증

```bash
# 프로젝트 디렉토리에서
claude

# 브라우저에서 로그인
# Anthropic Console에서 API 키 발급
```

## 3단계: 첫 실행

```bash
# Xcode 프로젝트에서
claude

# 프롬프트 입력
> "이 ViewController 리팩토링해줘"
```

## ✅ 설치 확인

```bash
claude --version
# claude-code 2.x.x
```

## 다음 단계

→ [Xcode 단축키 마이그레이션](../migrations/xcode-shortcuts-to-claude.md)
