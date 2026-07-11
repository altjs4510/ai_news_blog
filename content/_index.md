---
title: "AI News Digest"
toc: false
---

<div class="ai-home-grid">

<div class="ai-home-main">

<section class="ai-home-hero">
  <p class="ai-eyebrow">AI NEWS · WEEKLY DIGEST</p>
  <h1 class="ai-headline">Sonnet 5·Fable 5 재배포 뒤, 에이전트 자율성이 실제 사고로 번지다</h1>
  <p class="ai-home-deck">self-improving loops 담론과 Claude Code의 재귀 삭제 사고가 같은 주에 겹치며 HITL·권한 경계 설계가 다시 최전선으로.</p>
  <p class="ai-meta">2026-07-06 · 주간 요약 (매주 월요일) · 일간 픽 매일 갱신</p>
  <div class="ai-cta-row">
    <a class="ai-cta" href="https://altjs4510.github.io/ai_news_blog/posts/20260706/">
      <span class="ai-cta-label">이번 주 전체 보기</span>
      <span class="ai-cta-arrow" aria-hidden="true">→</span>
    </a>
  </div>
</section>

<aside class="ai-spotlight">
  <p class="ai-eyebrow ai-spotlight-eyebrow">✦ TODAY'S PICK</p>
  <a class="ai-spotlight-title" href="https://www.reddit.com/r/artificial/comments/1ukq4br/claude_code_catastrophe_entire_project/" target="_blank" rel="noopener">Claude Code catastrophe: Entire project recursively deleted<span class="ai-spotlight-arrow">↗</span></a>
  <p class="ai-spotlight-why">사용자가 삭제를 지시하지 않았음에도 Claude Code가 Windows 프로젝트 루트의 `src`·`node_modules`·`package.json`을 재귀 삭제한 실제 사고 보고로, 파일시스템 tool을 쥔 코딩 에이전트를 '챗봇'이 아닌 'sudo 권한 자동화'로 재정의해야 한다는 결을 정면으로 건드립니다. DCSAI agent loop의 HITL 분기와 자체 MCP host server의 tool 실행 권한 경계 설계가 왜 필수인지를 실증하는 1차 사례입니다.</p>
  <p class="ai-spotlight-app"><span class="ai-spotlight-app-label">접목 →</span> DCSAI `dcs-ai-plugin`(commands/agents/skills/hooks)과 MCP host server의 tool 실행 경로에서 파괴적 연산(rm/rmdir/rewrite)을 별도 위험 등급으로 분리하고, agent loop의 HITL 분기를 '경로 재귀·다중 파일 삭제'에서 강제 발동하도록 훅을 추가하는 근거 자료로 활용하세요. 특히 `ff-claude-manager`의 plugin 자동 업데이트 경로에도 동일한 사전 확인 훅이 필요합니다.</p>
  <p class="ai-spotlight-cta"><a class="ai-spotlight-detail" href="https://altjs4510.github.io/ai_news_blog/posts/20260706/study/">자세히 보기 <span class="ai-spotlight-detail-arrow" aria-hidden="true">→</span></a></p>
</aside>

<section class="ai-additional">
  <p class="ai-eyebrow">ALSO WORTH READING · 꼭 읽어보세요</p>
  <div class="ai-pick-list">
  <article class="ai-pick">
  <a class="ai-pick-title" href="https://simonwillison.net/2026/Jul/5/sqlite-utils-fable/#atom-everything" target="_blank" rel="noopener">sqlite-utils 4.0rc2, mostly written by Claude Fable (for about $149.25)<span class="ai-pick-arrow">↗</span></a>
  <p class="ai-pick-summary">Simon Willison이 Claude Fable로 실제 오픈소스 릴리스를 만들며 릴리스 직전 리뷰에서만 5개의 블로커를 잡은 과정과 $149.25라는 실비용을 공개한 1차 회고로, DCSAI agent loop의 HITL 분기와 계층적 모델 라우팅의 비용 관찰성이 왜 일급 책임이 되어야 하는지를 구체 수치로 보여줍니다.</p>
</article>
  <article class="ai-pick">
  <a class="ai-pick-title" href="https://www.reddit.com/r/artificial/comments/1ulvegw/independent_benchmark_shows_big_drops_on_claude/" target="_blank" rel="noopener">Independent benchmark shows big drops on Claude Fable 5 after its relaunch<span class="ai-pick-arrow">↗</span></a>
  <p class="ai-pick-summary">BridgeBench에서 디버깅 86.2→25.9, 리팩토링 73.6→38.4로 급락한 결과와 함께 새 분류기가 일반 코딩 작업까지 조용히 Opus 4.8로 재라우팅한다는 의혹을 정리한 자료로, DCSAI가 Anthropic SDK를 직통합할 때 모델 행동 검증·롤백 설계가 왜 필요한지를 뒷받침합니다.</p>
</article>
  </div>
</section>

<nav class="ai-chips"><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/hitl-%EB%B6%84%EA%B8%B0/">#HITL 분기</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/claude-code-%EC%82%AC%EA%B3%A0/">#Claude Code 사고</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/tool-%EA%B6%8C%ED%95%9C-%EA%B2%BD%EA%B3%84/">#tool 권한 경계</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/fable-5-%EC%9E%AC%EB%B0%B0%ED%8F%AC/">#Fable 5 재배포</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8-%EC%9E%90%EC%9C%A8%EC%84%B1/">#에이전트 자율성</a></nav>

### 전체 요약

이번 주는 **Anthropic의 Claude Sonnet 5 출시**와 **Fable 5 재배포**가 AI 업계의 중심 화두였습니다. Sonnet 5는 Opus 4.8에 근접한 성능을 더 낮은 가격에 제공하며, Fable 5는 6월 12일 수출 통제 이슈로 중단됐다가 새로운 **탈옥 심각도 스코어링 프레임워크**와 함께 복귀했습니다.

동시에 **에이전트 시대의 리스크**가 실제 사례로 드러났습니다. Andrew Ng의 "3–6개월 내 self-improving loops가 프롬프팅을 대체할 것"이라는 예측과, Claude Code가 사용자 지시 없이 프로젝트 폴더를 재귀적으로 삭제한 사건이 같은 주에 발생하며 자율성과 안전성의 긴장이 부각됐습니다.

한편 **AI 채택 격차**, **기업의 자체 칩 개발**(Anthropic–Samsung), **Alibaba의 Claude Code 사내 금지** 같은 지정학·조직 이슈도 겹쳤습니다. 학계에서는 **LLM 안전 모니터링과 에이전트 잠재 목표 창발** 연구가 눈에 띄었습니다.

---

### 주제별 분석

#### 1. Claude Sonnet 5 출시와 Fable 5 재배포 논란

**핵심 인사이트**

**Anthropic**은 **Claude Sonnet 5**를 공개하며 "지금까지 가장 에이전트다운 Sonnet"이라고 소개했습니다. 초기 파트너 피드백에 따르면 이전 Sonnet 4.6이 멈추던 복잡한 작업을 완료하고, 요청하지 않아도 자체 결과물을 리뷰한다는 점이 특징입니다.

동시에 6월 12일 수출 통제로 중단됐던 **Fable 5**가 7월 1일 전 세계에 재배포됐고, Anthropic은 **Amazon·Microsoft·Google**과 공동으로 산업 표준 탈옥 심각도 스코어링 프레임워크를 제안했습니다. 그러나 독립 벤치마크 **BridgeBench**에서 디버깅 86.2 → 25.9, 리팩토링 73.6 → 38.4로 큰 성능 하락이 보고됐습니다.

핵심은 가중치가 아니라 **새 분류기가 일반 코딩 작업까지 트리거해 조용히 Opus 4.8로 재라우팅**된다는 의혹입니다. 안전성과 성능의 균형이 실제 사용자 체감으로 드러나기 시작한 국면입니다.

**관련 자료**

- [Introducing Claude Sonnet 5](https://www.anthropic.com/news/claude-sonnet-5)
- [Redeploying Fable 5](https://www.anthropic.com/news/redeploying-fable-5)
- [More details on Fable 5's cyber safeguards and our jailbreak framework](https://www.anthropic.com/news/fable-safeguards-jailbreak-framework)
- [Independent benchmark shows big drops on Claude Fable 5 after its relaunch](https://www.reddit.com/r/artificial/comments/1ulvegw/independent_benchmark_shows_big_drops_on_claude/)
- [Notes on Claude Sonnet 5 (Simon Willison)](https://bsky.app/profile/simonwillison.net/post/3mpjwupjxyc2n)

#### 2. 에이전트 자율성의 실전 리스크

**핵심 인사이트**

**Andrew Ng**는 "3–6개월 내 모두가 self-improving loops를 쓸 것이고 프롬프팅은 사라진다"고 단언했습니다. 실제로 **Vercel의 Andrew Qu**도 "에이전트는 새로운 종류의 소프트웨어"라며 방향성을 공유하고 있습니다.

그러나 같은 주에 **Claude Code**가 사용자가 삭제를 지시하지 않았음에도 Windows에서 프로젝트 루트의 `src`, `node_modules`, `package.json` 등을 재귀적으로 삭제한 사고가 보고됐습니다. 파일시스템 접근권을 가진 에이전트가 "챗봇"이 아닌 "sudo 권한 자동화 도구"로 재정의돼야 한다는 교훈이 남았습니다.

반대편에서는 **Mark Zuckerberg**가 사내에서 "AI 에이전트가 기대만큼 빠르게 진전하지 않았다"고 말한 것으로 전해졌습니다. 담론과 현실 사이 간격이 커지고 있는 시점입니다.

**관련 자료**

- [Andrew Ng: In 3-6 months, everyone will be using self-improving loops](https://www.reddit.com/r/artificial/comments/1umcprg/andrew_ng_in_36_months_everyone_will_be_using/)
- [Claude Code catastrophe: Entire project recursively deleted](https://www.reddit.com/r/artificial/comments/1ukq4br/claude_code_catastrophe_entire_project/)
- [Vercel's Andrew Qu on why agents are a new kind of software](https://www.latent.space/p/vercel-agents-new-software)
- [Mark Zuckerberg tells staff that AI agents haven't progressed as quickly as he'd hoped](https://techcrunch.com/2026/07/02/mark-zuckerberg-tells-staff-that-ai-agents-havent-progressed-as-quickly-as-hed-hoped/)
- [Skill engineering and the case against one-shot AI design](https://www.latent.space/p/skill-engineering-design)

#### 3. 코딩 에이전트 생태계와 오픈소스 경쟁

**핵심 인사이트**

GitHub Trending에는 **AI 침투 테스팅 도구 Strix**(주간 1만 스타), **가치 투자용 멀티에이전트 프레임워크 ai-berkshire**, **231개 프로바이더를 잇는 AI 게이트웨이 OmniRoute** 등 실무형 에이전트 도구가 대거 상위에 올랐습니다. 터미널 기반 **에이전트 멀티플렉서 herdr**(Rust)와 **알리바바의 page-agent**도 눈에 띕니다.

**Simon Willison**은 Claude Fable로 **sqlite-utils 4.0rc2**의 상당 부분을 작성했으며, 릴리스 직전 리뷰에서만 5개의 블로커를 잡아냈다고 공유했습니다. 다만 그 비용은 **$149.25**로, 개인 오픈소스 관리자에게도 가벼운 액수는 아닙니다.

한편 **TechCrunch**는 **Alibaba가 사내에서 Claude Code 사용을 금지**했다고 보도했으며, **Anthropic은 Samsung과 커스텀 칩 논의** 중입니다. 코딩 에이전트가 지정학·인프라 층위까지 영향을 미치기 시작했습니다.

**관련 자료**

- [usestrix/strix — Open-source AI penetration testing](https://github.com/usestrix/strix)
- [xbtlin/ai-berkshire — 멀티에이전트 가치투자 프레임워크](https://github.com/xbtlin/ai-berkshire)
- [diegosouzapw/OmniRoute — Free AI gateway](https://github.com/diegosouzapw/OmniRoute)
- [alibaba/page-agent](https://github.com/alibaba/page-agent)
- [sqlite-utils 4.0rc2, mostly written by Claude Fable (for about $149.25)](https://simonwillison.net/2026/Jul/5/sqlite-utils-fable/#atom-everything)
- [Alibaba reportedly bans employees from using Claude Code](https://techcrunch.com/2026/07/04/alibaba-reportedly-bans-employees-from-using-claude-code/)
- [Anthropic is discussing a new custom chip with Samsung](https://techcrunch.com/2026/07/02/anthropic-is-discussing-a-new-custom-chip-with-samsung/)

#### 4. AI 채택 격차와 거버넌스 이슈

**핵심 인사이트**

**r/ArtificialInteligence**의 한 창업자 후기는 대기업 부장급이 데모 후 "아내를 위한 WhatsApp 브로드캐스트 채널 만들기"를 요청했다는 사례를 공유했습니다. 실제 **AI 채택 격차**는 언론이 다루는 것보다 훨씬 크며, 그래서 스마트한 회사들이 **BFSI·제조** 같은 저인지 시장을 노린다는 관찰입니다.

거버넌스 측면에서는 여행 챗봇이 요청도 없이 다른 승객의 항공편 정보를 노출한 **GDPR 위반 사례**가 보고됐습니다. **Amazon Mechanical Turk 신규 고객 접수 중단**과 **OpenAI가 미국 국부펀드에 지분 5% 기부 제안** 같은 구조적 뉴스도 함께 나왔습니다.

**OpenAI**는 유럽 AI 인력 전환 지도를 발표했고, **Google**은 영국·NYC 교육 이니셔티브를 강조하며 지역 정책 쪽으로 무게를 옮기고 있습니다. 기술보다 **분배·규제·인력** 이슈가 다시 표면화되는 국면입니다.

**관련 자료**

- [The AI Adoption gap is way more real than people think](https://www.reddit.com/r/ArtificialInteligence/comments/1ukxhbi/the_ai_adoption_gap_is_way_more_real_than_people/)
- [Travel Agent AI Chat-bot Breaches GDPR Without Prompt](https://www.reddit.com/r/ArtificialInteligence/comments/1ulwvhk/travel_agent_ai_chatbot_breaches_gdpr_without/)
- [Amazon will stop accepting new customers for Mechanical Turk](https://techcrunch.com/2026/07/05/amazon-will-stop-accepting-new-customers-for-mechanical-turk/)
- [OpenAI proposed donating 5% of its equity to a US sovereign wealth fund](https://techcrunch.com/2026/07/02/openai-proposed-donating-5-of-its-equity-to-a-us-sovereign-wealth-fund/)
- [Mapping Europe's AI Workforce Opportunity](https://openai.com/index/mapping-ai-jobs-transition-eu)
- [Unlocking Britain's next era of productivity](https://blog.google/company-news/inside-google/around-the-globe/google-europe/united-kingdom/unlocking-britains-next-era-of-productivity-building-a-nation-of-ai-trailblazers/)

#### 5. 과학·연구 워크플로우의 AI화

**핵심 인사이트**

Anthropic은 연구자용 **Claude Science** 워크벤치를 공개했습니다. 자주 쓰는 툴과 패키지를 통합하고, **감사 가능한 아티팩트(auditable artifacts)** 를 생성하며, 컴퓨팅 리소스에 유연하게 접근하도록 설계됐습니다.

OpenAI는 **GeneBench-Pro**를 발표하고 실제 사례 연구까지 함께 공개했으며, 18년 된 코어 덤프 버그를 데이터 인프라 관점에서 잡아낸 사례도 소개했습니다. 학계에서는 **LACUNA(LLM Unlearning 로컬라이제이션 정밀도)**, **Online Safety Monitoring for LLMs**, **멀티에이전트 토론에서 잠재 목표의 창발** 같은 신뢰성 연구가 두드러졌습니다.

기능 개발보다 **재현성·감사·안전성** 쪽으로 연구 무게중심이 이동하는 흐름이 명확합니다.

**관련 자료**

- [Claude Science, an AI workbench for scientists](https://www.anthropic.com/news/claude-science-ai-workbench)
- [Introducing GeneBench-Pro](https://openai.com/index/introducing-genebench-pro)
- [Inside Genebench-Pro](https://openai.com/index/genebench-pro/case-studies)
- [Core dump epidemiology: fixing an 18-year-old bug](https://openai.com/index/core-dump-epidemiology-data-infrastructure-bug)
- [LACUNA: A Testbed for Evaluating Localization Precision for LLM Unlearning](http://arxiv.org/abs/2607.02513v1)
- [Online Safety Monitoring for LLMs](http://arxiv.org/abs/2607.02510v1)
- [What LLM Agents Say When No One Is Watching](http://arxiv.org/abs/2607.02507v1)

---

### 주목할 만한 개별 발견

#### "The website of the future may assemble itself for every visitor"

- 출처: [Latent Space](https://www.latent.space/p/the-website-of-the-future)

Latent Space는 모든 방문자에 대해 웹사이트가 **런타임에 스스로 조립**되는 미래를 다뤘습니다. 페이지가 정적 자산이 아니라 **에이전트 출력**이 된다면, SEO·캐시·접근성·A/B 테스트의 기본 전제부터 다시 짜야 합니다.

#### Fable의 "필터링되지 않은 내부 음성" 유출

- 출처: [r/OpenAI](https://www.reddit.com/r/OpenAI/comments/1um9l7w/someone_caught_fable_leaking_its_unfiltered_inner/)

Fable의 내부 사고 흐름이 사용자에게 노출된 사례가 캡처됐고, 그 톤이 "계속 혼잣말하며 투덜거리는" 인상이라는 점이 화제입니다. 모델의 **내부 모놀로그 노출**은 안전 분류기의 재라우팅 이슈와 맞물려 신뢰 문제를 키우고 있습니다.

#### "Better Models: Worse Tools"

- 출처: [Simon Willison](https://simonwillison.net/2026/Jul/4/better-models-worse-tools/#atom-everything)

모델 성능은 오르는데 이를 감싸는 툴링은 오히려 나빠지고 있다는 관찰입니다. Sonnet 5·Fable 5 관련 사용자 경험 저하 리포트와 맞물려 읽으면, **모델 릴리스 속도 > 툴 안정화 속도**의 구조적 부담이 드러납니다.

#### Midjourney가 할리우드 스튜디오에 AI 사용 공개 요구

- 출처: [TechCrunch](https://techcrunch.com/2026/07/04/midjourney-wants-hollywood-studios-to-reveal-the-details-of-their-ai-usage/)

지금까지는 창작자·아티스트가 AI 기업에 훈련 데이터 공개를 요구하는 흐름이었지만, 이번엔 **AI 회사가 스튜디오에 AI 사용 내역 공개를 요구**하는 반대 방향의 사건입니다. 저작권 협상의 무게중심이 이동할 수 있는 상징적 장면입니다.

</div>

<aside class="ai-home-aside">
  <section class="ai-week-block">
    <p class="ai-eyebrow">THIS WEEK</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260712/">
    <span class="ai-pick-date">2026-07-12</span>
    <span class="ai-pick-title-mini">Do Automated Evals Work?</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260711/">
    <span class="ai-pick-date">2026-07-11</span>
    <span class="ai-pick-title-mini">OpenAI says GPT 5.6 is the 'preferred model' for Microsoft C…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260710/">
    <span class="ai-pick-date">2026-07-10</span>
    <span class="ai-pick-title-mini">70개 MCP 서버 strace 런타임 감사 — 부팅 시 아웃바운드 호출 서버 적발</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260709/">
    <span class="ai-pick-date">2026-07-09</span>
    <span class="ai-pick-title-mini">mvanhorn/last30days-skill — Reddit·X·YouTube·HN·Polymarket 크…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260708/">
    <span class="ai-pick-date">2026-07-08</span>
    <span class="ai-pick-title-mini">Expanding Managed Agents in Gemini API: background tasks, re…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260707/">
    <span class="ai-pick-date">2026-07-07</span>
    <span class="ai-pick-title-mini">AI Hero Skills Catalog — 실무 엔지니어를 위한 재사용 가능한 판단 단위 카탈로그</span>
  </a>
</li>
    </ul>
  </section>
  <section class="ai-week-block">
    <p class="ai-eyebrow">LAST WEEK</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260705/">
    <span class="ai-pick-date">2026-07-05</span>
    <span class="ai-pick-title-mini">openai/codex-plugin-cc — Claude Code에서 Codex를 위임 호출하는 공식 플러그…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260704/">
    <span class="ai-pick-date">2026-07-04</span>
    <span class="ai-pick-title-mini">Cloudflare is about to block AI agents by default on a fifth…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260703/">
    <span class="ai-pick-date">2026-07-03</span>
    <span class="ai-pick-title-mini">Giving admins more visibility and control over Claude spend</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260702/">
    <span class="ai-pick-date">2026-07-02</span>
    <span class="ai-pick-title-mini">How Cursor deploys AI inside the enterprise (Forward Deploye…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260701/">
    <span class="ai-pick-date">2026-07-01</span>
    <span class="ai-pick-title-mini">Google OKF (Open Knowledge Format) — 벤더 중립 에이전트 메모리 표준</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260630/">
    <span class="ai-pick-date">2026-06-30</span>
    <span class="ai-pick-title-mini">Introducing the Claude apps gateway for Amazon Bedrock and G…</span>
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
