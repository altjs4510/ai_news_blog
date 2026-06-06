---
title: "AI News Digest"
toc: false
---

<div class="ai-home-grid">

<div class="ai-home-main">

<section class="ai-home-hero">
  <p class="ai-eyebrow">AI NEWS · WEEKLY DIGEST</p>
  <h1 class="ai-headline">Opus 4.8과 65B 펀딩이 가른 진영, 에이전트 보안·청구 거버넌스가 동시에 무너졌다</h1>
  <p class="ai-home-deck">모델 경쟁이 자율성·자본 규모로 옮겨가는 사이, OpenClaw 침해와 5억 달러 청구 사고가 운영 공백을 노출했다.</p>
  <p class="ai-meta">2026-06-01 · 주간 요약 (매주 월요일) · 일간 픽 매일 갱신</p>
  <div class="ai-cta-row">
    <a class="ai-cta" href="https://altjs4510.github.io/ai_news_blog/posts/20260601/">
      <span class="ai-cta-label">이번 주 전체 보기</span>
      <span class="ai-cta-arrow" aria-hidden="true">→</span>
    </a>
  </div>
</section>

<aside class="ai-spotlight">
  <p class="ai-eyebrow ai-spotlight-eyebrow">✦ TODAY'S PICK</p>
  <a class="ai-spotlight-title" href="https://www.reddit.com/r/artificial/comments/1tq0t1g/the_openclaw_crisis_is_the_most_complete_case/" target="_blank" rel="noopener">The OpenClaw crisis — Claw Chain 4-CVE 연쇄와 245K 인스턴스 노출<span class="ai-spotlight-arrow">↗</span></a>
  <p class="ai-spotlight-why">TOCTOU 경합 → 자격증명 탈취 → MCP 권한 상승 → 백도어 설치까지 정상 에이전트 동작을 모방해 일어난 첫 대규모 공급망 침해 사례로, MCP host server의 OAuth·세션·tool 실행 권한 경계가 곧 보안 경계라는 점을 정조준합니다. DCSAI가 자체 구현 중인 MCP host server와 HITL 분기 설계가 정확히 같은 결을 다룹니다.</p>
  <p class="ai-spotlight-app"><span class="ai-spotlight-app-label">접목 →</span> DCSAI MCP host server의 tool 실행 경로에 에이전트별 자격증명 격리·런타임 입력 스캔·세션별 권한 스코프를 추가하고, agent loop의 HITL 분기를 'tool 권한 상승 요청' 단계로 확장해 silent 권한 확장을 차단하는 PoC로 곧장 연결됩니다.</p>
  <p class="ai-spotlight-cta"><a class="ai-spotlight-detail" href="https://altjs4510.github.io/ai_news_blog/knowledge/20260531/">자세히 보기 <span class="ai-spotlight-detail-arrow" aria-hidden="true">→</span></a></p>
</aside>

<section class="ai-additional">
  <p class="ai-eyebrow">ALSO WORTH READING · 꼭 읽어보세요</p>
  <div class="ai-pick-list">
  <article class="ai-pick">
  <a class="ai-pick-title" href="https://claude.com/blog/introducing-dynamic-workflows-in-claude-code" target="_blank" rel="noopener">Introducing dynamic workflows in Claude Code<span class="ai-pick-arrow">↗</span></a>
  <p class="ai-pick-summary">단일 세션에서 수백 개 병렬 서브에이전트를 띄우고 보고 전 결과를 검증하는 구조를 공식화한 발표로, Team Agent의 `discovery-core-agent`/`platform-core-agent` 2계층 오케스트레이션과 DCSAI agent loop의 HITL 분기 신뢰성 설계에 직결됩니다.</p>
</article>
  <article class="ai-pick">
  <a class="ai-pick-title" href="https://www.reddit.com/r/artificial/comments/1trmvgh/mystery_company_accidentally_blew_500_million_on/" target="_blank" rel="noopener">Mystery company accidentally blew $500 million on Claude AI<span class="ai-pick-arrow">↗</span></a>
  <p class="ai-pick-summary">직원 라이선스에 사용 한도를 걸지 않아 한 달 만에 5억 달러를 소진한 사례로, Anthropic SDK 직통합 환경에서 토큰·세션 미터링과 자동 한도/알림이 부가 기능이 아닌 운영 필수 레이어임을 보여줍니다. DCSAI `ff-claude-manager` Tauri tray의 사용량 가시화 결과 곧장 맞물립니다.</p>
</article>
  </div>
</section>

<nav class="ai-chips"><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8-%EB%B3%B4%EC%95%88/">#에이전트 보안</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/mcp-%EA%B6%8C%ED%95%9C-%EA%B2%A9%EB%A6%AC/">#MCP 권한 격리</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/claude-opus-4.8/">#Claude Opus 4.8</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EC%B2%AD%EA%B5%AC-%EA%B1%B0%EB%B2%84%EB%84%8C%EC%8A%A4/">#청구 거버넌스</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/codex-%EC%97%94%ED%84%B0%ED%94%84%EB%9D%BC%EC%9D%B4%EC%A6%88/">#Codex 엔터프라이즈</a></nav>

### 전체 요약

이번 주 AI 업계는 **Anthropic의 Claude Opus 4.8 출시**와 **965B 포스트머니 밸류에이션의 시리즈 H 65B 펀딩**으로 정점을 찍었습니다. 동시에 한국·이탈리아 오피스 개설, 오픈소스 유지보수자 1만명 무료 지원 등 글로벌 확장과 생태계 투자 행보가 두드러졌습니다. **OpenAI는 Codex 중심의 엔터프라이즈 사례** (Cisco, MUFG, Endava)를, **Google은 Gemini Omni 및 3.5의 I/O 2026 데모**를 전면에 내세우며 각자 다른 진영을 굳히고 있습니다.

반면 **에이전트 보안의 어두운 면**도 동시에 폭로되었습니다. **OpenClaw 위기**로 불리는 공급망/샌드박스 탈출 연쇄 CVE 사건은 245K 인스턴스 노출, 30K 이상 침해라는 충격적 수치를 남겼고, 한 익명 기업이 사용 한도 미설정으로 **Claude에 한 달 만에 5억 달러를 소진**했다는 보도까지 나왔습니다. 에이전트가 실험에서 프로덕션으로 넘어가는 과정의 청구·보안 거버넌스 공백이 그대로 드러난 한 주입니다.

개발자 생태계에서는 **GitHub Copilot의 토큰 기반 과금 전환에 대한 반발**, **Microsoft의 Claude Code 라이선스 취소** 보도 등 도구 공급망 갈등이 표면화되었고, 학계·HuggingFace에서는 **에이전트 안전(AgentDoG), 비디오 월드모델, LoRA 메모리 법칙** 등 다중모달·에이전트 연구가 흐름을 주도했습니다.

---

### 주제별 분석

#### 1. Claude Opus 4.8 출시와 Anthropic의 자본·조직 확장 가속

**핵심 인사이트**

**Anthropic**은 Opus 4.7 대비 코딩·에이전트·전문업무에서 더 날카로운 판단력과 장기 작업 일관성을 강조한 **Claude Opus 4.8**을 동일 가격에 공개했습니다. 함께 발표된 **고속 모드(2.5배 빠르고 3배 저렴)** 와 **Claude Code의 동적 워크플로우(수백 개 병렬 서브에이전트)** 는 Anthropic이 "더 똑똑한 모델"보다 "더 오래 자율적으로 일하는 모델"에 베팅하고 있음을 보여줍니다.

자본 측면에서는 **시리즈 H에서 65B 달러를 965B 포스트머니 밸류에이션**으로 조달했고, Axios의 보도처럼 "어느 산업·어느 시대에도 이 속도로 유기적 매출이 성장한 사례가 없다"는 평가가 나옵니다. **밀라노·서울 오피스 개설**, **한국 대표 KiYoung Choi 선임**으로 글로벌 엔터프라이즈 영업망을 빠르게 깔고 있습니다.

또한 **"Claude for Open Source"** 프로그램으로 오픈소스 유지보수자 1만명에게 Claude Max 20x를 6개월 무료(약 1,200달러 상당) 제공하며, 개발자 표심을 흡수하는 전형적인 플랫폼 락인 전략을 펼치고 있습니다.

**관련 자료**

- [Introducing Claude Opus 4.8](https://www.anthropic.com/news/claude-opus-4-8)
- [Anthropic raises $65B in Series H funding at $965B post-money valuation](https://www.anthropic.com/news/series-h)
- [Anthropic opens Milan office](https://www.anthropic.com/news/milan-office-opening)
- [KiYoung Choi as Representative Director of Korea](https://www.anthropic.com/news/kiyoung-choi-representative-director-anthropic-korea)
- [Introducing dynamic workflows in Claude Code](https://claude.com/blog/introducing-dynamic-workflows-in-claude-code)
- [Anthropic이 오픈소스 유지보수자 10,000명에게 Claude Max 20x를 6개월 무료](https://www.reddit.com/r/PromptEngineering/comments/1touhcf/anthropic_is_giving_10000_opensource_maintainers/)
- [Anthropic run-rate 코멘트 (Simon Willison)](https://simonwillison.net/2026/May/31/anthropic-run-rate/#atom-everything)

---

#### 2. 에이전트 보안 붕괴 — OpenClaw 위기와 청구 거버넌스 공백

**핵심 인사이트**

오픈소스 에이전트 플랫폼 **OpenClaw**에서 4개의 CVE가 연쇄되는 **"Claw Chain"**(CVSS 9.6 샌드박스 쓰기 탈출 포함)이 공개되며, **245,000개 인스턴스 노출, 30,000개 이상 침해, 마켓플레이스 12% 손상**이라는 결과가 드러났습니다. TOCTOU 경합 → 자격증명 탈취 → MCP 권한 상승 → 백도어 설치까지 모든 단계가 정상 에이전트 동작을 모방해 기존 모니터링으로 탐지가 불가능한 점이 핵심입니다.

이와 별개로 **익명의 기업이 직원 라이선스에 사용 한도를 설정하지 않아 한 달 만에 Claude에 5억 달러를 지출**한 사건이 보도되었고, **GitHub Copilot의 토큰 기반 과금 전환**도 개발자들의 거센 반발을 부르고 있습니다. 모델 비용이 사용량 폭증과 결합하면 통제 불가능한 청구가 발생한다는 사실이 처음으로 대규모로 노출된 셈입니다.

대응 방향은 명확합니다. **Claude Blog의 "Zero Trust for AI agents"**, **OpenAI의 Frontier Governance Framework**, **Anthropic의 "How we contain Claude"**가 모두 같은 주에 등장한 것은 우연이 아니며, 에이전트별 자격증명 격리·런타임 입력 스캔·행동 패턴 모니터링이 표준이 될 가능성이 높습니다.

**관련 자료**

- [The OpenClaw crisis 전체 타임라인](https://www.reddit.com/r/artificial/comments/1tq0t1g/the_openclaw_crisis_is_the_most_complete_case/)
- [Mystery company accidentally blew $500 million on Claude AI](https://www.reddit.com/r/artificial/comments/1trmvgh/mystery_company_accidentally_blew_500_million_on/)
- [Zero Trust for AI agents](https://claude.com/blog/zero-trust-for-ai-agents)
- [How we contain Claude across products](https://simonwillison.net/2026/May/30/how-we-contain-claude/#atom-everything)
- [OpenAI's Frontier Governance Framework](https://openai.com/index/openai-frontier-governance-framework)
- [GitHub Copilot's new token-based billing spurs consternation](https://techcrunch.com/2026/05/30/what-a-joke-github-copilots-new-token-based-billing-spurs-consternation-among-devs/)
- [Using LLMs to secure source code](https://claude.com/blog/using-llms-to-secure-source-code)

---

#### 3. Codex로 굳히는 OpenAI의 엔터프라이즈 진영

**핵심 인사이트**

**OpenAI**는 이번 주 거의 모든 블로그 포스트를 **Codex 기반 엔터프라이즈 도입 사례**로 채웠습니다. **Cisco의 엔터프라이즈 엔지니어링 재정의**, **MUFG의 AI 네이티브 전환**, **Endava의 에이전틱 조직 구축**, **Braintrust의 고객 요청→코드 자동화**, **자가개선 세금 에이전트**, **Warp의 GPT-5.5 기반 오픈소스** 등 사실상 모든 사례가 코드 자동화 축으로 정렬되어 있습니다.

이는 Anthropic이 Claude Code의 **동적 워크플로우와 서브에이전트 오케스트레이션**으로 같은 시장을 노리는 것과 정면충돌합니다. **CodeRabbit이 Claude로 에이전트 오케스트레이션 시스템을 구축**한 사례에서 보듯, "코딩 에이전트 = 엔터프라이즈 자동화의 입구"라는 인식이 양측 공통의 전제가 되었습니다.

흥미로운 점은 **Cognition의 Scott Wu가 "AI 코딩 에이전트가 인간을 대체해서는 안 된다"** 고 발언했다는 것이며, **TechCrunch는 "AI 없이는 일을 거부하는 코더들이 역풍을 맞을 수 있다"** 는 우려를 동시에 제기했습니다. 도구 의존도와 직무 정체성 사이의 긴장이 본격 논의 단계로 들어왔습니다.

**관련 자료**

- [Cisco and OpenAI redefine enterprise engineering with Codex](https://openai.com/index/cisco)
- [MUFG aims to become AI-native with OpenAI](https://openai.com/index/mufg)
- [How Endava builds an agentic organization with Codex](https://openai.com/index/endava)
- [How Braintrust turns customer requests into code with Codex](https://openai.com/index/braintrust)
- [Building self-improving tax agents with Codex](https://openai.com/index/building-self-improving-tax-agents-with-codex)
- [Warp's big bet on building open source with GPT-5.5](https://openai.com/index/warp)
- [How CodeRabbit used Claude to build an agent orchestration system](https://claude.com/blog/how-coderabbit-used-claude-to-build-an-agent-orchestration-system)
- [Cognition's Scott Wu says AI coding agents shouldn't replace humans](https://techcrunch.com/2026/05/29/cognitions-scott-wu-says-ai-coding-agents-shouldnt-replace-humans/)
- [Coders are refusing to work without AI](https://techcrunch.com/2026/05/29/coders-are-refusing-to-work-without-ai-and-that-could-come-back-to-bite-them/)

---

#### 4. 에이전트 스킬·하니스가 GitHub 트렌딩의 새로운 표준

**핵심 인사이트**

이번 주 GitHub 트렌딩의 절반 이상이 **"에이전트 하니스(harness)"와 "스킬(skill)" 패러다임**을 중심으로 형성되었습니다. **affaan-m/ECC**(에이전트 하니스 성능 최적화), **revfactory/harness**(도메인별 에이전트 팀 설계 메타스킬), **Leonxlnx/taste-skill**, **hardikpandya/stop-slop**(AI 특유 문체 제거)이 동시에 급상승했습니다.

**Anthropic 공식 저장소**(`anthropics/knowledge-work-plugins`)와 **mukul975/Anthropic-Cybersecurity-Skills**(MITRE ATT&CK·NIST 등 5개 프레임워크 매핑된 754개 보안 스킬)의 부상은, **"스킬 = 에이전트의 새로운 단위 추상"** 이라는 합의가 형성되었음을 보여줍니다. Claude Code, Codex, Gemini CLI, Cursor 등 멀티 에이전트 호환이 모든 저장소의 공통 셀링포인트입니다.

또한 **codegraph**, **Lum1104/Understand-Anything** 같은 **코드 지식 그래프 도구**가 주간 1만~2.5만 스타를 받으며, 컨텍스트 절약을 위한 "사전 인덱싱된 코드 그래프"가 표준 인프라로 자리잡고 있습니다.

**관련 자료**

- [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)
- [affaan-m/ECC](https://github.com/affaan-m/ECC)
- [revfactory/harness](https://github.com/revfactory/harness)
- [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)
- [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop)
- [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills)
- [colbymchenry/codegraph](https://github.com/colbymchenry/codegraph)
- [Lum1104/Understand-Anything](https://github.com/Lum1104/Understand-Anything)
- [cursor/plugins](https://github.com/cursor/plugins)

---

#### 5. 데이터센터 전력·인프라 군비 경쟁의 가속

**핵심 인사이트**

**SoftBank이 프랑스 데이터센터에 최대 750억 유로 투자**를 발표했고, **Nvidia의 Groq 20B 비-acqui-hire 직후 Groq이 6.5억 달러 추가 조달** 보도까지 이어지며 추론 칩 자본 경쟁이 격화되고 있습니다. 동시에 **Erin Brockovich가 데이터센터의 비밀주의(전력·용수 사용량 미공개)를 정조준**하며 환경·사회적 반발의 상징적 인물이 등장했습니다.

Reddit에서는 **"인간 뇌는 20W로 처리하는 일을 AI는 핵반응로가 필요하다"** 는 자조적 비판과 함께, 노스웨스턴 대학의 **MoS2·그래핀 잉크 인쇄 인공 뉴런이 살아있는 쥐 뇌세포와 상호작용**한 신경형태 컴퓨팅 연구가 화제가 되었습니다. 에너지 효율 한계가 실리콘 패러다임 자체에 대한 의문으로 번지고 있습니다.

이는 **OpenAI의 Rosalind Biodefense 협업, Boston Children's의 진단 AI** 같은 사회적 정당성 확보 콘텐츠가 같은 주에 집중 배포된 맥락과도 연결됩니다. 인프라 확장 = 사회적 라이선스 확보가 패키지로 묶이고 있습니다.

**관련 자료**

- [SoftBank says it will invest up to €75 billion to build French data centers](https://techcrunch.com/2026/05/30/softbank-says-it-will-invest-up-to-e75-billion-to-build-french-data-centers/)
- [After Nvidia's $20B not-acqui-hire, AI chip startup Groq reportedly raising $650M](https://techcrunch.com/2026/05/29/after-nvidias-20b-not-acqui-hire-ai-chip-startup-groq-reportedly-raising-650m/)
- [Erin Brockovich takes aim at data center secrecy](https://techcrunch.com/2026/05/31/erin-brockovich-takes-aim-at-data-center-secrecy/)
- [Your brain does on 20 watts what AI needs a nuclear reactor](https://www.reddit.com/r/artificial/comments/1tr4kau/your_brain_does_on_20_watts_what_ai_needs_a/)
- [Boston Children's uses AI to unlock new diagnoses](https://openai.com/index/boston-childrens-hospital)
- [Strengthening societal resilience with Rosalind Biodefense](https://openai.com/index/strengthening-societal-resilience-with-rosalind-biodefense)

---

### 주목할 만한 개별 발견

#### Microsoft의 Claude Code 라이선스 취소 보도

- 출처: [The Verge 보도 (Reddit 요약)](https://www.reddit.com/r/ClaudeAI/comments/1to6kqz/microsoft_has_started_canceling_claude_code/)

**Microsoft가 Claude Code 라이선스 취소를 시작**했다는 The Verge의 보도는, MS-OpenAI 진영과 Anthropic 진영의 전면 분리가 임박했다는 신호로 읽힙니다. 같은 주 Anthropic이 시리즈 H로 965B 밸류에이션에 도달한 것을 고려하면, 이는 단순 비용 절감이 아니라 **공급망 디커플링의 시작**으로 해석됩니다.

#### Pope Leo XIV의 AI 회칙 "Magnifica humanitas"

- 출처: [Anthropic Chris Olah의 코멘트](https://www.anthropic.com/news/chris-olah-pope-leo-encyclical)
- 출처: [Simon Willison의 분석](https://simonwillison.net/2026/May/25/)

**교황 레오 14세가 AI를 다룬 회칙**을 발표하고, Anthropic 공동창업자 **Chris Olah**가 이에 공식 코멘트를 낸 것은 매우 이례적입니다. 종교 기관이 AI 거버넌스 담론의 한 축으로 진입했음을 보여주는 상징적 사건이며, "AI 정렬"이 기술 문제가 아닌 사상적 문제로 확장되고 있음을 시사합니다.

#### "Continue? Y/N" — 에이전트 권한 피로감의 게이미피케이션

- 출처: [Show HN](https://llmgame.scalex.dev)

60초짜리 게임으로 **AI 에이전트 권한 승인 피로감**을 풍자한 작품이 Hacker News에 등장했습니다. OpenClaw 보안 사태와 맞물려, "모든 권한을 매번 묻는 에이전트 UX는 사람을 둔감하게 만든다"는 메시지가 개발자 커뮤니티의 공통 정서로 자리잡고 있음을 보여줍니다.

#### Gemini Omni·3.5와 I/O 2026의 멀티모달 데모 러시

- 출처: [9 demos of Gemini Omni and Gemini 3.5](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-omni-3-5-videos/)
- 출처: [Gemini Spark TechCrunch 리뷰](https://techcrunch.com/2026/05/30/i-put-googles-24-7-ai-assistant-gemini-spark-to-work-and-its-actually-pretty-useful/)

Google은 Anthropic·OpenAI의 코딩·엔터프라이즈 공세에 맞서 **Gemini Omni와 24/7 어시스턴트 Gemini Spark**로 일상·멀티모달 영역을 차별화하고 있습니다. TechCrunch가 Spark를 "실제로 유용하다"고 평가한 점은, **상시 작동 개인 에이전트** 카테고리가 2026년 하반기 주력 전선이 될 가능성을 시사합니다.

</div>

<aside class="ai-home-aside">
  <section class="ai-week-block">
    <p class="ai-eyebrow">THIS WEEK</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260607/">
    <span class="ai-pick-date">2026-06-07</span>
    <span class="ai-pick-title-mini">OpenAI Help: Lockdown Mode</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260606/">
    <span class="ai-pick-date">2026-06-06</span>
    <span class="ai-pick-title-mini">chopratejas/headroom — Compress tool outputs, logs, files, a…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260605/">
    <span class="ai-pick-date">2026-06-05</span>
    <span class="ai-pick-title-mini">chopratejas/headroom — Compress tool outputs, logs, and RAG …</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260604/">
    <span class="ai-pick-date">2026-06-04</span>
    <span class="ai-pick-title-mini">chopratejas/headroom — Compress tool outputs before they rea…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260603/">
    <span class="ai-pick-date">2026-06-03</span>
    <span class="ai-pick-title-mini">How Bad MCP design cost your Agent 5× more tokens</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260602/">
    <span class="ai-pick-date">2026-06-02</span>
    <span class="ai-pick-title-mini">revfactory/harness — 도메인별 에이전트 팀과 스킬을 자동 설계하는 메타 스킬</span>
  </a>
</li>
    </ul>
  </section>
  <section class="ai-week-block">
    <p class="ai-eyebrow">LAST WEEK</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260531/">
    <span class="ai-pick-date">2026-05-31</span>
    <span class="ai-pick-title-mini">How we contain Claude across products</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260530/">
    <span class="ai-pick-date">2026-05-30</span>
    <span class="ai-pick-title-mini">Leonxlnx/taste-skill — AI에게 좋은 취향을 부여해 generic slop을 막는 Clau…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260529/">
    <span class="ai-pick-date">2026-05-29</span>
    <span class="ai-pick-title-mini">Introducing dynamic workflows in Claude Code</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260528/">
    <span class="ai-pick-date">2026-05-28</span>
    <span class="ai-pick-title-mini">Building self-improving tax agents with Codex</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260527/">
    <span class="ai-pick-date">2026-05-27</span>
    <span class="ai-pick-title-mini">Microsoft Copilot Cowork Exfiltrates Files</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260526/">
    <span class="ai-pick-date">2026-05-26</span>
    <span class="ai-pick-title-mini">colbymchenry/codegraph — Pre-indexed code knowledge graph fo…</span>
  </a>
</li>
    </ul>
  </section>
</aside>

</div>

<footer class="ai-home-footer">
  <p class="ai-eyebrow">SOURCES</p>
  <div class="ai-source-grid">
    <p class="ai-source-row"><span class="ai-source-label">공식</span>Anthropic · OpenAI · Google · DeepMind</p>
    <p class="ai-source-row"><span class="ai-source-label">전문가</span>Simon Willison · Karpathy · Lilian Weng · Hamel Husain · Matt Pocock (AI Hero)</p>
    <p class="ai-source-row"><span class="ai-source-label">에이전트·툴</span>LangChain · LlamaIndex · AutoGen · CrewAI · Cursor · Cline · Aider</p>
    <p class="ai-source-row"><span class="ai-source-label">뉴스레터</span>Latent Space · TLDR AI · The Rundown · AlphaSignal · Ben's Bites · The Batch</p>
    <p class="ai-source-row"><span class="ai-source-label">커뮤니티</span>Reddit · Hacker News · Product Hunt · TechCrunch AI · Bluesky</p>
    <p class="ai-source-row"><span class="ai-source-label">연구·코드</span>arxiv · HuggingFace Papers · GitHub Trending</p>
  </div>
  <p class="ai-home-links"><a href="https://altjs4510.github.io/ai_news_blog/posts/">주간 요약</a><span class="ai-dot">·</span><a href="https://altjs4510.github.io/ai_news_blog/knowledge/">학습 노트</a><span class="ai-dot">·</span><a href="https://altjs4510.github.io/ai_news_blog/tags/">태그</a><span class="ai-dot">·</span><a href="https://altjs4510.github.io/ai_news_blog/posts/index.xml">RSS</a><span class="ai-dot">·</span><a href="https://altjs4510.github.io/ai_news_blog/about/">소개</a></p>
</footer>
