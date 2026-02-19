# Swift → AI 전환 가이드

> Xcode 중심 개발에서 AI-augmented workflow로의 전환

[![GitHub stars](https://img.shields.io/github/stars/ComBba/swift-ai-transition-guide?style=social)](https://github.com/ComBba/swift-ai-transition-guide)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 왜 이 가이드인가?

Swift 개발자들이 Claude Code, OpenClaw, Cursor 등 AI 도구로 
효과적으로 전환할 수 있도록 돕는 실전 가이드입니다.

**steipete.me 철학을 따릅니다:**
- 모든 커밋은 GitHub에 공개됩니다
- 실제 문제를 해결하는 실용적 콘텐츠
- 커뮤니티와 함께 성장하는 오픈소스

## 🚀 빠른 시작

### 1단계: Claude Code 설치
```bash
# macOS
brew install claude-code

# 또는 npm
npm install -g @anthropic-ai/claude-code
```

### 2단계: 첫 AI 코딩 세션
```bash
# 프로젝트 디렉토리에서
claude

# "이 SwiftUI �트를 리팩토링해줘"라고 요청해보세요
```

## 📚 목차

### 🎯 마이그레이션 가이드
- [Xcode 단축키 → Claude Code 명령어](./migrations/xcode-shortcuts-to-claude.md)
- [빌드 에러 AI로 해결하기](./migrations/build-errors-with-ai.md)
- [SwiftUI 프리뷰 AI 보조 workflow](./migrations/swiftui-preview-to-ai.md)

### 💡 실전 팁
- [Swift 특화 프롬프트 모음](./tips/prompts-for-swift.md)
- [초보자가 흔히 하는 실수](./tips/common-pitfalls.md)
- [AI로 코드 리뷰 받기](./tips/ai-code-review.md)

### 📖 핵심 개념
- [왜 Swift 개발자가 AI를 써야 하는가](./docs/01-why-ai.md)
- [Claude Code 상세 설치 가이드](./docs/02-claude-code-setup.md)
- [OpenClaw 에이전트 설정](./docs/03-agent-setup.md)
- [고급 AI 활용 패턴](./docs/04-advanced-patterns.md)

### 🛠️ 예제 프로젝트
- [Todo 앱 - AI로 만든 풀스택 Swift](./examples/todo-app/)
- [리팩토링 before/after](./examples/refactoring/)

## 🤝 기여하기

PR 환영합니다! 
- 새로운 마이그레이션 팁 공유
- 실제 사례 스터디
- 번역 (한국어 → 영어 등)

See [CONTRIBUTING.md](./CONTRIBUTING.md)

## 📣 커뮤니티

- **Twitter/X**: [@swift_ai_guide](https://twitter.com/swift_ai_guide)
- **Discord**: [Swift Korea](https://discord.gg/swiftkorea)

## 📝 라이선스

MIT © 숭숭이 팀 & Contributors

---

**Inspired by** [steipete.me](https://steipete.me) - Peter Steinberger의 오픈소스 철학
