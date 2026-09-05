---
title: "AI News Digest"
toc: false
---

<div class="ai-home-grid">

<div class="ai-home-main">

<section class="ai-home-hero">
  <p class="ai-eyebrow">AI NEWS · WEEKLY DIGEST</p>
  <h1 class="ai-headline">모델 공급이 정치로 끊긴 주 — 코딩 툴의 생존 요건이 된 '모델 복원력'</h1>
  <p class="ai-home-deck">단일 벤더 SDK를 하드코딩한 제품은 계약 한 줄로 멈춘다는 게 이번 주 실증됐고, 대안은 라우팅·페일오버 계층이다</p>
  <p class="ai-meta">2026-08-31 · 주간 요약 (매주 월요일) · 일간 픽 매일 갱신</p>
  <div class="ai-cta-row">
    <a class="ai-cta" href="https://altjs4510.github.io/ai_news_blog/posts/20260831/">
      <span class="ai-cta-label">이번 주 전체 보기</span>
      <span class="ai-cta-arrow" aria-hidden="true">→</span>
    </a>
  </div>
</section>

<aside class="ai-spotlight">
  <p class="ai-eyebrow ai-spotlight-eyebrow">✦ TODAY'S PICK</p>
  <a class="ai-spotlight-title" href="https://github.com/tashfeenahmed/freellmapi" target="_blank" rel="noopener">tashfeenahmed/freellmapi — 34개 프로바이더·635개 모델 엔드포인트를 단일 /v1 뒤에 두는 스마트 라우팅·자동 페일오버 게이트웨이<span class="ai-spotlight-arrow">↗</span></a>
  <p class="ai-spotlight-why">OpenAI가 SpaceX에 인수된 Cursor에 모델 공급을 끊은 사건(https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex)과 정확히 맞물려 이번 주 22,605스타로 급부상한 항목으로, hardmaru가 말한 '모델 복원력'(https://bsky.app/profile/hardmaru.bsky.social/post/3mu7oaexpsc2p)을 실제 코드 구조로 내린 레퍼런스입니다 — 여러 프로바이더를 OpenAI 호환 단일 엔드포인트 뒤에 두고 장애·차단 시 자동 페일오버하는 설계라, DCSAI가 Anthropic SDK를 agent loop에 직통합해 두고 HTTP chunked streaming까지 벤더 SDK에 얹은 구조의 단일 의존 지점을 정면으로 건드립니다.</p>
  <p class="ai-spotlight-app"><span class="ai-spotlight-app-label">접목 →</span> DCSAI agent loop와 MCP host server 사이에 벤더 SDK 호출을 감싸는 얇은 라우팅 레이어를 두는 PoC — 현재 `make_client` 격의 단일 진입점을 프로바이더 추상화로 바꾸고, tool use·HITL 분기 중 모델 호출이 실패했을 때 스트리밍 세션을 끊지 않고 대체 백엔드로 넘기는 페일오버 경로를 설계 검증용으로 참고할 수 있습니다.</p>
  <p class="ai-spotlight-cta"><a class="ai-spotlight-detail" href="https://altjs4510.github.io/ai_news_blog/knowledge/20260830/">자세히 보기 <span class="ai-spotlight-detail-arrow" aria-hidden="true">→</span></a></p>
</aside>

<section class="ai-additional">
  <p class="ai-eyebrow">ALSO WORTH READING · 꼭 읽어보세요</p>
  <div class="ai-pick-list">
  <article class="ai-pick">
  <a class="ai-pick-title" href="https://claude.com/blog/cowork-built-in-browser" target="_blank" rel="noopener">Claude gets its own browser in Cowork<span class="ai-pick-arrow">↗</span></a>
  <p class="ai-pick-summary">Anthropic이 Cowork에 브라우저를 내장해 에이전트의 작업 표면을 확장 프로그램이 아니라 제품 안쪽으로 끌어들인 공지로, 로그인 세션·사내 SaaS처럼 API 없는 업무까지 실행 경계 안에 들어옵니다. DCSAI가 자체 구현 중인 MCP host server의 tool 실행 경계와 agent loop HITL 분기(어느 행위를 사람이 승인할 것인가)를 다시 그어야 하는 이유를 벤더 1차 자료로 확인할 수 있습니다.</p>
</article>
  <article class="ai-pick">
  <a class="ai-pick-title" href="http://arxiv.org/abs/2608.27454v1" target="_blank" rel="noopener">WikiSkill: Compiling Agent Experience into Persistent Knowledge for Skill Evolution<span class="ai-pick-arrow">↗</span></a>
  <p class="ai-pick-summary">에이전트 실행 경험을 일회성 로그가 아니라 다음 실행이 물려받는 지속 지식으로 컴파일해 스킬로 진화시키는 방법을 다룹니다. 같은 주 archify·scientific-agent-skills·claude-plugins-community가 동시에 트렌딩에 오른 배경을 설명하는 이론 축이라, Team Agent의 Activity Log → Observer 피드백루프(L1)가 축적한 기록을 어떤 형태로 재사용 자산화할지 설계할 때 함께 읽을 만합니다.</p>
</article>
  </div>
</section>

<nav class="ai-chips"><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EB%AA%A8%EB%8D%B8-%EB%B3%B5%EC%9B%90%EB%A0%A5/">#모델 복원력</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EB%A9%80%ED%8B%B0-%ED%94%84%EB%A1%9C%EB%B0%94%EC%9D%B4%EB%8D%94-%EB%9D%BC%EC%9A%B0%ED%8C%85/">#멀티 프로바이더 라우팅</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EB%B2%A4%EB%8D%94-%EC%A2%85%EC%86%8D-%EB%A6%AC%EC%8A%A4%ED%81%AC/">#벤더 종속 리스크</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8-%EC%8A%A4%ED%82%AC-%EC%B6%95%EC%A0%81/">#에이전트 스킬 축적</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8-%EB%B8%8C%EB%9D%BC%EC%9A%B0%EC%A0%80/">#에이전트 브라우저</a></nav>

### 전체 요약

이번 주 AI 업계의 가장 큰 사건은 **인프라·계약 관계의 재편**이다. **OpenAI**가 **SpaceX**에 인수된 **Cursor**에 대한 모델 공급 계약을 종료하기로 결정하면서, 코딩 툴이 특정 프론티어 모델에 종속됐을 때의 취약성이 그대로 드러났다. 동시에 **Sony Music·Warner**가 **Anthropic**을 상대로 대규모 저작권 소송을 제기하며 학습 데이터 정당성 문제가 다시 법정으로 향했다.

기술 축에서는 **에이전트의 '기억'과 '스킬'** 이 공통 주제로 떠올랐다. **Anthropic**은 **Cowork**에 자체 브라우저를 내장했고, GitHub 트렌딩과 arxiv 양쪽에서 에이전트 경험을 재사용 가능한 스킬로 압축하는 흐름(**WikiSkill**, **archify**, **scientific-agent-skills**)이 동시에 관측된다.

한편 **오픈 웨이트 진영**은 **Tencent**의 **Hy4**(770B 총 파라미터, 49B 활성, 1M 컨텍스트) 공개로 규모 경쟁을 이어갔다. 반대편에서는 **Emily Bender**를 비롯한 AI 회의론 진영의 목소리와 **"AI is killing my brain"** 류의 실사용자 피로감이 같은 주에 나란히 확산됐다.

---

### 주제별 분석

#### 1. 모델 공급 계약의 정치화 — 툴이 모델에 종속되면 벌어지는 일

**핵심 인사이트**

**OpenAI**는 **Cursor**가 **SpaceX**에 인수된 것을 이유로 모델 공급 계약을 종료한다고 공식 발표했다. 기술적 결함이나 정책 위반이 아니라 **소유 구조 변경**이 공급 중단 사유가 됐다는 점이 핵심이다.

**hardmaru**는 이 사건을 두고 "인기 코딩 툴이 프론티어 모델 접근권을 잃는 걸 보면 **모델 복원력(model resiliency)** 이 왜 중요한지 알 수 있다"고 짚었다. 앞으로의 제품은 여러 모델이 동시에 죽어도 라우팅으로 계속 작동해야 한다는 주장이다.

이 흐름은 **freellmapi** 같은 프로젝트가 이번 주 22,605 스타를 기록한 배경과 정확히 맞물린다. **34개 프로바이더 · 635개 모델 엔드포인트를 단일 `/v1` 뒤에 두고 스마트 라우팅과 자동 페일오버**를 제공한다는 설계는, 더 이상 최적화가 아니라 생존 요건에 가깝다.

**관련 자료**

- [Our decision on Cursor following its acquisition by SpaceX](https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex)
- [hardmaru — 모델 복원력에 대하여](https://bsky.app/profile/hardmaru.bsky.social/post/3mu7oaexpsc2p)
- [tashfeenahmed/freellmapi](https://github.com/tashfeenahmed/freellmapi)
- [cursor/plugins](https://github.com/cursor/plugins)

#### 2. 에이전트 스킬 — 경험을 재사용 가능한 자산으로 압축하기

**핵심 인사이트**

arxiv의 **WikiSkill**은 에이전트가 수행한 경험을 **지속 가능한 지식(persistent knowledge)** 으로 컴파일해 스킬로 진화시키는 방법을 제안한다. 일회성 실행 로그가 아니라 다음 실행이 물려받을 수 있는 형태로 축적하는 것이 요지다.

같은 문제의식이 GitHub에서는 이미 제품으로 나타났다. **archify**(이번 주 14,875 스타)는 아키텍처·시퀀스·데이터 플로우 다이어그램을 검증 가능한 자체 완결형 HTML로 뽑는 스킬이고, **scientific-agent-skills**는 19만 명 과학자가 쓰는 스킬 라이브러리를 표방한다.

**Anthropic** 역시 공식·커뮤니티 플러그인 마켓플레이스를 동시에 운영하며 이 레이어를 제도화하고 있다. **RedEvoAgent**가 레드팀 에이전트에 같은 '경험 기반 스킬 진화'를 적용한 걸 보면, 스킬 축적은 특정 도메인이 아니라 에이전트 아키텍처의 기본 패턴으로 굳어지는 중이다.

**관련 자료**

- [WikiSkill: Compiling Agent Experience into Persistent Knowledge for Skill Evolution](http://arxiv.org/abs/2608.27454v1)
- [RedEvoAgent: Automatic Red-Teaming Agent with Experience-Driven Skill Evolution](http://arxiv.org/abs/2608.27439v1)
- [tt-a1i/archify](https://github.com/tt-a1i/archify)
- [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- [anthropics/claude-plugins-community](https://github.com/anthropics/claude-plugins-community)

#### 3. 코딩 에이전트의 학습 효율 — 데이터를 늘리는 시대의 종료

**핵심 인사이트**

**SWE-Prime**의 제목 자체가 이번 흐름을 요약한다 — **"더 적은 궤적(trajectory), 더 나은 성능"**. 지금까지는 대규모 에이전트 궤적 데이터셋을 구축해 SFT를 돌리는 것이 정석이었지만, 이 전제가 깨지고 있다.

**TTPO(Test-Time Policy Optimization)** 와 **CritICL**은 같은 방향에서 다른 답을 낸다. 학습 단계에서 데이터를 밀어넣는 대신 **추론 시점**에 정책을 최적화하거나, 작은 모델의 실패 모드로부터 약-강 일반화를 유도하는 방식이다.

평가 쪽도 정적 벤치마크에서 벗어나는 중이다. **MCR-Bench**는 코드 리뷰를 개발자와 리뷰어 사이의 **반복적 상호작용**으로 모델링해, 단일 턴 정답 채점으로는 잡히지 않던 실제 개발 프로세스를 벤치마크에 넣었다.

**관련 자료**

- [SWE-Prime: Fewer Trajectories, Better Performance](http://arxiv.org/abs/2608.27449v1)
- [TTPO: Test-Time Policy Optimization](http://arxiv.org/abs/2608.27448v1)
- [CritICL: Inference-Time Weak-to-Strong Generalization from Small Language Model Failure Modes](http://arxiv.org/abs/2608.27455v1)
- [From Static to Dynamic: Benchmarking Real-World Code Review with MCR-Bench](http://arxiv.org/abs/2608.27442v1)
- [Advancing price-performance for developers with GPT‑5.6 in Kiro](https://openai.com/index/gpt-5-6-in-kiro)

#### 4. AI의 법적·윤리적 청구서가 동시에 도착했다

**핵심 인사이트**

**Sony Music**과 **Warner**가 **Anthropic**을 상대로 "**뻔뻔한 지식재산 절도 캠페인**"이라 표현한 소송을 제기했다. 이번 건은 범위가 넓고 특히 **불법 복제(piracy)** 자체를 정면으로 겨냥한다는 점에서 기존 학습 데이터 소송과 결이 다르다.

보안 쪽에서도 청구서가 왔다. **OpenAI**는 **Hugging Face 보안 침해 사건**의 조사 결과를 공개하며 모델 보안·모니터링·정렬 강화 조치를 발표했는데, 모델 유통 허브가 공급망 공격 지점이 됐다는 사실이 확인된 셈이다.

담론 층위에서는 **Emily Bender**가 "불편한 중간 지대에서 벗어나 확고한 AI 저항으로"라는 뉴스레터를 냈고, 다른 이용자는 **"절도·노동 착취·환경 파괴 위에 세운 소프트웨어를 윤리적으로 쓰라고 가르치는 AI 리터러시"** 를 비꼬았다. 법정·보안·여론 세 축의 압력이 같은 주에 겹친 것이 이번 주의 특징이다.

**관련 자료**

- [Sony Music, Warner sue Anthropic, alleging a "brazen campaign" of intellectual property theft](https://techcrunch.com/2026/08/29/sony-music-warner-sue-anthropic-alleging-a-brazen-campaign-of-intellectual-property-theft/)
- [The Hugging Face incident and the road ahead](https://openai.com/index/hugging-face-incident-and-the-road-ahead)
- [Emily Bender — MAIHT3k 뉴스레터: 확고한 AI 저항으로](https://bsky.app/profile/emilymbender.bsky.social/post/3mu7wwqonqs2a)
- [AI 리터러시에 대한 비판](https://bsky.app/profile/elizabethwithaz.bsky.social/post/3mucrzl33f22g)

#### 5. 로컬 우선(local-first) — 에이전트를 내 기계로 되돌리기

**핵심 인사이트**

**Apache Maka**는 모델 메시지·툴 호출·툴 결과·권한 결정·종료 이벤트를 전부 **추가 전용 로그(append-only log)** 로 기록하는 로컬 우선 에이전트 워크스페이스다. 감사 가능성을 아키텍처 차원에서 보장하는 접근으로, arxiv의 **Persona-Execution Separation** 논문이 말하는 "페르소나는 자유롭게 진화하되 실행은 추적 가능해야 한다"는 요구와 정확히 같은 문제를 푼다.

Product Hunt에서는 **oMLX**가 **Mac LLM 서버로 에이전트 대기 시간을 90초에서 5초로 줄인다**고 내세웠다. 로컬 실행의 명분이 프라이버시에서 **응답 속도**로 옮겨간 것이 눈에 띈다.

**ai-job-search**(이번 주 5,145 스타) 역시 "내 기계에서 도는 구직 활동"을 표방하며 **Claude Code** 위에 구축됐다. 클라우드 API 종속 리스크가 현실화된 주에 로컬 우선 프로젝트들이 나란히 트렌딩에 오른 건 우연으로 보기 어렵다.

**관련 자료**

- [apache/maka](https://github.com/apache/maka)
- [Persona-Execution Separation: An Architecture Pattern for Evolving LLM Agents under Execution Audit](http://arxiv.org/abs/2608.27427v1)
- [oMLX — Mac LLM server](https://www.producthunt.com/products/omlx)
- [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)
- [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi)

---

### 주목할 만한 개별 발견

#### Tencent Hy4 — 1M 컨텍스트 오픈 웨이트, 다만 텍스트 전용

- 출처: [Introducing Hy4 Preview](https://simonwillison.net/2026/Aug/29/hy4/)
- 출처: [Hy4 preview on Product Hunt](https://www.producthunt.com/products/hunyuan-a13b)

**770B 총 파라미터 중 49B만 활성**되는 MoE 구조에 **100만 토큰 컨텍스트**, Hugging Face 기준 **1.56TB** 규모다. 비전 없이 텍스트 입력만 지원한다는 제약이 명시돼 있어, 멀티모달 경쟁이 아니라 **장기 지평 작업(long-horizon work)** 을 겨냥한 포지셔닝임이 분명하다.

활성 파라미터가 총량의 6% 수준이라는 점은 추론 비용 측면에서 실용적 배포 가능성을 시사한다. 다만 1.56TB 다운로드를 감당할 인프라가 전제되므로, 실질적으로는 서빙 사업자용 모델에 가깝다.

#### Anthropic이 Claude에 브라우저를 직접 붙였다

- 출처: [Claude gets its own browser in Cowork](https://claude.com/blog/cowork-built-in-browser)

**Cowork**에 브라우저가 내장되면서 에이전트가 외부 도구를 경유하지 않고 웹을 직접 다루게 됐다. 검색 API나 스크래핑 래퍼를 붙이던 기존 패턴이 플랫폼 기본 기능으로 흡수되는 흐름이다.

같은 주에 **"Anthropic 직원들은 Claude Tag을 어떻게 쓰는가"** 글도 함께 나왔다. 자사 도구의 내부 사용 패턴을 공개하는 건 기능 소개보다 **워크플로 표준을 제시하려는 의도**로 읽힌다.

#### 데이터센터 전력이 AI 뉴스의 고정 항목이 됐다

- 출처: [Musk's faster path to more gas turbines comes with pollution problem](https://techcrunch.com/2026/08/30/musks-faster-path-to-more-gas-turbines-comes-with-pollution-problem/)
- 출처: [Caterpillar is bringing to AI deployment what it learned from automating mining](https://techcrunch.com/2026/08/30/caterpillar-is-bringing-to-ai-deployment-what-it-learned-from-automating-mining/)

**Elon Musk**는 **SpaceX**의 비공개 주조 공장에서 터빈 블레이드를 직접 만들어 가스 발전을 **18개월 앞당기겠다**고 밝혔다. 모델 경쟁이 아니라 **발전 설비 리드타임 경쟁**이 병목이 됐다는 신호다.

**Caterpillar**는 원격 광산 자동화에서 수십 년간 쌓은 경험을 AI 배포에 적용하고 있다. AI 인프라의 실질적 노하우가 소프트웨어 회사가 아니라 **중장비·에너지 업계**에서 나오는 국면이다.

#### "AI가 내 뇌를 망치고 있다" — Hacker News의 피로 신호

- 출처: [Tell HN: Man, AI is killing my brain](https://news.ycombinator.com/item?id=49468252)

댓글 28개에 54포인트로 폭발적 반응은 아니지만, **Tell HN** 형식으로 개발자가 직접 인지적 피로를 호소했다는 점이 중요하다. 생산성 지표로 잡히지 않는 사용자 비용이 축적되고 있다는 신호다.

**Simon Willison**의 **LLM 클리셰 하이라이터가 38개 패턴까지 늘었다**는 소식도 같은 결이다. AI 산출물의 특징적 문체를 탐지하는 도구가 커뮤니티에서 491 좋아요를 받는 건, 생성물에 대한 **감별 욕구**가 그만큼 커졌다는 뜻이다.

</div>

<aside class="ai-home-aside">
  <section class="ai-week-block ai-trend-block">
    <p class="ai-eyebrow">🔥 X 화제 키워드</p>
    <ul class="ai-trend-chips">
      <li><a class="ai-trend-chip ai-trend-chip--new" href="https://x.com/adamdotnew/status/2096053889141489669" target="_blank" rel="noopener"><span class="ai-trend-chip-badge">NEW</span><span class="ai-trend-chip-term">agentic CAD</span></a></li>
      <li><a class="ai-trend-chip ai-trend-chip--rising" href="https://x.com/adamdotnew/status/2096053889141489669" target="_blank" rel="noopener"><span class="ai-trend-chip-badge">↑</span><span class="ai-trend-chip-term">GPT-6 Astra</span></a></li>
    </ul>
  </section>
  <section class="ai-week-block">
    <p class="ai-eyebrow">THIS WEEK</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260906/">
    <span class="ai-pick-date">2026-09-06</span>
    <span class="ai-pick-title-mini">DietrichGebert/ponytail — 에이전트를 '방에서 가장 게으른 시니어 개발자'처럼 생각하게 …</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260905/">
    <span class="ai-pick-date">2026-09-05</span>
    <span class="ai-pick-title-mini">magnitudedev/magnitude — 하드웨어에 맞는 최적 로컬 모델을 띄워 이미 쓰는 에이전트에 그…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260904/">
    <span class="ai-pick-date">2026-09-04</span>
    <span class="ai-pick-title-mini">HarnessDev: Can LLMs Create and Evolve Their Own Agent Harne…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260903/">
    <span class="ai-pick-date">2026-09-03</span>
    <span class="ai-pick-title-mini">pacifio/atlas — 여러 코딩 에이전트의 변경을 한곳에서 추적·질의하는 '에이전트용 소스 컨트롤' …</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260902/">
    <span class="ai-pick-date">2026-09-02</span>
    <span class="ai-pick-title-mini">AIR raises $50M to help companies vet the skills and add-ons…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260901/">
    <span class="ai-pick-date">2026-09-01</span>
    <span class="ai-pick-title-mini">affaan-m/ECC — 스킬·본능·메모리·보안을 묶은 에이전트 하네스 성능 최적화 시스템</span>
  </a>
</li>
    </ul>
  </section>
  <section class="ai-week-block">
    <p class="ai-eyebrow">LAST WEEK</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260830/">
    <span class="ai-pick-date">2026-08-30</span>
    <span class="ai-pick-title-mini">[AINews] OpenAI shuts off Cursor — 프론티어 모델 공급 차단과 '모델 복원력(mo…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260829/">
    <span class="ai-pick-date">2026-08-29</span>
    <span class="ai-pick-title-mini">cursor/plugins — 플러그인 명세(specification)와 공식 플러그인을 함께 공개</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260828/">
    <span class="ai-pick-date">2026-08-28</span>
    <span class="ai-pick-title-mini">Google ADK for Python v2.8.0 — RemoteA2aAgent 네이티브 task 모드 +…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260827/">
    <span class="ai-pick-date">2026-08-27</span>
    <span class="ai-pick-title-mini">Claude in Chrome is generally available</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260826/">
    <span class="ai-pick-date">2026-08-26</span>
    <span class="ai-pick-title-mini">apache/maka — 도구 호출·권한 결정·종료 이벤트를 append-only 로그로 남기는 로컬 우선 …</span>
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
