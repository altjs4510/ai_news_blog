---
title: About
---

## 이 블로그는 무엇인가요

매일 오전, 지난 24시간 동안의 AI 동향을 자동으로 수집·요약해 발행합니다. 사람의 손을 거치지 않고 GitHub Actions가 모든 단계를 자동화합니다. 운영자는 [@altjs4510](https://github.com/altjs4510) 한 명입니다.

## 수집 소스

- **공식 블로그** — Anthropic, OpenAI, Google AI, DeepMind
- **전문가** — Simon Willison, Karpathy, Lilian Weng, Hamel Husain, Matt Pocock (AI Hero)
- **에이전트·툴** — LangChain, LlamaIndex, AutoGen, CrewAI, Cursor, Cline, Aider
- **뉴스레터** — Latent Space, TLDR AI, The Rundown, AlphaSignal, Ben's Bites, The Batch
- **커뮤니티** — Reddit (`r/AI_Agents`, `r/ClaudeAI`, `r/OpenAI`, `r/PromptEngineering`, `r/artificial`, `r/ArtificialInteligence`), Hacker News (Algolia API · AI 키워드 · ≥50점), Product Hunt AI, TechCrunch AI, Bluesky
- **연구·코드** — arxiv (`cs.AI`, `cs.CL`), HuggingFace Papers, GitHub Trending

## 처리 파이프라인

1. 모든 소스에서 지난 24시간 콘텐츠 수집
2. Reddit 포스트는 키워드 또는 LLM 평가로 관련성 필터링 → 한국어 번역
3. 모든 소스를 통합 입력으로 **Claude Opus 4.7**이 인사이트 글 작성
4. 같은 자료로 헤드라인 · 추천 항목(Spotlight) · 키워드 5개 추출
5. Hugo 빌드 → GitHub Pages 배포 → Slack 알림

## 사용 모델

- 평가 · 번역 (대량 호출): **Claude Haiku 4.5**
- 통합 인사이트 · 요약 (소량, 핵심): **Claude Opus 4.7**

## 코드

- [`ai_news_agent`](https://github.com/altjs4510/ai_news_agent) — 수집·요약·발행 자동화 (Python)
- [`ai_news_blog`](https://github.com/altjs4510/ai_news_blog) — 정적 사이트 (Hugo + Hextra)

## 라이선스 · 출처

본 사이트의 인사이트 본문과 큐레이션은 자동 생성된 것입니다. 인용된 모든 외부 글·저장소·논문의 권리는 각 출처에 있으며, 본문에는 출처 링크를 항상 명시합니다. 인용 외 본 사이트 코드는 MIT 라이선스를 따릅니다.
