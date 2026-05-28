---
title: "AI News Digest"
toc: false
---

<div class="ai-home-grid">

<div class="ai-home-main">

<section class="ai-home-hero">
  <p class="ai-eyebrow">AI NEWS · WEEKLY DIGEST</p>
  <h1 class="ai-headline">토큰 경제가 빅테크 예산을 무너뜨리고, Google은 agentic Gemini로 응수하다</h1>
  <p class="ai-home-deck">MS의 Anthropic 라이선스 취소와 Salesforce의 '엔지니어 0명·토큰 3억 달러' 구조 전환이 AI 운영 단위경제성을 재정의합니다.</p>
  <p class="ai-meta">2026-05-25 · 주간 요약 (매주 월요일) · 일간 픽 매일 갱신</p>
  <div class="ai-cta-row">
    <a class="ai-cta" href="https://altjs4510.github.io/ai_news_blog/posts/20260525/">
      <span class="ai-cta-label">이번 주 전체 보기</span>
      <span class="ai-cta-arrow" aria-hidden="true">→</span>
    </a>
  </div>
</section>

<aside class="ai-spotlight">
  <p class="ai-eyebrow ai-spotlight-eyebrow">✦ TODAY'S PICK</p>
  <a class="ai-spotlight-title" href="https://github.com/rohitg00/agentmemory" target="_blank" rel="noopener">rohitg00/agentmemory — Persistent memory for AI coding agents<span class="ai-spotlight-arrow">↗</span></a>
  <p class="ai-spotlight-why">코딩 에이전트용 퍼시스턴트 메모리 레이어를 실측 벤치마크로 검증한 신규 트렌딩 레포로, 단발성 tool use를 넘어 세션·프로젝트 축으로 컨텍스트를 누적시키는 패턴을 다룹니다. DCSAI agent loop의 HITL 분기와 Team Agent의 Activity Log/Observer가 정조준하는 '시간축 메모리' 결을 정면으로 건드립니다.</p>
  <p class="ai-spotlight-app"><span class="ai-spotlight-app-label">접목 →</span> Team Agent `discovery-core-agent`의 Activity Log → Observer → UI refresh 루프에 perspective memory layer로 결합해, Quest(전체·파티·플레이어) 단위 컨텍스트를 세션 간 유지하는 PoC에 바로 활용 가능합니다. DCSAI agent loop에서는 HITL 분기 직전 메모리 조회 훅으로 붙여 토큰 누적을 줄이는 실험이 자연스럽습니다.</p>
  <p class="ai-spotlight-cta"><a class="ai-spotlight-detail" href="https://altjs4510.github.io/ai_news_blog/knowledge/20260512/">자세히 보기 <span class="ai-spotlight-detail-arrow" aria-hidden="true">→</span></a></p>
</aside>

<section class="ai-additional">
  <p class="ai-eyebrow">ALSO WORTH READING · 꼭 읽어보세요</p>
  <div class="ai-pick-list">
  <article class="ai-pick">
  <span class="ai-pick-title">Microsoft Cancels Internal Anthropic Licenses as Token Billing Explodes</span>
  <p class="ai-pick-summary">토큰 기반 청구가 빅테크 내부 예산까지 흔드는 첫 가시 사례로, Salesforce의 '연 3억 달러 토큰·신입 0명' 케이스와 묶어 읽으면 DCSAI·Team Agent 운영비 산정에서 '컨텍스트 세금'을 1급 KPI로 다뤄야 할 이유가 분명해집니다.</p>
</article>
  <article class="ai-pick">
  <a class="ai-pick-title" href="https://claude.com/blog/claude-managed-agents-updates" target="_blank" rel="noopener">New in Claude Managed Agents: self-hosted sandboxes and MCP tunnels<span class="ai-pick-arrow">↗</span></a>
  <p class="ai-pick-summary">Anthropic이 Managed Agents에 셀프호스팅 샌드박스와 MCP 터널을 1급 시민으로 추가했습니다. DCSAI가 자체 구현 중인 MCP host server(OAuth·세션·tool 실행)와 외부 dcsai KG MCP 노출 결의 미래 호환 경로를 직접 비교 학습할 수 있는 1차 자료입니다.</p>
</article>
  </div>
</section>

<nav class="ai-chips"><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%ED%8D%BC%EC%8B%9C%EC%8A%A4%ED%84%B4%ED%8A%B8-%EB%A9%94%EB%AA%A8%EB%A6%AC/">#퍼시스턴트 메모리</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%ED%86%A0%ED%81%B0-%EA%B2%BD%EC%A0%9C/">#토큰 경제</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/agentic-gemini/">#agentic Gemini</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/mcp-%ED%84%B0%EB%84%90/">#MCP 터널</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EC%97%94%ED%84%B0%ED%94%84%EB%9D%BC%EC%9D%B4%EC%A6%88-%EC%BD%94%EB%94%A9-%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8/">#엔터프라이즈 코딩 에이전트</a></nav>

### 전체 요약

이번 주 AI 산업의 가장 큰 흐름은 **Google I/O 2026**의 대규모 발표와 **Gemini 3.5** 공개로 요약됩니다. Google은 "agentic Gemini era"를 선언하며 검색, Workspace, AI 구독 전반을 에이전트 중심으로 재편했고, OpenAI·Anthropic도 각자 **Codex/Claude Code** 기반 엔터프라이즈 확장과 파트너십(Dell, KPMG, Singapore 등)을 가속화했습니다.

동시에 **AI 비용 구조의 충격**이 본격적으로 가시화되고 있습니다. Microsoft가 토큰 기반 청구 폭증으로 내부 Anthropic 라이선스를 취소하고, Salesforce는 Anthropic 토큰에만 연 3억 달러를 쓰는 한편 신입 엔지니어 채용을 0명으로 유지하는 등 "**고용 대신 토큰 지출**"이라는 구조 전환이 명확해지고 있습니다.

연구·오픈소스 진영에서는 **에이전트 인프라**(스테이트풀 샌드박스, 코드 지식 그래프, 영구 메모리)와 **자기개선·자가진화 에이전트**(MOSS, Karpathy의 Anthropic 합류)가 키워드로 떠올랐습니다. 동시에 AI 보안·콘텐츠 출처 검증 이슈도 Google·OpenAI 차원에서 본격 다뤄지고 있습니다.

---

### 주제별 분석

#### 1. Google I/O 2026 — Agentic Gemini 시대 선언

**핵심 인사이트**

Google은 이번 I/O에서 **Gemini 3.5**를 공개하며 단순 모델 업그레이드가 아닌 "**행동하는 지능(frontier intelligence with action)**"을 전면에 내세웠습니다. Sundar Pichai는 직접 [agentic Gemini era](https://blog.google/innovation-and-ai/sundar-pichai-io-2026/) 진입을 선언했고, 검색·Workspace·AI 구독이 모두 에이전트 워크플로우로 재구성되었습니다.

특히 [A new era for AI Search](https://blog.google/products-and-platforms/products/search/search-io-2026/)와 [AI Mode](https://blog.google/products-and-platforms/products/search/ai-mode-us-insights/) 데이터는 검색 행동 자체가 바뀌고 있음을 보여줍니다. 한편 Simon Willison은 [Gemini 3.5 Flash가 이전 버전 대비 3배 가격](https://bsky.app/profile/simonwillison.net/post/3mmahk7bg3s2h)이라는 점을 지적하며, **성능 향상과 가격 인상의 동시 진행**이라는 업계 공통 패턴을 짚었습니다.

흥미롭게도 Product Hunt에서 **Google Antigravity CLI**, **Stitch 3.0**이 동시에 등장하며, Google이 개발자용 터미널 에이전트 영역까지 본격 진출한 점이 두드러집니다.

**관련 자료**

- [Gemini 3.5: frontier intelligence with action](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-5/)
- [I/O 2026: Welcome to the agentic Gemini era](https://blog.google/innovation-and-ai/sundar-pichai-io-2026/)
- [100 things we announced at I/O 2026](https://blog.google/innovation-and-ai/technology/ai/google-io-2026-all-our-announcements/)
- [Google Antigravity CLI](https://www.producthunt.com/products/google-antigravity)
- [Simon Willison — Gemini Spark/Antigravity 노트](https://bsky.app/profile/simonwillison.net/post/3mmcahayyqc2i)

#### 2. AI 비용 폭발 — 토큰 경제가 고용 구조를 바꾸다

**핵심 인사이트**

이번 주 가장 충격적인 흐름은 **토큰 기반 청구가 빅테크 예산까지 무너뜨리고 있다**는 사실입니다. r/artificial과 r/ArtificialInteligence에서는 [Microsoft가 내부 Anthropic 라이선스를 취소했다](https://www.reddit.com/r/artificial/comments/1tkb0op/microsoft_cancels_internal_anthropic_licenses_as/)는 보도가 화제였고, "인플레이션이 AGI를 취소했다"는 표현이 회자되었습니다.

Salesforce 사례는 더 구조적입니다. [Anthropic 토큰에 연 3억 달러를 지출하면서 2025년 1월 이후 신입 엔지니어 0명 채용](https://www.reddit.com/r/ArtificialInteligence/comments/1tismyo/300m_on_anthropic_tokens_zero_new_engineers_hired/), 지원 인력은 9,000명에서 5,000명으로 감축했습니다. **인건비가 토큰비로 이동하는** 분기점이 가시화된 셈입니다.

이는 [How VCs and founders use inflated 'ARR' to crown AI startups](https://techcrunch.com/2026/05/22/how-vcs-and-founders-use-inflated-arr-to-kingmake-ai-startups/)에서 다룬 ARR 부풀리기 논쟁과 맞물려, AI 경제의 단위 경제성(unit economics)에 대한 의구심을 키우고 있습니다.

**관련 자료**

- [Microsoft Cancels Internal Anthropic Licenses](https://www.reddit.com/r/artificial/comments/1tkb0op/microsoft_cancels_internal_anthropic_licenses_as/)
- [$300M on Anthropic tokens, zero new engineers hired](https://www.reddit.com/r/ArtificialInteligence/comments/1tismyo/300m_on_anthropic_tokens_zero_new_engineers_hired/)
- [How VCs and founders use inflated ARR](https://techcrunch.com/2026/05/22/how-vcs-and-founders-use-inflated-arr-to-kingmake-ai-startups/)

#### 3. 엔터프라이즈 코딩 에이전트 전쟁 — Codex vs Claude Code

**핵심 인사이트**

OpenAI는 Gartner로부터 [엔터프라이즈 코딩 에이전트 분야 Leader로 선정](https://openai.com/index/gartner-2026-agentic-coding-leader)되었음을 강조하며, [Virgin Atlantic](https://openai.com/index/virgin-atlantic), [Ramp](https://openai.com/index/ramp), 그리고 [Dell과의 하이브리드/온프레미스 파트너십](https://openai.com/index/dell-codex-enterprise-partnership)으로 **Codex의 기업 침투**를 가속화했습니다.

Anthropic은 [KPMG 27만 명 규모 전사 도입](https://www.anthropic.com/news/anthropic-kpmg)과 [API 툴체인 회사 Stainless 인수](https://www.anthropic.com/news/anthropic-acquires-stainless)로 응수했습니다. Claude Managed Agents에는 [self-hosted sandbox와 MCP tunnel](https://claude.com/blog/claude-managed-agents-updates)이 추가되어 보안 요구가 강한 기업 환경 대응을 강화했습니다.

GitHub Trending에서도 이 경쟁의 그림자가 보입니다. [codegraph](https://github.com/colbymchenry/codegraph)와 [Understand-Anything](https://github.com/Lum1104/Understand-Anything)은 **Claude Code/Codex/Cursor 모두를 지원하는 코드 지식 그래프**로 한 주에 1만 스타 이상을 모았는데, 이는 "어느 에이전트를 쓰든 토큰을 줄이려는" 개발자 수요를 직접 반영합니다.

**관련 자료**

- [OpenAI named a Leader in enterprise coding agents by Gartner](https://openai.com/index/gartner-2026-agentic-coding-leader)
- [OpenAI and Dell partner to bring Codex to hybrid and on-premise](https://openai.com/index/dell-codex-enterprise-partnership)
- [KPMG integrates Claude across its workforce of 276,000](https://www.anthropic.com/news/anthropic-kpmg)
- [Anthropic acquires Stainless](https://www.anthropic.com/news/anthropic-acquires-stainless)
- [codegraph — Pre-indexed code knowledge graph](https://github.com/colbymchenry/codegraph)
- [agentmemory — Persistent memory for AI coding agents](https://github.com/rohitg00/agentmemory)

#### 4. 자기개선 에이전트와 Karpathy의 이동

**핵심 인사이트**

OpenAI 공동창립자 **Andrej Karpathy의 Anthropic 합류**는 이번 주 커뮤니티에서 가장 뜨거운 이슈였습니다. r/OpenAI, r/ClaudeAI 모두에서 [Karpathy가 Claude의 자기개선(self-improvement)을 가르치기 위해 합류](https://www.reddit.com/r/OpenAI/comments/1tjotur/openai_cofounder_karpathy_joins_anthropic_to/)했다는 해석이 지배적이었습니다.

이 흐름은 학술 자료와도 정확히 일치합니다. arxiv의 [MOSS: Self-Evolution through Source-Level Rewriting in Autonomous Agent Systems](http://arxiv.org/abs/2605.22794v1)는 에이전트가 자기 소스 코드를 수정하며 진화하는 프레임워크를 제시했고, [DeltaBox](http://arxiv.org/abs/2605.22781v1)는 밀리초 단위 샌드박스 체크포인트로 **장기 실행 자율 에이전트의 인프라**를 제안합니다.

HuggingFace에서도 [ACC: Compiling Agent Trajectories for Long-Context Training](https://huggingface.co/papers/2605.21850)이 주목받으며, 에이전트 학습 데이터 자체를 자동 생성·압축하는 방향이 강해지고 있습니다. **인간 피드백 없이 자가진화하는 에이전트**가 2026년 핵심 연구 주제로 부상한 모습입니다.

**관련 자료**

- [Karpathy joins Anthropic](https://www.reddit.com/r/ClaudeAI/comments/1thpuf1/karpathy_joins_anthropic/)
- [Karpathy to teach Claude to improve itself without humans](https://www.reddit.com/r/OpenAI/comments/1tjotur/openai_cofounder_karpathy_joins_anthropic_to/)
- [MOSS: Self-Evolution through Source-Level Rewriting](http://arxiv.org/abs/2605.22794v1)
- [DeltaBox: Millisecond-Level Sandbox Checkpoint/Rollback](http://arxiv.org/abs/2605.22781v1)
- [ACC: Compiling Agent Trajectories](https://huggingface.co/papers/2605.21850)

#### 5. AI 보안·출처 검증·신뢰 인프라

**핵심 인사이트**

빅테크가 모두 동시에 **AI 보안 모델을 실시간으로 짜고 있다**는 점이 이번 주 드러났습니다. TechCrunch는 [Everyone is navigating AI security in real time — even Google](https://techcrunch.com/2026/05/24/everyone-is-navigating-ai-security-in-real-time-even-google/)에서 업계 전체의 즉흥적 대응을 지적했습니다.

OpenAI는 [콘텐츠 출처(content provenance) 강화](https://openai.com/index/advancing-content-provenance)로 생성물 추적 인프라를 공식화했고, Anthropic은 [컴플라이언스·보안 파트너 통합](https://claude.com/blog/compliance-api-security-partners)과 [Opus를 사이버보안 파트너에 적용한 사례](https://claude.com/blog/how-our-partners-are-putting-opus-to-work-for-cybersecurity)를 공개했습니다.

연구 측에서는 [LCGuard: Latent Communication Guard for Safe KV Sharing in Multi-Agent Systems](http://arxiv.org/abs/2605.22786v1)가 **에이전트 간 KV 캐시 공유 시 발생하는 새로운 보안 위협**을 다뤘는데, 멀티에이전트 시스템 확산과 함께 보안 표면이 빠르게 늘어나고 있음을 보여줍니다.

**관련 자료**

- [Everyone is navigating AI security in real time — even Google](https://techcrunch.com/2026/05/24/everyone-is-navigating-ai-security-in-real-time-even-google/)
- [Advancing content provenance](https://openai.com/index/advancing-content-provenance)
- [Claude now works with more security and compliance tools](https://claude.com/blog/compliance-api-security-partners)
- [How our partners are putting Opus to work for cybersecurity](https://claude.com/blog/how-our-partners-are-putting-opus-to-work-for-cybersecurity)
- [LCGuard: Latent Communication Guard](http://arxiv.org/abs/2605.22786v1)

---

### 주목할 만한 개별 발견

#### OpenAI 모델이 이산기하학 추측을 반증하다

- 출처: [An OpenAI model has disproved a central conjecture in discrete geometry](https://openai.com/index/model-disproves-discrete-geometry-conjecture)

OpenAI 모델이 이산기하학의 핵심 추측을 **실제로 반증**한 사건은 단순한 풀이 도우미를 넘어 수학 연구의 1차 생산자로 AI가 진입했음을 시사합니다. HuggingFace의 [Forecasting Scientific Progress with Artificial Intelligence](https://huggingface.co/papers/2605.22681) 흐름과 연결해 보면, **AI가 과학 발견의 속도와 방향 자체를 측정·예측하는 단계**로 넘어가고 있습니다.

#### "HTML의 비합리적 효과성" — 에이전트 UI의 재발견

- 출처: [Using Claude Code: The unreasonable effectiveness of HTML](https://claude.com/blog/using-claude-code-the-unreasonable-effectiveness-of-html)

Anthropic은 Claude Code가 복잡한 GUI 프레임워크 대신 **단순 HTML로 출력할 때 가장 강력하다**는 점을 공식화했습니다. 이는 에이전트가 인간을 위해 만든 도구가 아니라 **에이전트 친화적 출력 포맷**이 별도로 존재한다는 점을 시사하며, 향후 에이전트용 마크업/프로토콜 표준화 논의로 확장될 가능성이 높습니다.

#### "코딩하지만 코드는 읽지 않는다" — 시니어 엔지니어의 vibe coding 매뉴얼

- 출처: [I vibe code all of my side projects from my phone using Claude Code](https://www.reddit.com/r/ClaudeAI/comments/1tjpfh8/anthropic_officially_launched_13_free_ai_courses/)

10년 차 엔지니어가 **Plan Mode → 계획 검토 → 서브에이전트 보안/테스트 감사 → 자동 모드** 워크플로우를 정리한 글이 화제였습니다. 핵심은 "코드는 안 읽지만 **계획은 반드시 읽는다**"는 점으로, vibe coding 시대의 시니어 역할이 **코드 작성자에서 계획 검토자**로 재정의되고 있음을 잘 보여줍니다.

#### Spotify × Universal — 팬 메이드 AI 커버 합법화

- 출처: [Spotify and Universal Music strike deal allowing fan-made AI covers and remixes](https://techcrunch.com/2026/05/21/spotify-and-universal-music-strike-deal-allowing-fan-made-ai-covers-and-remixes/)

소송 일변도였던 음악 업계가 처음으로 **AI 커버·리믹스를 라이선스 구조 안에 편입**시켰습니다. 이는 "AI 생성물 vs 저작권"의 적대 구도가 **수익 분배 구조**로 전환되는 첫 메이저 사례로, 이미지·영상 영역의 향후 협상 템플릿이 될 가능성이 큽니다.

</div>

<aside class="ai-home-aside">
  <section class="ai-week-block">
    <p class="ai-eyebrow">THIS WEEK</p>
    <ul class="ai-pick-mini-list">
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
  <section class="ai-week-block">
    <p class="ai-eyebrow">LAST WEEK</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260524/">
    <span class="ai-pick-date">2026-05-24</span>
    <span class="ai-pick-title-mini">colbymchenry/codegraph — Pre-indexed code knowledge graph fo…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260523/">
    <span class="ai-pick-date">2026-05-23</span>
    <span class="ai-pick-title-mini">colbymchenry/codegraph — 사전 인덱싱된 코드 지식 그래프 MCP</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260522/">
    <span class="ai-pick-date">2026-05-22</span>
    <span class="ai-pick-title-mini">Giving Agents Computers — Ivan Burazin, Daytona</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260521/">
    <span class="ai-pick-date">2026-05-21</span>
    <span class="ai-pick-title-mini">colbymchenry/codegraph — Pre-indexed code knowledge graph fo…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260520/">
    <span class="ai-pick-date">2026-05-20</span>
    <span class="ai-pick-title-mini">New in Claude Managed Agents: self-hosted sandboxes and MCP …</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260519/">
    <span class="ai-pick-date">2026-05-19</span>
    <span class="ai-pick-title-mini">Anthropic acquires Stainless</span>
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
