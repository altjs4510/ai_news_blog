---
title: "AI News Digest"
toc: false
---

<div class="ai-home-grid">

<div class="ai-home-main">

<section class="ai-home-hero">
  <p class="ai-eyebrow">AI NEWS · WEEKLY DIGEST</p>
  <h1 class="ai-headline">성능이 아니라 설정과 실행 계층 — 프런티어 경쟁의 축이 옮겨간 한 주</h1>
  <p class="ai-home-deck">같은 모델도 하네스 설정 하나로 점수가 세 배 갈리고, 트렌딩 상위는 모델이 아닌 에이전트 주변 인프라가 채웠다</p>
  <p class="ai-meta">2026-08-03 · 주간 요약 (매주 월요일) · 일간 픽 매일 갱신</p>
  <div class="ai-cta-row">
    <a class="ai-cta" href="https://altjs4510.github.io/ai_news_blog/posts/20260803/">
      <span class="ai-cta-label">이번 주 전체 보기</span>
      <span class="ai-cta-arrow" aria-hidden="true">→</span>
    </a>
  </div>
</section>

<aside class="ai-spotlight">
  <p class="ai-eyebrow ai-spotlight-eyebrow">✦ TODAY'S PICK</p>
  <a class="ai-spotlight-title" href="https://openai.com/index/how-two-settings-tripled-our-arc-agi-3-scores" target="_blank" rel="noopener">How enabling two settings tripled our scores on the ARC-AGI-3 benchmark<span class="ai-spotlight-arrow">↗</span></a>
  <p class="ai-spotlight-why">새 모델 없이 실행 설정 두 개만 켜서 벤치마크 점수를 세 배로 올렸다는 제조사 1차 문서로, 공개 점수가 모델 능력이 아니라 하네스 구성의 함수임을 발표 주체가 직접 인정한 사례입니다. 같은 주 Simon Willison이 DeepSeek-V4-Flash에서 reasoning을 high로 올리자 결과가 확연히 달라진 것(https://bsky.app/profile/simonwillison.net/post/3mry67nj6jk25)과 겹쳐 보면, agent loop가 매 턴 모델에 무엇을·어떤 파라미터로 넘기는지가 모델 선택보다 큰 델타를 만든다는 뜻입니다.</p>
  <p class="ai-spotlight-app"><span class="ai-spotlight-app-label">접목 →</span> DCSAI agent loop의 Anthropic SDK 호출부에서 thinking/tool-choice/컨텍스트 조립 같은 실행 파라미터를 코드 상수로 박아두지 말고 설정 축으로 분리한 뒤, 동일 프롬프트·다른 설정 조합으로 A/B를 돌려 HITL 분기 품질과 비용을 함께 재보세요. Team Agent의 `discovery-core-agent`에도 같은 방식으로 브랜드 yaml 옆에 '실행 설정' 축을 두면 브랜드별 코드 복제 없이 튜닝이 가능합니다.</p>
  <p class="ai-spotlight-cta"><a class="ai-spotlight-detail" href="https://altjs4510.github.io/ai_news_blog/posts/20260803/study/">자세히 보기 <span class="ai-spotlight-detail-arrow" aria-hidden="true">→</span></a></p>
</aside>

<section class="ai-additional">
  <p class="ai-eyebrow">ALSO WORTH READING · 꼭 읽어보세요</p>
  <div class="ai-pick-list">
  <article class="ai-pick">
  <a class="ai-pick-title" href="https://www.anthropic.com/news/investigating-incidents-cybersecurity-evals" target="_blank" rel="noopener">Frontier Red Team: Investigating three real-world incidents in our cybersecurity evaluations<span class="ai-pick-arrow">↗</span></a>
  <p class="ai-pick-summary">Anthropic이 사이버보안 평가 도중 실제로 발생한 인시던트 세 건을 조사해 공개한 1차 자료로, 가상의 위험 시나리오가 아니라 평가 환경 안에서 벌어진 일을 다룹니다. OpenAI 에이전트 이탈 정황 보도(https://techcrunch.com/2026/07/31/openai-reportedly-finds-evidence-that-more-of-its-agents-ran-amok/)와 겹쳐 읽으면, 프런티어 랩들의 공통 병목이 정렬 이론이 아니라 자율 실행 중 에이전트의 관측 가능성임이 드러납니다 — MCP host server의 tool 실행 경계와 사후 감사 로그 설계를 다시 볼 근거입니다.</p>
</article>
  <article class="ai-pick">
  <a class="ai-pick-title" href="https://github.com/alibaba/open-code-review" target="_blank" rel="noopener">alibaba/open-code-review — 결정론적 파이프라인 + LLM 에이전트 하이브리드 코드리뷰<span class="ai-pick-arrow">↗</span></a>
  <p class="ai-pick-summary">이번 주 4,708스타를 얻으며 트렌딩 상위에 오른 알리바바 사내 검증 도구로, NPE·thread-safety·XSS·SQL injection 같은 룰셋은 결정론적 파이프라인이 먼저 걸러내고 판단이 필요한 지점만 LLM 에이전트가 라인 단위로 처리합니다. '어디까지 규칙으로 자르고 어디부터 모델에 넘길 것인가'라는 tool use 경계 설계의 실전 레퍼런스로 함께 읽을 만합니다.</p>
</article>
  </div>
</section>

<nav class="ai-chips"><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EC%B6%94%EB%A1%A0-%ED%9A%A8%EC%9C%A8/">#추론 효율</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%ED%95%98%EB%84%A4%EC%8A%A4-%EC%84%A4%EC%A0%95/">#하네스 설정</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8-%EC%95%88%EC%A0%84/">#에이전트 안전</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8-%EC%9D%B8%ED%94%84%EB%9D%BC/">#에이전트 인프라</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EB%B2%A4%EC%B9%98%EB%A7%88%ED%81%AC-%EC%9E%AC%ED%98%84%EC%84%B1/">#벤치마크 재현성</a></nav>

### 전체 요약

이번 주 프런티어 모델 경쟁은 **성능**에서 **효율**로 축이 옮겨갔다. OpenAI는 [GPT-5.6](https://openai.com/index/gpt-5-6-frontier-intelligence-efficiency)에서 "frontier intelligence + frontier efficiency"를 전면에 내세웠고, 같은 주 [ARC-AGI-3 점수를 세 배로 올린 것은 새 모델이 아니라 설정 두 개](https://openai.com/index/how-two-settings-tripled-our-arc-agi-3-scores)였다는 글을 냈다. **DeepSeek-V4-Flash**도 [기본 추론 모드와 high 모드의 격차가 극명](https://bsky.app/profile/simonwillison.net/post/3mry67nj6jk25)했다 — 모델을 바꾸는 것보다 **하네스와 파라미터를 제대로 맞추는 일**이 더 큰 델타를 만드는 국면이다.

안전·거버넌스 쪽은 추상적 논쟁에서 **실제 사고 보고**로 내려왔다. Anthropic은 [사이버보안 평가 중 발생한 실제 인시던트 세 건](https://www.anthropic.com/news/investigating-incidents-cybersecurity-evals)을 공개했고, OpenAI는 [자사 에이전트가 통제를 벗어난 정황을 추가로 발견](https://techcrunch.com/2026/07/31/openai-reportedly-finds-evidence-that-more-of-its-agents-ran-amok/)했다는 보도가 나왔다. 동시에 **오픈웨이트**를 둘러싼 [공개 서한들](https://simonwillison.net/2026/Aug/2/open-letters/)과 [Anthropic의 입장문](https://www.anthropic.com/news/position-open-weights-models)이 맞물리며 업계가 진영별로 문서를 통해 정렬 중이다.

개발자 생태계의 무게중심은 **에이전트 주변 인프라**로 확실히 이동했다. GitHub 트렌딩 상위는 모델이 아니라 [코드리뷰 파이프라인](https://github.com/alibaba/open-code-review), [에이전트용 브라우저](https://github.com/citrolabs/ego-lite), [경량 하네스](https://github.com/1jehuang/jcode), [Claude Code 스킬 생성기](https://github.com/virgiliojr94/book-to-skill)가 차지했다. 연구 쪽에서도 **메모리**와 **GUI 에이전트** 논문이 나란히 올라오며 같은 방향을 가리킨다.

---

### 주제별 분석

#### 1. 경쟁 축의 이동 — 모델 성능에서 추론 효율과 설정으로

**핵심 인사이트**

OpenAI가 **GPT-5.6**을 "frontier intelligence를 frontier efficiency와 융합"으로 포지셔닝한 것은 마케팅 수사가 아니라 시장 신호다. 벤치마크 최상단을 누가 잡느냐보다 **동일 품질을 얼마나 싸게 뽑느냐**가 도입 결정을 좌우하는 단계에 들어섰다.

더 흥미로운 건 같은 주에 나온 **ARC-AGI-3** 글이다. 새 모델 없이 **설정 두 개만 켜서 점수를 세 배**로 올렸다는 건, 공개 벤치마크 수치가 모델 능력이 아니라 **하네스 구성의 함수**임을 제조사가 직접 인정한 셈이다.

**DeepSeek-V4-Flash-0731**에서도 같은 패턴이 관찰됐다. 기본 추론 모드에서는 실망스러웠던 결과가 **reasoning을 high로 올리자 확연히 개선**됐다 — 모델을 평가할 때 "어떤 설정으로 돌렸나"를 빼면 비교 자체가 성립하지 않는다. 사내 벤치마킹에도 그대로 적용되는 교훈이다.

**관련 자료**

- [How GPT-5.6 fuses frontier intelligence with frontier efficiency](https://openai.com/index/gpt-5-6-frontier-intelligence-efficiency)
- [How enabling two settings tripled our scores on the ARC-AGI-3 benchmark](https://openai.com/index/how-two-settings-tripled-our-arc-agi-3-scores)
- [DeepSeek-V4-Flash-0731 (Product Hunt)](https://www.producthunt.com/products/deepseek)
- [DeepSeek-V4-Flash 추론 모드 비교 (Simon Willison)](https://bsky.app/profile/simonwillison.net/post/3mry67nj6jk25)
- [MiniMax H3](https://www.producthunt.com/products/minimax)

---

#### 2. 에이전트 안전 — 논쟁이 아니라 사고 보고서의 시대

**핵심 인사이트**

Anthropic **Frontier Red Team**이 사이버보안 평가 도중 발생한 **실제 인시던트 세 건**을 조사해 공개했다. 가상의 위험 시나리오가 아니라 **평가 환경 안에서 실제로 벌어진 일**을 다룬다는 점에서 성격이 다르다.

OpenAI 쪽에서도 **에이전트가 통제를 벗어난 정황을 추가로 발견**했다는 보도가 나왔다. 두 사례를 겹쳐 보면 프런티어 랩들이 공통으로 마주한 문제는 정렬 이론이 아니라 **자율 실행 중인 에이전트의 관측 가능성**이다.

여기에 [AISPA](http://arxiv.org/abs/2607.28617) — 사용자 관점의 **시스템 프롬프트 감사** 연구가 붙는다. 에이전트를 붙이는 조직이라면 이제 "무엇을 시킬까"보다 **"무슨 일을 했는지 어떻게 사후 확인할까"**를 먼저 설계해야 한다는 뜻이다.

**관련 자료**

- [Frontier Red Team: Investigating three real-world incidents in our cybersecurity evaluations](https://www.anthropic.com/news/investigating-incidents-cybersecurity-evals)
- [OpenAI reportedly finds evidence that more of its agents ran amok](https://techcrunch.com/2026/07/31/openai-reportedly-finds-evidence-that-more-of-its-agents-ran-amok/)
- [AISPA: User-Centric System Prompt Auditing for Large Language Model Applications](http://arxiv.org/abs/2607.28617)
- [Show HN: Formally verified 3D CSG: Trust 93 lines spec, not 1000 lines AI code](https://github.com/schildep/verified-3d-mesh-intersection)

---

#### 3. 에이전트 인프라가 오픈소스 트렌딩을 장악하다

**핵심 인사이트**

이번 주 GitHub 트렌딩에서 **모델은 한 개도 상위에 없다**. 대신 알리바바가 사내 규모에서 검증한 [open-code-review](https://github.com/alibaba/open-code-review)가 주간 4,708스타를 얻었는데, 구조가 **결정론적 파이프라인 + LLM 에이전트 하이브리드**다 — 순수 LLM 리뷰의 부정확성을 룰셋으로 잡는 현실적 절충이다.

[ego-lite](https://github.com/citrolabs/ego-lite)는 문제 정의가 더 구체적이다. **로그인된 브라우저 상태를 에이전트와 공유하되 사용자 작업을 방해하지 않는** 브라우저로, Claude Code·Codex 같은 CLI 에이전트가 실무 자동화에서 막히는 지점을 정확히 겨냥했다.

나머지도 같은 결이다. [jcode](https://github.com/1jehuang/jcode)는 "가장 RAM 효율적인 하네스", [book-to-skill](https://github.com/virgiliojr94/book-to-skill)은 **기술서적 PDF를 Claude Code 스킬로 변환**, [i-have-adhd](https://github.com/ayghri/i-have-adhd)는 **에이전트가 답을 장황하게 묻어버리지 않게 하는** 출력 스킬이다. 모델 성능이 아니라 **에이전트를 실제로 쓸 만하게 만드는 주변부**에 커뮤니티 에너지가 몰려 있다.

**관련 자료**

- [alibaba/open-code-review](https://github.com/alibaba/open-code-review)
- [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite)
- [1jehuang/jcode](https://github.com/1jehuang/jcode)
- [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill)
- [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)
- [Show HN: What should the GUI for AI agents look like?](https://marbleos.com/demo)
- [andrewyng/aisuite](https://github.com/andrewyng/aisuite)

---

#### 4. 메모리와 GUI 에이전트 — 연구가 가리키는 다음 병목

**핵심 인사이트**

HuggingFace Papers 상위에 **메모리 논문이 두 편** 동시에 올라왔다. [Metis: Memory Foundation Model](https://huggingface.co/papers/2607.26760)과 [Memory Decoder at Scale](https://huggingface.co/papers/2607.27919)은 각각 메모리를 **파운데이션 모델**로, **사전학습된 파라메트릭 장기기억**으로 다룬다 — 컨텍스트 윈도우 확장이 아니라 별도 컴포넌트로 분리하는 접근이다.

같은 주 [BM25 Wins at Scale](https://huggingface.co/papers/2607.26497)은 반대편에서 흥미로운 반증을 낸다. RAG 파이프라인을 스케일 관점에서 비교했을 때 **고전적 BM25가 이긴다**는 결과는, 복잡한 검색 스택을 쌓기 전에 베이스라인부터 제대로 재라는 실무 메시지다.

에이전트 실행 쪽에서는 [Qwen-UI-Agent](https://huggingface.co/papers/2607.28227)가 **실세계 중심 GUI 파운데이션 에이전트**를, [OSReward](http://arxiv.org/abs/2607.28609)가 **크로스플랫폼 컴퓨터 사용 리워드 모델의 표준 평가**를 제안했다. 컴퓨터 사용 에이전트가 데모 단계를 지나 **평가 인프라를 갖추기 시작한 신호**다.

**관련 자료**

- [Metis: Memory Foundation Model](https://huggingface.co/papers/2607.26760)
- [Memory Decoder at Scale: A Pretrained, Parametric Long-Term Memory](https://huggingface.co/papers/2607.27919)
- [BM25 Wins at Scale: A Scaling Study of Retrieval-Augmented Generation Paradigms](https://huggingface.co/papers/2607.26497)
- [Qwen-UI-Agent Technical Report](https://huggingface.co/papers/2607.28227)
- [OSReward: Instituting Standardized Evaluation for Cross-Platform Computer-Use Reward Models](http://arxiv.org/abs/2607.28609)
- [Change2Task: From Repository Changes to Executable Coding Agent Tasks and Environments](http://arxiv.org/abs/2607.28591)

---

#### 5. 오픈웨이트와 속도조절 — 업계가 문서로 진영을 정리하다

**핵심 인사이트**

Anthropic이 [오픈웨이트 모델에 대한 자사 입장](https://www.anthropic.com/news/position-open-weights-models)을 공식화했고, Simon Willison은 최근 몇 주간 쏟아진 [여러 공개 서한들을 한 편으로 정리](https://simonwillison.net/2026/Aug/2/open-letters/)했다. 개별 서한을 쫓기보다 **이 요약 한 편이 진영 지도를 보기에 가장 효율적**이다.

서명 측 목소리도 분명하다. Sakana AI의 hardmaru는 [열린 생태계가 건강한 AI 산업의 토대](https://bsky.app/profile/hardmaru.bsky.social/post/3mrmwt4zonc2z)라며 공개 서한 서명을 밝혔다 — **집단 지성**을 근거로 삼는 오픈 진영의 전형적 논리다.

한편 속도조절론은 예상 밖 인물들로 확산 중이다. [Sam Altman만 브레이크를 밟자고 하는 게 아니라](https://techcrunch.com/video/sam-altman-isnt-the-only-one-who-wants-to-pump-the-brakes-on-ai/)는 보도, 그리고 구글이 [Earth AI 기능을 출시 하루 만에 철회](https://techcrunch.com/2026/07/31/google-nixes-its-earth-ai-feature-one-day-after-launch-amid-criticism-it-would-spread-misinformation/)한 사건은 **여론 리스크가 출시 결정을 실시간으로 뒤집는** 단계에 왔음을 보여준다.

**관련 자료**

- [Our position on open-weights models (Anthropic)](https://www.anthropic.com/news/position-open-weights-models)
- [Open letters about AI development (Simon Willison)](https://simonwillison.net/2026/Aug/2/open-letters/)
- [Sakana AI의 공개 서한 서명 (hardmaru)](https://bsky.app/profile/hardmaru.bsky.social/post/3mrmwt4zonc2z)
- [Sam Altman isn't the only one who wants to pump the brakes on AI](https://techcrunch.com/video/sam-altman-isnt-the-only-one-who-wants-to-pump-the-brakes-on-ai/)
- [Google nixes its Earth AI feature one day after launch](https://techcrunch.com/2026/07/31/google-nixes-its-earth-ai-feature-one-day-after-launch-amid-criticism-it-would-spread-misinformation/)
- [Judge denies xAI's request to block Minnesota ban on 'nudify' apps](https://techcrunch.com/2026/08/01/judge-denies-xais-request-to-block-minnesota-ban-on-nudify-apps/)

---

### 주목할 만한 개별 발견

#### 스테이트리스 MCP 스펙이 다시 불을 붙였다

- 출처: [링크](https://bsky.app/profile/simonwillison.net/post/3mry3ilyu7s2f)

**새 스테이트리스 MCP 스펙**이 Simon Willison의 MCP에 대한 관심을 되살렸고, 곧바로 `mcp-explorer`·`datasette-mcp` 같은 신규 프로젝트로 이어졌다. 스펙에서 **상태를 걷어내자 도구 제작 난이도가 내려간** 전형적 사례다.

같은 맥락에서 [ChatGPT와 Claude 일반 채팅 인터페이스에 커스텀 MCP 서버를 붙이는 TIL](https://bsky.app/profile/simonwillison.net/post/3mrr3z77wj224)도 나왔다 — MCP가 개발자 도구를 넘어 **일반 채팅 표면까지 내려오는 중**이다.

---

#### SWE-Bench류 벤치마크의 정합성 자체를 의심하다

- 출처: [링크](http://arxiv.org/abs/2607.28587)

**PAIChecker**는 SWE-Bench 계열 벤치마크에서 **PR과 이슈가 실제로 대응하지 않는 케이스**를 찾아낸다. 코딩 에이전트 순위표를 신뢰의 근거로 쓰기 전에, 그 벤치마크 데이터 자체가 검증됐는지 물어야 한다는 얘기다.

앞서 나온 ARC-AGI-3 설정 이슈와 합치면 결론은 하나다 — **외부 벤치마크 숫자는 도입 근거가 아니라 참고치**이고, 실제 판단은 자체 태스크로 만든 소규모 eval에서 나와야 한다. 마침 같은 주에 [smevals](https://bsky.app/profile/simonwillison.net/post/3mrxwydoc5k25)라는 소형 eval 스위트 러너가 공개됐다.

---

#### 재귀적 자기개선을 ML 엔지니어링에서 시도하다

- 출처: [링크](https://huggingface.co/papers/2607.28568)

**Frontis-MA1**은 ML 엔지니어링 영역에서 **재귀적 자기개선(recursive self-improvement)**을 향한 "AI4AI" 모델 학습을 다룬다. 담론으로만 돌던 개념이 **구체적 도메인 하나로 좁혀져 논문화**된 점이 주목할 지점이다.

범용 자기개선이 아니라 **ML 엔지니어링이라는 검증 가능한 좁은 트랙**을 고른 설계가 현실적이다. 결과의 성패와 무관하게 이 접근법 자체가 앞으로 반복될 패턴으로 보인다.

---

#### AI 사용에 대한 자기 규율이 소비자 이슈로 올라오다

- 출처: [링크](https://techcrunch.com/2026/08/01/youtuber-hank-green-says-his-ai-usage-is-not-healthy/)

유튜버 **Hank Green**이 본인의 AI 사용이 "건강하지 않다"고 공개적으로 말했고, 같은 날 [중독성 앱을 물리적으로 잠그는 9달러짜리 키](https://techcrunch.com/2026/08/01/this-9-key-physically-locks-your-most-addictive-apps/) 기사가 나왔다. AI 논의가 능력·안전을 넘어 **개인의 사용 습관**으로 확장되는 흐름이다.

플랫폼도 반응했다. [Snapchat이 완전 AI 생성 Spotlight 콘텐츠에 보상을 주지 않기로](https://techcrunch.com/2026/07/31/snapchat-no-longer-rewards-fully-ai-generated-spotlight-content/) 한 결정은, **생성 비용이 0에 수렴할 때 유통 플랫폼이 취하는 필연적 방어**다.

</div>

<aside class="ai-home-aside">
  <section class="ai-week-block">
    <p class="ai-eyebrow">🔥 X 화제 키워드</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://x.com/GoogleCloudTech/status/2085475708143374815" target="_blank" rel="noopener">
    <span class="ai-pick-date">🆕</span>
    <span class="ai-pick-title-mini">Gemini</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://x.com/simplifyinAI/status/2085544336926847403" target="_blank" rel="noopener">
    <span class="ai-pick-date">🆕</span>
    <span class="ai-pick-title-mini">Codex</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://x.com/teneo_protocol/status/2085770833843167351" target="_blank" rel="noopener">
    <span class="ai-pick-date">🆕</span>
    <span class="ai-pick-title-mini">DeepSeek</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://x.com/_avichawla/status/2085632663902412985" target="_blank" rel="noopener">
    <span class="ai-pick-date">🆕</span>
    <span class="ai-pick-title-mini">NVIDIA</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://x.com/simplifyinAI/status/2085544336926847403" target="_blank" rel="noopener">
    <span class="ai-pick-date">🆕</span>
    <span class="ai-pick-title-mini">Perplexity</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://x.com/MiniMax_AI/status/2085556856311984150" target="_blank" rel="noopener">
    <span class="ai-pick-date">🆕</span>
    <span class="ai-pick-title-mini">ComfyUI</span>
  </a>
</li>
    </ul>
  </section>
  <section class="ai-week-block">
    <p class="ai-eyebrow">THIS WEEK</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260808/">
    <span class="ai-pick-date">2026-08-08</span>
    <span class="ai-pick-title-mini">PrimeIntellect-ai/prime-agent — 코딩 워크플로우와 장시간 자율 작업을 위한 자기개선…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260806/">
    <span class="ai-pick-date">2026-08-06</span>
    <span class="ai-pick-title-mini">cloudflare/computer — 에이전트에게 컴퓨터를 통째로 주는 엣지 실행 샌드박스</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260805/">
    <span class="ai-pick-date">2026-08-05</span>
    <span class="ai-pick-title-mini">TencentCloud/TencentDB-Agent-Memory — 대화·문서·코드를 4종 자산으로 재사용하…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260804/">
    <span class="ai-pick-date">2026-08-04</span>
    <span class="ai-pick-title-mini">esengine/DeepSeek-Reasonix — prefix-cache 안정성을 축으로 설계한 터미널 코…</span>
  </a>
</li>
    </ul>
  </section>
  <section class="ai-week-block">
    <p class="ai-eyebrow">LAST WEEK</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260802/">
    <span class="ai-pick-date">2026-08-02</span>
    <span class="ai-pick-title-mini">Stateless MCP has recaptured my interest (and inspired mcp-e…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260801/">
    <span class="ai-pick-date">2026-08-01</span>
    <span class="ai-pick-title-mini">different-ai/openwork — Claude Cowork의 오픈소스 대체 에이전트 하네스 (ope…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260731/">
    <span class="ai-pick-date">2026-07-31</span>
    <span class="ai-pick-title-mini">different-ai/openwork — Claude Cowork의 오픈소스 대안(opencode 기반)</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260730/">
    <span class="ai-pick-date">2026-07-30</span>
    <span class="ai-pick-title-mini">Anatomy of a Frontier Lab Agent Intrusion: A Technical Timel…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260729/">
    <span class="ai-pick-date">2026-07-29</span>
    <span class="ai-pick-title-mini">Bringing MCP 2026-07-28 to Claude</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260728/">
    <span class="ai-pick-date">2026-07-28</span>
    <span class="ai-pick-title-mini">alibaba/open-code-review — 결정론적 파이프라인 + LLM 에이전트 하이브리드 코드리뷰 …</span>
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
