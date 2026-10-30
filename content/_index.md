---
title: "AI News Digest"
toc: false
---

<div class="ai-home-grid">

<div class="ai-home-main">

<section class="ai-home-hero">
  <p class="ai-eyebrow">AI NEWS · WEEKLY DIGEST</p>
  <h1 class="ai-headline">오픈 웨이트 Kimi K3.1 Pro가 프론티어 턱밑까지 왔고, 보안·에이전트 하네스는 실무 단계로 넘어가고 있다</h1>
  <p class="ai-home-deck">클로즈드 모델과의 격차가 '월' 단위로 줄면서, 이제 어떤 모델을 쓰느냐보다 에이전트 루프에 어떤 검증과 사람 리뷰를 두느냐가 경쟁력을 가른다</p>
  <p class="ai-meta">2026-10-26 · 주간 요약 (매주 월요일) · 일간 픽 매일 갱신</p>
  <div class="ai-cta-row">
    <a class="ai-cta" href="https://altjs4510.github.io/ai_news_blog/posts/20261026/">
      <span class="ai-cta-label">이번 주 전체 보기</span>
      <span class="ai-cta-arrow" aria-hidden="true">→</span>
    </a>
  </div>
</section>

<aside class="ai-spotlight">
  <p class="ai-eyebrow ai-spotlight-eyebrow">✦ TODAY'S PICK</p>
  <a class="ai-spotlight-title" href="https://simonwillison.net/2026/Oct/23/kimi-k31-pro/" target="_blank" rel="noopener">Introducing Kimi K3.1 Pro (Simon Willison 노트)<span class="ai-spotlight-arrow">↗</span></a>
  <p class="ai-spotlight-why">이번 윈도우에 새로 나온 1차 발표이고, 이번 주 가장 화제가 된 항목입니다. Simon Willison은 오픈 웨이트(11월 4일 가중치 공개 예정) 모델이 지금 프론티어와 이 정도로 신뢰할 만하게 경쟁한 건 처음이라고 평가했고([Bluesky](https://bsky.app/profile/simonwillison.net/post/3mykwxawoa22u), ❤262), Latent Space는 104B 활성 / 2.8T 총 파라미터 규모의 Fable-5.1급 모델로 소개했습니다. 오픈 웨이트가 프론티어급까지 올라오면 Anthropic SDK 기반 agent loop에서 매 턴 어떤 모델을 쓸지 정하는 라우팅 기준과 tool use 보조 호출의 비용 구조를 다시 따져 봐야 합니다.</p>
  <p class="ai-spotlight-app"><span class="ai-spotlight-app-label">접목 →</span> DCSAI agent loop에서 요약·분류·tool 결과 정리 같은 보조 호출을 자체 호스팅 오픈 웨이트 모델(vLLM 서빙)로 돌리고, 본 추론과 HITL 판단은 Claude에 남기는 2단 라우팅 PoC를 11월 4일 가중치가 공개되면 바로 시작할 수 있습니다. 사내 데이터가 외부로 나가지 않는 경로를 확보하는 데에도 의미가 있습니다.</p>
  <p class="ai-spotlight-cta"><a class="ai-spotlight-detail" href="https://altjs4510.github.io/ai_news_blog/posts/20261026/study/">자세히 보기 <span class="ai-spotlight-detail-arrow" aria-hidden="true">→</span></a></p>
</aside>

<section class="ai-additional">
  <p class="ai-eyebrow">ALSO WORTH READING · 꼭 읽어보세요</p>
  <div class="ai-pick-list">
  <article class="ai-pick">
  <a class="ai-pick-title" href="https://openai.com/index/cloudflare-cyber" target="_blank" rel="noopener">Cloudflare links vulnerability discovery to defense with OpenAI<span class="ai-pick-arrow">↗</span></a>
  <p class="ai-pick-summary">Cloudflare가 OpenAI Daybreak로 취약점을 조사하고 수정안을 받은 뒤, 반영 전에 반드시 사람이 검토하는 '발견→수정 제안→리뷰' 루프를 운영하는 이번 주 신규 공식 사례입니다. 같은 주 OpenAI가 공개한 [프론티어 학습 환경 봉쇄 방식](https://openai.com/index/securing-our-frontier-model-training-environment)과 함께 읽으면, 에이전트 출력 중 무엇을 자동 검증에 맡기고 어디서 사람 승인을 받을지 HITL 분기를 설계하는 실전 기준을 얻을 수 있습니다.</p>
</article>
  <article class="ai-pick">
  <a class="ai-pick-title" href="https://github.com/akitaonrails/ai-memory" target="_blank" rel="noopener">akitaonrails/ai-memory<span class="ai-pick-arrow">↗</span></a>
  <p class="ai-pick-summary">코딩 에이전트 CLI에 장기 기억을 붙이고, 벤더가 다른 에이전트 사이에서 작업을 넘겨받을 수 있게 하는 Rust 도구로, 이번 주 GitHub Trending에서 3,541스타를 받았습니다. 하네스 경쟁이 '메모리와 핸드오프'로 옮겨 가는 흐름을 보여 주며, Team Agent의 Activity Log→Observer 피드백루프에서 쌓인 기록을 다음 실행이나 다른 에이전트에 넘기는 구조를 설계할 때 참고할 만합니다.</p>
</article>
  </div>
</section>

<nav class="ai-chips"><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/kimi-k3.1-pro/">#Kimi K3.1 Pro</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EC%98%A4%ED%94%88-%EC%9B%A8%EC%9D%B4%ED%8A%B8/">#오픈 웨이트</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%ED%94%84%EB%A1%A0%ED%8B%B0%EC%96%B4-%EA%B2%A9%EC%B0%A8/">#프론티어 격차</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/hitl-%EB%B3%B4%EC%95%88-%EB%A3%A8%ED%94%84/">#HITL 보안 루프</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8-%EB%A9%94%EB%AA%A8%EB%A6%AC/">#에이전트 메모리</a></nav>

### 전체 요약

이번 주 가장 큰 뉴스는 **Kimi K3.1 Pro**입니다. 오픈 웨이트 공개를 예고한 모델이 프론티어 클로즈드 모델과 정면으로 비교될 만큼 올라왔고, "클로즈드 AI와의 격차가 1개월로 좁혀졌다"는 평가까지 나왔습니다.

보안 쪽에서도 큰 흐름이 보였습니다. **OpenAI**는 프론티어 모델 학습 환경을 어떻게 격리하는지와 사이버 방어자 지원 청사진을 함께 공개했습니다. **Cloudflare**는 취약점 발견부터 수정 제안까지를 AI로 연결하는 사례와 보안 감사 스킬 오픈소스로 그 흐름을 실무 수준에서 보여줬습니다.

오픈소스 생태계는 **에이전트 하네스·스킬·메모리** 중심으로 재편되고 있습니다. 그 반대편에는 "기술 업계 밖에서는 **재무적 성과가 0**"이라는 이코노미스트의 진단과 소셜에서 커지는 AI 회의론이 함께 있어서, 기술 진보와 실질 가치 사이의 간극이 뚜렷하게 드러난 한 주였습니다.

---

### 주제별 분석

#### 1. 프론티어 AI × 사이버 보안 — 공격 능력 봉쇄와 방어 능력 강화가 동시에

**핵심 인사이트**

**OpenAI**는 프론티어 모델의 학습·평가 환경을 **오프라인 환경**과 **고연산 레드티밍**으로 봉쇄하는 방식을 공개했습니다. 같은 주에 사이버 방어자에게 프론티어 AI를 쥐여주는 정책 청사진도 냈습니다. 모델이 강력해질수록 "안에서 새지 않게 하는 것"과 "밖에서 방어에 쓰게 하는 것"을 한 묶음으로 다루겠다는 메시지입니다.

실무 사례로는 **Cloudflare**가 가장 앞서 있습니다. **OpenAI Daybreak**로 취약점을 조사하고 수정안을 제안받아 사람이 검토하며, 개발자들은 **Codex**로 코드 품질을 끌어올리고 있습니다. 여기서 핵심은 수정을 바로 반영하지 않고 반드시 사람이 검토하는 **"발견→수정 제안→리뷰"** 루프입니다.

이 흐름은 GitHub에도 그대로 나타났습니다. **cloudflare/security-audit-skill**은 독립적으로 검증되고 기계가 읽을 수 있는 형태의 감사 결과를 내는 코딩 에이전트 스킬로, 이번 주 **12,680 스타**를 받아 트렌딩 1위에 올랐습니다. Cloudflare 앱 전용 AI 온콜 엔지니어인 **Polylane**까지 나오면서, 보안·운영 자동화는 에이전트가 가장 빨리 자리 잡는 영역이 되고 있습니다.

**관련 자료**

- [Securing our frontier model training environment](https://openai.com/index/securing-our-frontier-model-training-environment)
- [Democratic governance of frontier AI, part II: Empowering cyber defenders](https://openai.com/index/empowering-cyber-defenders)
- [Cloudflare links vulnerability discovery to defense with OpenAI](https://openai.com/index/cloudflare-cyber)
- [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)
- [Polylane for Cloudflare](https://www.producthunt.com/products/polylane)

#### 2. Kimi K3.1 Pro — 오픈 웨이트가 프론티어 바로 뒤까지 따라왔다

**핵심 인사이트**

**Moonshot**의 **Kimi K3.1 Pro**가 Kimi API로 먼저 공개됐습니다. 지금은 오픈 웨이트가 아니지만 **2026년 11월 4일까지 전체 가중치를 공개**하겠다고 약속했습니다. **Simon Willison**은 이 모델을 두고 "오픈 웨이트 계열이 현재 프론티어와 이 정도로 신뢰할 만하게 경쟁한 건 처음"이라고 평가했습니다.

**Latent Space**는 이 모델을 **104B 활성 / 2.8T 총 파라미터** 규모의 **Fable-5.1급** 오픈 웨이트로 소개했습니다. 클로즈드 진영과의 격차를 **약 1개월**로 봤고, 2~3배 빠른 **Pro Highspeed API**도 함께 언급했습니다. 한편 "We have Fable at home… or so we are being told by paid shills"라는 부제처럼 과장된 홍보를 경계하는 시선도 같이 담았습니다.

격차가 '분기'가 아니라 '월' 단위로 줄면, 클로즈드 모델의 가격 프리미엄을 정당화하기는 더 어려워집니다. 다만 실제 가중치 공개와 독립 벤치마크가 나오기 전까지는 **"예고된 오픈 웨이트"**라는 점을 감안해야 합니다.

**관련 자료**

- [Introducing Kimi K3.1 Pro](https://simonwillison.net/2026/Oct/23/kimi-k31-pro/)
- [[AINews] Kimi 3.1 Pro 104BA-2.8T: Fable-5.1-Class Open Weights narrows Closed-AI lead to 1 month... and Pro Highspeed API with 2-3× speed](https://latent.space/p/ainews-kimi-31/)
- [Notes on Kimi K3.1 (Bluesky)](https://bsky.app/profile/simonwillison.net/post/3mykwxawoa22u)

#### 3. 에이전트 하네스·스킬·메모리 — 모델 대신 '둘레'에서 승부가 난다

**핵심 인사이트**

GitHub 트렌딩 상위권은 거의 다 에이전트 **오케스트레이션 레이어**입니다. 여러 코딩 에이전트를 자기 구독으로 한 화면에서 돌리는 **Orca**(이번 주 9,828 스타), 멀티 플레이어 스웜을 내세운 **ruflo**, 오픈소스 코딩 에이전트 **opencode**가 대표적입니다. 이제 개발자는 에이전트 하나를 고르기보다 **에이전트 여러 대를 지휘하는 쪽**으로 움직이고 있습니다.

같은 흐름에서 **스킬·플러그인**이 사실상 표준 배포 단위로 자리를 잡았습니다. Anthropic의 **claude-plugins-official**과 **knowledge-work-plugins**, **android/skills**, 코드베이스를 지식 그래프로 바꿔주는 **/graphify** 스킬이 나란히 올라왔습니다. **Google ADK v2.13.0**, **CrewAI 1.15.30**, **Hermes Agent** 카나리 릴리스처럼 프레임워크 쪽도 매주 업데이트가 이어지고 있습니다.

다음 과제는 **메모리와 핸드오프**입니다. **ai-memory**는 서로 다른 벤더의 에이전트 사이에서 장기 기억을 넘겨주는 문제를 풀고, **Context Engine**과 **AgentGrid.io**는 사람과 에이전트가 같은 기억과 작업 공간을 쓰게 하는 방향을 제시합니다.

**관련 자료**

- [stablyai/orca](https://github.com/stablyai/orca)
- [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- [anomalyco/opencode](https://github.com/anomalyco/opencode)
- [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)
- [android/skills](https://github.com/android/skills)
- [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify)
- [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory)
- [Context Engine](https://www.producthunt.com/products/context-engine-2)
- [AgentGrid.io](https://www.producthunt.com/products/agentgrid-io)
- [Google ADK v2.13.0](https://github.com/google/adk-python/releases/tag/v2.13.0)
- [CrewAI 1.15.30](https://github.com/crewAIInc/crewAI/releases/tag/1.15.30)

#### 4. 에이전트 신뢰성 인프라 — 트레이스 디버깅, 게이트웨이, 자격증명 위임

**핵심 인사이트**

에이전트가 실제 업무에 들어가면서 **"무엇을 잘못했는지 찾아내는"** 도구가 따로 하나의 시장이 되고 있습니다. **Laminar**는 에이전트 트레이스에서 오류를 찾도록 **RL로 학습한 모델**을 내놨고, **Specsight**는 AI로 빠르게 출시하는 팀을 위한 프로덕트 관측성 도구를 표방합니다.

통제 지점도 늘고 있습니다. **Respan**은 플러그인 구조의 **오픈소스 Rust AI 게이트웨이**이고, **1Password for Agents**는 에이전트가 비밀번호를 보지 않고도 로그인할 수 있게 해줍니다. 에이전트에게 권한은 주되 **비밀은 주지 않는** 위임 모델이 점점 표준으로 굳어지는 모습입니다.

연구 쪽 근거도 같은 방향을 가리킵니다. **EpiSEM-Bench**는 도구 응답에서 안전 관련 사실이 빠졌을 때 에이전트가 금지된 행동을 실행해 버릴 수 있다는 점을 평가합니다. 입력이 불완전할 때 멈추고 근거를 다시 찾는 능력이 에이전트 안전성의 핵심 지표가 되고 있습니다.

**관련 자료**

- [Launch HN: Laminar (YC S24) – RL-trained model that finds errors in agent traces](https://news.ycombinator.com/item?id=50154029)
- [Launch HN: Respan (YC W24) – Open-source Rust AI gateway built around plugins](https://news.ycombinator.com/item?id=50167583)
- [1Password for Agents](https://www.producthunt.com/products/1password)
- [Specsight](https://www.producthunt.com/products/specsight)
- [EpiSEM-Bench: Evaluating Safety and Evidence Recovery in LLM Agents under Missing Evidence](http://arxiv.org/abs/2610.31650v1)

#### 5. ROI 회의론과 반발 — "기술 밖에선 재무 성과 0"

**핵심 인사이트**

**Apollo** 이코노미스트는 막대한 투자와 과열된 기대에도 AI가 **기술 업계 밖 미국 기업에는 재무적 성과를 전혀 내지 못했다**고 진단했습니다. 모델 성능 경쟁이 치열해지는 와중에 나온 지적이라, 도입 효과를 숫자로 보여달라는 압박이 커지고 있습니다.

반대 방향의 사례도 있습니다. **AT&T**의 LegalEdge 팀은 OpenAI와 함께 법무 접수 과정을 재설계해 **법률 판단을 조직 전체로 확장**하고 있습니다. **Moshi**는 "AI 도구는 트레이더의 워크플로에 맞아야 한다"고 강조합니다. 결국 ROI가 나는 곳은 범용 도입이 아니라 **특정 업무 흐름을 다시 설계한 곳**이라는 신호입니다.

소셜에서는 반발이 더 거셉니다. **Anthony Moser**의 "AI 담론은 우리의 사회적 예의를 악용한다"는 글이 큰 반응(❤ 738)을 얻었고, **Emily M. Bender**는 공격적인 인용 게시물 때문에 차단을 적극적으로 쓰기 시작했다고 밝혔습니다. 기술 커뮤니티 바깥의 정서는 기술 진보 속도와 반대로 움직이고 있습니다.

**관련 자료**

- [AI delivers 'zero financial payoff' to most companies, Apollo economist says](https://techcrunch.com/2026/10/25/ai-delivers-zero-financial-payoff-to-most-companies-according-to-apollo-economist/)
- [How AT&T is rethinking in-house legal work with OpenAI](https://openai.com/index/att-legal)
- [You are the Team — Anekha Sokhal, Moshi](https://latent.space/p/moshi/)
- [Anthony Moser (Bluesky)](https://bsky.app/profile/anthonymoser.com/post/3mymxu6l22c2e)
- [Emily M. Bender (Bluesky)](https://bsky.app/profile/emilymbender.bsky.social/post/3mynbn5pg2cb3)

---

### 주목할 만한 개별 발견

#### Opus 5.5로 만든 브라우저 RTS, 일주일 만에 포크까지

- 출처: [battledrones v14: Compass Rose, a four player map](https://simonwillison.net/2026/Oct/24/battledrones/)

**Simon Willison**은 주로 **Claude Opus 5.5**로 Command & Conquer 스타일 RTS인 **Battle Drones**를 만들었습니다. 브라우저에서 돌아가고, **오디오 링크로 기기 간 멀티플레이**까지 지원합니다. 공개 하루도 안 돼 벨 에포크 스팀펑크 버전의 프랑스어 포크가 나왔고, 일주일 안에 4인용 맵(v14)까지 추가됐습니다.

개인 한 명이 프롬프트로 게임을 만들고 커뮤니티가 바로 포크하는 속도는 **"바이브 코딩"이 장난감 수준을 넘어섰다**는 걸 보여줍니다. 원 게시물은 [Bluesky](https://bsky.app/profile/simonwillison.net/post/3mydffvspjs2x)에서 볼 수 있습니다.

#### 왜 AI 컴퓨트는 '직사각형'으로 팔리나

- 출처: [Why AI Compute Comes in Rectangles — Erik Bernhardsson, Modal CEO](https://latent.space/p/modal-d/)

**Modal** CEO **Erik Bernhardsson**은 **탄력적 GPU**, **샌드박스 수요 증가**, **에이전트 클라우드의 경제학**을 다룹니다. 에이전트가 늘어날수록 GPU 추론뿐 아니라 코드를 실행하는 격리 샌드박스가 새로운 컴퓨트 수요가 된다는 관점입니다.

#### CoT는 정말 답을 '만들고' 있나

- 출처: [Causal Chain of Thought: Mitigating Attention Leakage via Context Isolation](http://arxiv.org/abs/2610.31639v1)

일반적인 자기회귀 생성에서는 Chain-of-thought의 추론 단계가 최종 답을 **인과적으로 결정한다는 보장이 없습니다**. 이 논문은 **컨텍스트 격리**로 어텐션 누수를 막아 추론과 답의 인과 관계를 강제하는 방법을 제안합니다. 추론 모델의 설명 가능성과 신뢰성 논의에 직접 연결되는 연구입니다.

#### 오분류 비용이 크면 '판단 보류'가 답이다

- 출처: [Cost-Aware Abstention for LLM-Based IT Ticket Classification](http://arxiv.org/abs/2610.31657v1)

IT 티켓을 잘못 자동 라우팅하면 사람이 직접 분류하는 것보다 비용이 더 클 수 있습니다. 이 연구는 비용 조건에 따라 **언제 LLM이 판단을 보류하고 사람에게 넘길지**를 사전에 평가하는 프레임을 제시합니다. 앞서 본 **ROI 회의론**에 대한 실무적인 해법 중 하나입니다.

</div>

<aside class="ai-home-aside">
  <section class="ai-week-block">
    <p class="ai-eyebrow">THIS WEEK</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20261031/">
    <span class="ai-pick-date">2026-10-31</span>
    <span class="ai-pick-title-mini">CopilotKit/OpenBot — AI 동료마다 전용 컴퓨터를 주고 모든 행동을 실행 전 결정·실행 후 …</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20261030/">
    <span class="ai-pick-date">2026-10-30</span>
    <span class="ai-pick-title-mini">How we detect frontier model misalignment</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20261029/">
    <span class="ai-pick-date">2026-10-29</span>
    <span class="ai-pick-title-mini">How Anthropic ships Claude with Claude: Separating the Brain…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20261028/">
    <span class="ai-pick-date">2026-10-28</span>
    <span class="ai-pick-title-mini">Greptile takes bug detection beyond code review with GPT-6 A…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20261027/">
    <span class="ai-pick-date">2026-10-27</span>
    <span class="ai-pick-title-mini">nightly-labs/openbot — Codex·Claude·Grok을 상주 팀원처럼 운영하는 로컬 우선…</span>
  </a>
</li>
    </ul>
  </section>
  <section class="ai-week-block">
    <p class="ai-eyebrow">LAST WEEK</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20261024/">
    <span class="ai-pick-date">2026-10-24</span>
    <span class="ai-pick-title-mini">Donating Agent Skills to the Agentic AI Foundation</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20261023/">
    <span class="ai-pick-date">2026-10-23</span>
    <span class="ai-pick-title-mini">Claude Duet app is Anthropic's bet on agents</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20261022/">
    <span class="ai-pick-date">2026-10-22</span>
    <span class="ai-pick-title-mini">Claude Mods: Flipping the Harness Inside Out</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20261021/">
    <span class="ai-pick-date">2026-10-21</span>
    <span class="ai-pick-title-mini">cloudflare/security-audit-skill — 독립 검증된 기계 판독형 결과를 내는 다단계 보…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20261020/">
    <span class="ai-pick-date">2026-10-20</span>
    <span class="ai-pick-title-mini">Satya Nadella — 모델을 내부자 위험으로 보는 원칙에 따라 Project Perception 확장</span>
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
