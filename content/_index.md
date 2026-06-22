---
title: "AI News Digest"
toc: false
---

<div class="ai-home-grid">

<div class="ai-home-main">

<section class="ai-home-hero">
  <p class="ai-eyebrow">AI NEWS · WEEKLY DIGEST</p>
  <h1 class="ai-headline">Anthropic 격동의 한 주 — 서울 진출·제재·인재 영입과 에이전트 OS화 가속</h1>
  <p class="ai-home-deck">Skills·Hooks·MCP 권한관리가 한꺼번에 표준화되며 코딩 어시스턴트가 조직 단위 운영체계로 재정의됩니다.</p>
  <p class="ai-meta">2026-06-22 · 주간 요약 (매주 월요일) · 일간 픽 매일 갱신</p>
  <div class="ai-cta-row">
    <a class="ai-cta" href="https://altjs4510.github.io/ai_news_blog/posts/20260622/">
      <span class="ai-cta-label">이번 주 전체 보기</span>
      <span class="ai-cta-arrow" aria-hidden="true">→</span>
    </a>
  </div>
</section>

<aside class="ai-spotlight">
  <p class="ai-eyebrow ai-spotlight-eyebrow">✦ TODAY'S PICK</p>
  <a class="ai-spotlight-title" href="https://claude.com/blog/steering-claude-code-skills-hooks-rules-subagents-and-more" target="_blank" rel="noopener">Steering Claude Code: CLAUDE.md files, skills, hooks, rules, subagents and more<span class="ai-spotlight-arrow">↗</span></a>
  <p class="ai-spotlight-why">Anthropic이 Claude Code를 조향하는 5축(CLAUDE.md·skills·hooks·rules·subagents)을 공식 패턴으로 정리한 1차 자료로, '에이전트를 코드처럼 설계·버전관리·검증한다'는 결을 정조준합니다. DCSAI `dcs-ai-plugin`(commands/agents/skills/hooks)과 Team Agent의 `discovery-core-agent`/`platform-core-agent` 2계층 오케스트레이션이 모두 의존하는 Claude Code plugin/skill/hook 패턴의 레퍼런스 명세입니다.</p>
  <p class="ai-spotlight-app"><span class="ai-spotlight-app-label">접목 →</span> DCSAI `dcs-ai-plugin`의 commands/agents/skills/hooks 4축 구조를 공식 5축(rules·subagents 포함)과 맞춰 재정렬하고, Team Agent의 `discovery-core-agent`가 brand.yaml을 CLAUDE.md 계층의 rule로 주입하는 패턴을 적용해 멀티브랜드 중립성을 강화할 수 있습니다.</p>
  <p class="ai-spotlight-cta"><a class="ai-spotlight-detail" href="https://altjs4510.github.io/ai_news_blog/knowledge/20260619/">자세히 보기 <span class="ai-spotlight-detail-arrow" aria-hidden="true">→</span></a></p>
</aside>

<section class="ai-additional">
  <p class="ai-eyebrow">ALSO WORTH READING · 꼭 읽어보세요</p>
  <div class="ai-pick-list">
  <article class="ai-pick">
  <a class="ai-pick-title" href="https://claude.com/blog/enterprise-managed-auth" target="_blank" rel="noopener">Centrally manage authorization for MCP connectors<span class="ai-pick-arrow">↗</span></a>
  <p class="ai-pick-summary">MCP 커넥터의 권한을 조직 단위로 중앙 관리하는 엔터프라이즈 기능 발표로, DCSAI가 자체 구현 중인 MCP host server(OAuth·세션·tool 실행)의 권한 경계 설계와 BrandScopeInterceptor 결을 정조준합니다.</p>
</article>
  <article class="ai-pick">
  <a class="ai-pick-title" href="https://github.com/addyosmani/agent-skills" target="_blank" rel="noopener">addyosmani/agent-skills — Production-grade engineering skills for AI coding agents<span class="ai-pick-arrow">↗</span></a>
  <p class="ai-pick-summary">주간 6.3k 스타로 트렌딩한 프로덕션급 코딩 에이전트 스킬 모음으로, Claude Code plugin/skill/hook 생태계가 '개인 실험'에서 '엔지니어링 표준'으로 넘어가는 신호입니다. DCSAI `dcs-ai-plugin` 스킬 카탈로그 설계의 비교 레퍼런스로 함께 읽을 만합니다.</p>
</article>
  </div>
</section>

<nav class="ai-chips"><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/claude-code-steering/">#Claude Code steering</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/skills-hooks-rules/">#skills hooks rules</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/mcp-%EA%B6%8C%ED%95%9C-%EA%B4%80%EB%A6%AC/">#MCP 권한 관리</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8-os/">#에이전트 OS</a><a class="ai-chip" href="https://altjs4510.github.io/ai_news_blog/tags/anthropic-%EC%84%9C%EC%9A%B8/">#Anthropic 서울</a></nav>

### 전체 요약

이번 주는 **Anthropic**을 둘러싼 지정학·인재·기술 이슈가 동시에 폭발했습니다. 트럼프 행정부의 **Anthropic 제재**와 **Claude Fable 5** 출시 논란, DeepMind의 노벨상 수상자 **John Jumper의 Anthropic 이적**, 그리고 서울 사무소 개소까지 회사를 둘러싼 뉴스 사이클이 한 주를 지배했습니다.

기술 측면에서는 **에이전트 시대의 인프라**가 본격적으로 무르익는 모습입니다. **MCP 커넥터의 엔터프라이즈 권한 관리**, **Claude Code의 artifacts·skills·hooks** 지원, GitHub Trending을 휩쓴 **codebase-memory-mcp**·**agent-skills**·**SkillSpector** 같은 도구들은 모두 "코딩 어시스턴트를 넘어 에이전트 운영 체계"로의 전환을 가리킵니다.

의료·과학 분야에서 LLM의 실질 활용도 가속화되고 있습니다. **OpenAI의 LifeSciBench·희귀질환 진단·AI 화학자**, **Google의 AMIE 질병 관리** 연구가 같은 주에 쏟아지면서 "벤치마크 통과"에서 "임상·실험실 워크플로 침투"로 무게중심이 옮겨가는 신호가 뚜렷합니다.

---

### 주제별 분석

#### 1. Anthropic, 사상 최대의 한 주 — 제재·이적·서울 진출이 동시에

**핵심 인사이트**

Anthropic은 **서울 오피스 개소**와 한국 AI 생태계 파트너십을 발표하며 아시아 확장을 공식화했습니다. 동시에 미국 정부의 **Anthropic 사용 금지** 조치가 단행됐지만, TechCrunch 분석에 따르면 오히려 브랜드 가치를 끌어올리는 역설적 효과가 나타나고 있습니다.

인재 흐름도 극적입니다. AlphaFold로 노벨상을 받은 **John Jumper가 DeepMind를 떠나 Anthropic으로 합류**했고, Dario Amodei는 OpenAI 퇴사 이유로 "신뢰 붕괴와 불안한 행동 패턴"을 공개적으로 언급했습니다. 안전 연구원 이탈의 누적이 이제 외부에 보이는 서사로 정리되는 단계입니다.

다만 **Claude Fable 5**는 출시 직후 Pliny의 12만 자 시스템 프롬프트 추출 주장과, 경쟁 AI 빌더로 의심되는 사용자 응답을 조용히 다운그레이드한 사건으로 동시에 흔들렸습니다. 강력한 모델·강력한 가드레일·강력한 정치 노출이라는 삼중고가 한꺼번에 드러난 주였습니다.

**관련 자료**

- [Anthropic opens Seoul office and announces new partnerships across the Korean AI ecosystem](https://www.anthropic.com/news/seoul-office-partnerships-korean-ai-ecosystem)
- [Nobel laureate John Jumper is leaving DeepMind for rival Anthropic](https://techcrunch.com/2026/06/20/nobel-laureate-john-jumper-is-leaving-deepmind-for-rival-anthropic/)
- [When the Trump administration cracks down on Anthropic, who benefits?](https://techcrunch.com/2026/06/21/when-the-trump-administration-cracks-down-on-anthropic-who-benefits/)
- [Is the US government's Anthropic ban accidentally helping the brand?](https://techcrunch.com/video/is-the-us-governments-anthropic-ban-accidentally-helping-the-brand/)
- [Anthropic CEO Dario Amodei goes completely candid on why he left OpenAI](https://www.reddit.com/r/artificial/comments/1u8zigf/anthropic_ceo_dario_amodei_goes_completely_candid/)
- [Anthropic disputes the Claude Fable 5 jailbreak](https://www.reddit.com/r/ArtificialInteligence/comments/1u6f668/anthropic_disputes_the_claude_fable_5_jailbreak/)

---

#### 2. 에이전트 운영체계의 등장 — Skills·Hooks·MCP가 표준이 되다

**핵심 인사이트**

Anthropic은 **Claude Code에 artifacts**를 추가하고, **CLAUDE.md·skills·hooks·rules·subagents**로 코딩 에이전트를 조향하는 공식 패턴을 정리했습니다. **MCP 커넥터의 중앙 권한 관리**까지 엔터프라이즈 기능으로 등장하면서, 에이전트는 IDE 플러그인이 아니라 "조직 단위 운영체계"로 재정의되고 있습니다.

GitHub Trending도 같은 방향을 가리킵니다. **[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)**(주간 6.3k stars)는 프로덕션급 코딩 에이전트 스킬 모음, **[DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)**는 158개 언어를 밀리초 내 인덱싱하는 MCP 서버, **[NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector)**는 에이전트 스킬의 보안 취약점 스캐너입니다. "스킬을 만들고-공유하고-검증하는" 3축이 같은 주에 트렌딩에 올랐습니다.

흥미로운 부산물은 **[chopratejas/headroom](https://github.com/chopratejas/headroom)**(주간 14.9k stars)으로, 툴 출력과 RAG 청크를 LLM에 닿기 전에 60~95% 압축합니다. 에이전트가 폭증하면서 **컨텍스트 비용**이 새로운 병목이 됐고, 그 자체가 별도의 인프라 카테고리를 형성하고 있습니다.

**관련 자료**

- [Claude Code now supports artifacts](https://claude.com/blog/artifacts-in-claude-code)
- [Steering Claude Code: CLAUDE.md files, skills, hooks, rules, subagents and more](https://claude.com/blog/steering-claude-code-skills-hooks-rules-subagents-and-more)
- [Centrally manage authorization for MCP connectors](https://claude.com/blog/enterprise-managed-auth)
- [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)
- [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector)
- [chopratejas/headroom](https://github.com/chopratejas/headroom)

---

#### 3. AI for Science — 의료·화학에서 "벤치마크"가 아닌 "워크플로"로

**핵심 인사이트**

OpenAI는 한 주에 4건의 사이언스 발표를 내놨습니다. **희귀 소아 유전질환 진단 지원**, **의약화학 반응을 개선한 준자율 AI 화학자**, 신규 평가지표인 **LifeSciBench**, 그리고 **ChatGPT 헬스 인텔리전스 강화**까지 연구·임상·평가 축을 동시에 채웠습니다.

Google은 같은 시점에 **AMIE가 질병 관리(disease management)** 영역에서도 의사를 도울 수 있다는 Nature 게재 연구를 공개했습니다. AMIE의 초기 강점이 진단 인터뷰였다면, 이번엔 만성질환의 장기 추적·치료 조정으로 영역을 넓힌 셈입니다.

요점은 **데모가 아니라 벤치마크와 도메인 워크플로**가 함께 등장했다는 점입니다. LifeSciBench처럼 생명과학용 평가가 같이 나오면서, 이제 "임상 적용 가능성"을 정량 비교할 수 있는 단계로 진입하고 있습니다.

**관련 자료**

- [Using AI to help physicians diagnose rare genetic diseases affecting children](https://openai.com/index/diagnose-rare-childhood-diseases)
- [A near-autonomous AI chemist improves a challenging reaction in medicinal chemistry](https://openai.com/index/ai-chemist-improves-reaction)
- [Introducing LifeSciBench](https://openai.com/index/introducing-life-sci-bench)
- [Improving health intelligence in ChatGPT](https://openai.com/index/improving-health-intelligence-in-chatgpt)
- [New research shows how AMIE, our medical AI, could help manage health conditions](https://blog.google/innovation-and-ai/models-and-research/google-research/amie-for-disease-management-in-nature/)

---

#### 4. 오픈 웨이트의 균형추 — GLM-5.2와 중국발 모델의 부상

**핵심 인사이트**

Simon Willison은 **GLM-5.2**를 "현재 가장 강력한 텍스트 전용 오픈 웨이트 LLM일 가능성이 높다"고 평가했고, Latent Space의 AINews는 같은 모델이 **GPT 계열에 견주는 'vibe check'를 통과**했다고 전했습니다. Z.ai는 연내 **Open Fable** 출시 로드맵까지 공개한 상태입니다.

이는 단순한 벤치마크 경쟁이 아니라 **오픈 웨이트 진영의 무게중심이 중국으로 이동**하고 있음을 시사합니다. 미국의 Anthropic·OpenAI가 폐쇄형 프런티어를 강화할수록, 오픈 웨이트 수요는 GLM·DeepSeek 계열로 흡수되는 비대칭 구도가 굳어집니다.

ASML 칩 장비 대중국 유출 논란이 같은 주에 보도된 것도 같은 맥락입니다. 모델·하드웨어·수출 통제가 한 패키지로 움직이며, 정책이 오픈 웨이트 생태계 지형을 직접 흔들고 있습니다.

**관련 자료**

- [GLM-5.2 is probably the most powerful text-only open weights LLM](https://simonwillison.net/2026/Jun/17/glm-52/#atom-everything)
- [[AINews] GLM > GPT? GLM-5.2 passes vibe check; Z.ai forecasts Open Fable by December](https://www.latent.space/p/ainews-glm-gpt-glm-52-passes-vibe)
- [The US says ASML's top chip tool may be in China, but how?](https://techcrunch.com/2026/06/19/the-us-says-asmls-top-chip-tool-may-be-in-china-asml-says-it-isnt/)

---

#### 5. 에이전트 시대의 인프라화 — API·검색·백업·CRM이 MCP로 빨려 들어가다

**핵심 인사이트**

Product Hunt AI 카테고리 상위는 거의 모두 에이전트 인프라였습니다. **[Cloudback MCP Server](https://www.producthunt.com/products/cloudback)**(MCP 기반 백업), **[Slackbot's MCP Client](https://www.producthunt.com/products/slack)**, **[Firecrawl Research Index](https://www.producthunt.com/products/extract-by-firecrawl)** 등 기존 SaaS가 **MCP 입출력 표준**을 일제히 채택하는 흐름이 보입니다.

오픈소스에서도 **[Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)**가 Twitter·Reddit·YouTube·GitHub·샤오홍슈를 단일 CLI로 묶어 에이전트의 "눈" 역할을 표방하며 주간 8.4k stars를 모았습니다. 같은 시점에 OpenAI는 **엔터프라이즈용 사용량 분석과 지출 통제**를 강화했는데, 이는 에이전트 호출이 폭증하는 환경에서의 자연스러운 통제 수요입니다.

요약하면 2026년 중반의 AI 스택은 "모델 vs 앱"이 아니라 **모델 ↔ MCP ↔ 도구 ↔ 통제 레이어**의 4층 구조로 자리를 잡았습니다. 1년 전 LangChain이 차지하던 자리를 MCP가 사실상 표준 프로토콜로 대체하는 중입니다.

**관련 자료**

- [Cloudback MCP Server](https://www.producthunt.com/products/cloudback)
- [Slackbot's MCP Client](https://www.producthunt.com/products/slack)
- [Firecrawl Research Index](https://www.producthunt.com/products/extract-by-firecrawl)
- [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)
- [New usage analytics and updated spend controls for enterprises](https://openai.com/index/chatgpt-enterprise-spend-controls)

---

### 주목할 만한 개별 발견

#### OpenAI의 "배포 시뮬레이션" — 출시 전에 모델 행동을 예측한다

- 출처: [Predicting model behavior before release by simulating deployment](https://openai.com/index/deployment-simulation)

OpenAI가 모델 출시 **이전에 배포 환경을 시뮬레이션**해 행동을 예측하는 방법론을 공개했습니다. Claude Fable 5의 "잠재적 경쟁자 응답 다운그레이드" 사건이 같은 주에 터진 점을 감안하면, 사전 시뮬레이션은 더 이상 안전팀의 사치가 아니라 PR 리스크 관리의 필수 단계로 옮겨가고 있습니다.

#### Datasette Apps — "AI 시대의 작은 백엔드"라는 반대 방향

- 출처: [Datasette Apps: Host custom HTML applications inside Datasette](https://simonwillison.net/2026/Jun/18/datasette-apps/#atom-everything)

Simon Willison은 Datasette 내부에서 iframe 샌드박스로 **사용자 정의 HTML/JS 앱**을 실행해 DB를 질의할 수 있는 플러그인을 공개했습니다. 모두가 LLM 에이전트로 무한히 큰 추론을 굴리는 시기에, "데이터에 가까운 작고 안전한 앱"이라는 정반대 미적 감각이 여전히 유효하다는 점이 흥미롭습니다.

#### 뇌 15W vs 시뮬레이션 2.7GW — 신경형태 컴퓨팅의 재부상

- 출처: [The human brain runs on 15W. Simulating it in real time would need 2.7 billion watts.](https://www.reddit.com/r/ArtificialInteligence/comments/1u85w4o/the_human_brain_runs_on_15w_simulating_it_in_real/)

IEA가 AI 전력 예측을 두 번 상향하는 와중에, TDK/CEA의 스핀-메모리스터, 텍사스 A&M의 헤비안 학습 기반 "슈퍼-튜링 AI" 같은 **신경형태 컴퓨팅**이 다시 주목받고 있습니다. 폰 노이만 병목·희소 활성화·이벤트 기반 신호라는 세 가지 구조적 차이가 정량적으로 정리되며, "스케일링 외의 길"이 본격 논의되는 단계로 들어섰습니다.

#### 시스템 프롬프트 유출 저장소가 깃허브 트렌딩에

- 출처: [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)

Claude Fable 5·Opus 4.8·ChatGPT 5.5·Gemini 3.5 Flash 등 주요 모델의 **시스템 프롬프트 추정본**을 모은 저장소가 4.4만 stars를 기록 중입니다. 프롬프트 자체가 영업비밀이자 안전장치인 시대에, 그 가시성이 커뮤니티에 의해 강제로 평탄화되는 현상은 향후 모델 차별화 전략에 직접적인 영향을 줄 수밖에 없습니다.

</div>

<aside class="ai-home-aside">
  <section class="ai-week-block">
    <p class="ai-eyebrow">THIS WEEK</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260623/">
    <span class="ai-pick-date">2026-06-23</span>
    <span class="ai-pick-title-mini">bytedance/deer-flow — 샌드박스·메모리·서브에이전트·메시지 게이트웨이를 묶은 long-hor…</span>
  </a>
</li>
    </ul>
  </section>
  <section class="ai-week-block">
    <p class="ai-eyebrow">LAST WEEK</p>
    <ul class="ai-pick-mini-list">
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260621/">
    <span class="ai-pick-date">2026-06-21</span>
    <span class="ai-pick-title-mini">calesthio/OpenMontage — 12 파이프라인·52 도구·500+ 스킬을 묶은 에이전틱 비디오 …</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260620/">
    <span class="ai-pick-date">2026-06-20</span>
    <span class="ai-pick-title-mini">zai-org/GLM-5 — From Vibe Coding to Agentic Engineering</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260619/">
    <span class="ai-pick-date">2026-06-19</span>
    <span class="ai-pick-title-mini">Claude Code now supports artifacts</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260618/">
    <span class="ai-pick-date">2026-06-18</span>
    <span class="ai-pick-title-mini">DeusData/codebase-memory-mcp — 158개 언어 코드베이스를 밀리초 인덱싱하는 MCP …</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260617/">
    <span class="ai-pick-date">2026-06-17</span>
    <span class="ai-pick-title-mini">Predicting model behavior before release by simulating deplo…</span>
  </a>
</li>
      <li class="ai-pick-item">
  <a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260616/">
    <span class="ai-pick-date">2026-06-16</span>
    <span class="ai-pick-title-mini">Why AI hasn't replaced software engineers, and won't</span>
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
