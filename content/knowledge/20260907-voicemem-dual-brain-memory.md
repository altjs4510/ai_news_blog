---
title: "VoiceMem — 좌뇌·우뇌로 쪼갠 스트리밍 메모리로 음성 에이전트 지연 없애기"
date: 2026-09-07
source_url: "https://github.com/xzf-thu/VoiceMem"
tags: ["에이전트 메모리", "보이스 에이전트", "스트리밍", "감정 메모리", "오픈소스", "직접 실행", "설계 철학"]
categories: ["모델 & 연구"]
---

<div class="ai-knowledge-shell">

<aside class="ai-knowledge-sidebar">
  <p class="ai-eyebrow">CATEGORIES</p>
  <nav class="ai-cat-tree"><details class="ai-cat" open><summary><span class="catname">에이전트 오케스트레이션</span><span class="catcount">13</span></summary><ul><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260908/"><span class="kdate">2026-09-08</span><span class="ktitle">bytedance/deer-flow — 샌드박스·메모리·서브에이전트·메시지 게이트웨이를…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260904/"><span class="kdate">2026-09-04</span><span class="ktitle">HarnessDev: Can LLMs Create and Evolve Their Own…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260831-openexecutive-virtual-c-suite/"><span class="kdate">2026-08-31</span><span class="ktitle">Open Executive — 8명의 전문 에이전트를 하나의 임원 목소리로</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260828/"><span class="kdate">2026-08-28</span><span class="ktitle">Google ADK for Python v2.8.0 — RemoteA2aAgent 네이…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260826/"><span class="kdate">2026-08-26</span><span class="ktitle">apache/maka — 도구 호출·권한 결정·종료 이벤트를 append-only 로그…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260823/"><span class="kdate">2026-08-23</span><span class="ktitle">The Evolution of the Agent Harness — 하네스가 모델 가중치…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260821/"><span class="kdate">2026-08-21</span><span class="ktitle">volcengine/OpenViking — 에이전트 메모리·Knowledge RAG·스…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260805/"><span class="kdate">2026-08-05</span><span class="ktitle">TencentCloud/TencentDB-Agent-Memory — 대화·문서·코드를 …</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260623/"><span class="kdate">2026-06-23</span><span class="ktitle">bytedance/deer-flow — 샌드박스·메모리·서브에이전트·메시지 게이트웨이를…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260611/"><span class="kdate">2026-06-11</span><span class="ktitle">The evolution of agentic surfaces: building with…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260602/"><span class="kdate">2026-06-02</span><span class="ktitle">revfactory/harness — 도메인별 에이전트 팀과 스킬을 자동 설계하는 메타…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260529/"><span class="kdate">2026-05-29</span><span class="ktitle">Introducing dynamic workflows in Claude Code</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260507/"><span class="kdate">2026-05-07</span><span class="ktitle">ruvnet/ruflo — Claude 멀티 에이전트 오케스트레이션 플랫폼</span></a></li></ul></details><details class="ai-cat" open><summary><span class="catname">MCP &amp; 도구 통합</span><span class="catcount">20</span></summary><ul><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260831-gitnexus-code-knowledge-graph/"><span class="kdate">2026-08-31</span><span class="ktitle">GitNexus — 코드베이스를 지식그래프로 바꿔 에이전트에게 쥐어주기</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260829/"><span class="kdate">2026-08-29</span><span class="ktitle">cursor/plugins — 플러그인 명세(specification)와 공식 플러그인…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260802/"><span class="kdate">2026-08-02</span><span class="ktitle">Stateless MCP has recaptured my interest (and in…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260801/"><span class="kdate">2026-08-01</span><span class="ktitle">different-ai/openwork — Claude Cowork의 오픈소스 대체 에…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260731/"><span class="kdate">2026-07-31</span><span class="ktitle">different-ai/openwork — Claude Cowork의 오픈소스 대안(o…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260729/"><span class="kdate">2026-07-29</span><span class="ktitle">Bringing MCP 2026-07-28 to Claude</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260721/"><span class="kdate">2026-07-21</span><span class="ktitle">tirth8205/code-review-graph — 로컬 우선 코드 인텔리전스 그래프…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260719/"><span class="kdate">2026-07-19</span><span class="ktitle">tirth8205/code-review-graph — 로컬 우선 코드 인텔리전스 그래프…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260718/"><span class="kdate">2026-07-18</span><span class="ktitle">tirth8205/code-review-graph — MCP·CLI용 로컬 코드 인텔리…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260709/"><span class="kdate">2026-07-09</span><span class="ktitle">mvanhorn/last30days-skill — Reddit·X·YouTube·HN·…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260708/"><span class="kdate">2026-07-08</span><span class="ktitle">Expanding Managed Agents in Gemini API: backgrou…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260701/"><span class="kdate">2026-07-01</span><span class="ktitle">Google OKF (Open Knowledge Format) — 벤더 중립 에이전트 …</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260618/"><span class="kdate">2026-06-18</span><span class="ktitle">DeusData/codebase-memory-mcp — 158개 언어 코드베이스를 밀리…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260606/"><span class="kdate">2026-06-06</span><span class="ktitle">chopratejas/headroom — Compress tool outputs, lo…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260605/"><span class="kdate">2026-06-05</span><span class="ktitle">chopratejas/headroom — Compress tool outputs, lo…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260604/"><span class="kdate">2026-06-04</span><span class="ktitle">chopratejas/headroom — Compress tool outputs bef…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260603/"><span class="kdate">2026-06-03</span><span class="ktitle">How Bad MCP design cost your Agent 5× more token…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260523/"><span class="kdate">2026-05-23</span><span class="ktitle">colbymchenry/codegraph — 사전 인덱싱된 코드 지식 그래프 MCP</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260517/"><span class="kdate">2026-05-17</span><span class="ktitle">I gave my LLM 100,000+ tools — Lazy Discovery &a…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260509/"><span class="kdate">2026-05-09</span><span class="ktitle">How to connect 100 MCP servers without the conte…</span></a></li></ul></details><details class="ai-cat" open><summary><span class="catname">코딩 에이전트</span><span class="catcount">30</span></summary><ul><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260906/"><span class="kdate">2026-09-06</span><span class="ktitle">DietrichGebert/ponytail — 에이전트를 '방에서 가장 게으른 시니어 …</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260903/"><span class="kdate">2026-09-03</span><span class="ktitle">pacifio/atlas — 여러 코딩 에이전트의 변경을 한곳에서 추적·질의하는 '에이…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260901/"><span class="kdate">2026-09-01</span><span class="ktitle">affaan-m/ECC — 스킬·본능·메모리·보안을 묶은 에이전트 하네스 성능 최적화 …</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260822/"><span class="kdate">2026-08-22</span><span class="ktitle">mattpocock/skills — Skills for Real Engineers (하…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260820/"><span class="kdate">2026-08-20</span><span class="ktitle">akitaonrails/ai-memory — 코딩 에이전트 CLI의 장기 메모리와 벤더…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260819/"><span class="kdate">2026-08-19</span><span class="ktitle">akitaonrails/ai-memory — 코딩 에이전트 CLI 간 장기 기억과 벤더…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260814/"><span class="kdate">2026-08-14</span><span class="ktitle">cathrynlavery/diagram-design — Claude Code용 에디토리…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260811/"><span class="kdate">2026-08-11</span><span class="ktitle">PrimeIntellect-ai/prime-agent — 장기 자율 실행을 전제로 설계…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260810/"><span class="kdate">2026-08-10</span><span class="ktitle">Auto mode is now the default in Claude Code for …</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260809/"><span class="kdate">2026-08-09</span><span class="ktitle">PrimeIntellect-ai/prime-agent — 코딩 워크플로우·장기 자율 작…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260808/"><span class="kdate">2026-08-08</span><span class="ktitle">PrimeIntellect-ai/prime-agent — 코딩 워크플로우와 장시간 자율…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260804/"><span class="kdate">2026-08-04</span><span class="ktitle">esengine/DeepSeek-Reasonix — prefix-cache 안정성을 축…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260728/"><span class="kdate">2026-07-28</span><span class="ktitle">alibaba/open-code-review — 결정론적 파이프라인 + LLM 에이전트…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260725/"><span class="kdate">2026-07-25</span><span class="ktitle">The new rules of context engineering for Claude …</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260722/"><span class="kdate">2026-07-22</span><span class="ktitle">tirth8205/code-review-graph — MCP·CLI용 로컬 우선 코드 …</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260714/"><span class="kdate">2026-07-14</span><span class="ktitle">Graphify-Labs/graphify — 코드베이스를 질의 가능한 지식 그래프로 만…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260707/"><span class="kdate">2026-07-07</span><span class="ktitle">AI Hero Skills Catalog — 실무 엔지니어를 위한 재사용 가능한 판단 …</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260705/"><span class="kdate">2026-07-05</span><span class="ktitle">openai/codex-plugin-cc — Claude Code에서 Codex를 위임…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260626/"><span class="kdate">2026-06-26</span><span class="ktitle">google-labs-code/design.md — 코딩 에이전트에게 디자인 시스템을 …</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260619/"><span class="kdate">2026-06-19</span><span class="ktitle">Claude Code now supports artifacts</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260530/"><span class="kdate">2026-05-30</span><span class="ktitle">Leonxlnx/taste-skill — AI에게 좋은 취향을 부여해 generic s…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260528/"><span class="kdate">2026-05-28</span><span class="ktitle">Building self-improving tax agents with Codex</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260526/"><span class="kdate">2026-05-26</span><span class="ktitle">colbymchenry/codegraph — Pre-indexed code knowle…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260524/"><span class="kdate">2026-05-24</span><span class="ktitle">colbymchenry/codegraph — Pre-indexed code knowle…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260521/"><span class="kdate">2026-05-21</span><span class="ktitle">colbymchenry/codegraph — Pre-indexed code knowle…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260512/"><span class="kdate">2026-05-12</span><span class="ktitle">agentmemory — Persistent memory for AI coding ag…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260510/"><span class="kdate">2026-05-10</span><span class="ktitle">addyosmani/agent-skills — Production-grade engin…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260508/"><span class="kdate">2026-05-08</span><span class="ktitle">addyosmani/agent-skills — Production-grade engin…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260506/"><span class="kdate">2026-05-06</span><span class="ktitle">mksglu/context-mode — AI 코딩 에이전트용 컨텍스트 윈도우 최적화</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260505/"><span class="kdate">2026-05-05</span><span class="ktitle">mattpocock/skills — Skills for Real Engineers (.…</span></a></li></ul></details><details class="ai-cat" open><summary><span class="catname">모델 &amp; 연구</span><span class="catcount">6</span></summary><ul><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260907-voicemem-dual-brain-memory/" class="current"><span class="kdate">2026-09-07</span><span class="ktitle">VoiceMem — 좌뇌·우뇌로 쪼갠 스트리밍 메모리로 음성 에이전트 지연 없애기</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260716-proprag/"><span class="kdate">2026-07-16</span><span class="ktitle">PropRAG — 프로포지션 경로 위 beam search로 멀티홉 검색 안내</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260620/"><span class="kdate">2026-06-20</span><span class="ktitle">zai-org/GLM-5 — From Vibe Coding to Agentic Engi…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260617/"><span class="kdate">2026-06-17</span><span class="ktitle">Predicting model behavior before release by simu…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260516/"><span class="kdate">2026-05-16</span><span class="ktitle">STALE — 에이전트가 자기 기억의 유효성을 인지할 수 있는가</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260513/"><span class="kdate">2026-05-13</span><span class="ktitle">Thinking Machines' Native Interaction Models — T…</span></a></li></ul></details><details class="ai-cat" open><summary><span class="catname">인프라 &amp; 컴퓨트</span><span class="catcount">8</span></summary><ul><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260905/"><span class="kdate">2026-09-05</span><span class="ktitle">magnitudedev/magnitude — 하드웨어에 맞는 최적 로컬 모델을 띄워 이…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260813/"><span class="kdate">2026-08-13</span><span class="ktitle">semantica-agi/semantica — 컨텍스트와 책임 추적을 위한 그래프 네이…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260812/"><span class="kdate">2026-08-12</span><span class="ktitle">semantica-agi/semantica — 컨텍스트와 '책임 추적 가능한(accou…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260806/"><span class="kdate">2026-08-06</span><span class="ktitle">cloudflare/computer — 에이전트에게 컴퓨터를 통째로 주는 엣지 실행 샌…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260724/"><span class="kdate">2026-07-24</span><span class="ktitle">diegosouzapw/OmniRoute — 단일 엔드포인트로 278+ 프로바이더·50…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260723/"><span class="kdate">2026-07-23</span><span class="ktitle">diegosouzapw/OmniRoute — 268+ 프로바이더를 단일 엔드포인트로 묶…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260522/"><span class="kdate">2026-05-22</span><span class="ktitle">Giving Agents Computers — Ivan Burazin, Daytona</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260520/"><span class="kdate">2026-05-20</span><span class="ktitle">New in Claude Managed Agents: self-hosted sandbo…</span></a></li></ul></details><details class="ai-cat" open><summary><span class="catname">보안 &amp; 거버넌스</span><span class="catcount">18</span></summary><ul><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260902/"><span class="kdate">2026-09-02</span><span class="ktitle">AIR raises $50M to help companies vet the skills…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260827/"><span class="kdate">2026-08-27</span><span class="ktitle">Claude in Chrome is generally available</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260819-mind-viruses/"><span class="kdate">2026-08-19</span><span class="ktitle">탈옥도, 인젝션도 없이 — 대화로만 퍼지는 에이전트의 '마인드 바이러스'</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260730/"><span class="kdate">2026-07-30</span><span class="ktitle">Anatomy of a Frontier Lab Agent Intrusion: A Tec…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260716/"><span class="kdate">2026-07-16</span><span class="ktitle">Dicklesworthstone/destructive_command_guard — 에이…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260715/"><span class="kdate">2026-07-15</span><span class="ktitle">Dicklesworthstone/destructive_command_guard — 에이…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260710/"><span class="kdate">2026-07-10</span><span class="ktitle">70개 MCP 서버 strace 런타임 감사 — 부팅 시 아웃바운드 호출 서버 적발</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260704/"><span class="kdate">2026-07-04</span><span class="ktitle">Cloudflare is about to block AI agents by defaul…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260703/"><span class="kdate">2026-07-03</span><span class="ktitle">Giving admins more visibility and control over C…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260630/"><span class="kdate">2026-06-30</span><span class="ktitle">Introducing the Claude apps gateway for Amazon B…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260625/"><span class="kdate">2026-06-25</span><span class="ktitle">Agent identity in Claude Tag: a new access model…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260624/"><span class="kdate">2026-06-24</span><span class="ktitle">Agent identity in Claude Tag: a new access model…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260614/"><span class="kdate">2026-06-14</span><span class="ktitle">NVIDIA/SkillSpector — Security scanner for AI ag…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260613/"><span class="kdate">2026-06-13</span><span class="ktitle">Fable 5's guardrails got bypassed in 48 hours — …</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260612/"><span class="kdate">2026-06-12</span><span class="ktitle">NVIDIA/SkillSpector — AI 에이전트 스킬용 보안 스캐너</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260607/"><span class="kdate">2026-06-07</span><span class="ktitle">OpenAI Help: Lockdown Mode</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260531/"><span class="kdate">2026-05-31</span><span class="ktitle">How we contain Claude across products</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260527/"><span class="kdate">2026-05-27</span><span class="ktitle">Microsoft Copilot Cowork Exfiltrates Files</span></a></li></ul></details><details class="ai-cat" open><summary><span class="catname">응용 사례</span><span class="catcount">6</span></summary><ul><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260726/"><span class="kdate">2026-07-26</span><span class="ktitle">citrolabs/ego-lite — 로그인된 브라우저 상태를 AI 에이전트와 공유하는…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260717/"><span class="kdate">2026-07-17</span><span class="ktitle">After a year building agent memory, 'save everyt…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260712/"><span class="kdate">2026-07-12</span><span class="ktitle">Do Automated Evals Work?</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260621/"><span class="kdate">2026-06-21</span><span class="ktitle">calesthio/OpenMontage — 12 파이프라인·52 도구·500+ 스킬을 …</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260609/"><span class="kdate">2026-06-09</span><span class="ktitle">Building intelligent apps for Apple platforms wi…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260514/"><span class="kdate">2026-05-14</span><span class="ktitle">Introducing Claude for Small Business</span></a></li></ul></details><details class="ai-cat" open><summary><span class="catname">산업 동향</span><span class="catcount">9</span></summary><ul><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260907-humanmade-52week-rhythm/"><span class="kdate">2026-09-07</span><span class="ktitle">휴먼 메이드의 '52주 리듬' — 아이디어가 흔해진 시대에 값이 오르는 건 버리는 판단</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260830/"><span class="kdate">2026-08-30</span><span class="ktitle">[AINews] OpenAI shuts off Cursor — 프론티어 모델 공급 차단…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260711/"><span class="kdate">2026-07-11</span><span class="ktitle">OpenAI says GPT 5.6 is the 'preferred model' for…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260702/"><span class="kdate">2026-07-02</span><span class="ktitle">How Cursor deploys AI inside the enterprise (For…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260616/"><span class="kdate">2026-06-16</span><span class="ktitle">Why AI hasn't replaced software engineers, and w…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260610/"><span class="kdate">2026-06-10</span><span class="ktitle">Fable 5 just made cost-aware model routing manda…</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260519/"><span class="kdate">2026-05-19</span><span class="ktitle">Anthropic acquires Stainless</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260515/"><span class="kdate">2026-05-15</span><span class="ktitle">Clawdmeter — Claude Code 사용량을 데스크톱 대시보드로</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260504/"><span class="kdate">2026-05-04</span><span class="ktitle">Agents for Everything Else: Codex for Knowledge …</span></a></li></ul></details></nav>
</aside>

<article class="ai-knowledge-article">

<header class="ai-post-hero">
  <p class="ai-eyebrow"><a class="ai-back" href="../">KNOWLEDGE</a> · 2026-09-07 · 리서치 노트</p>
  <h2 class="ai-post-title">VoiceMem — 좌뇌·우뇌로 쪼갠 스트리밍 메모리로 음성 에이전트 지연 없애기</h2>
</header>

음성 에이전트에 장기 기억을 붙이는 건 원리상 어렵지 않다. 대화를 텍스트로 받아 Mem0 같은 메모리 레이어에 넣고, 다음 턴에 검색해서 프롬프트에 끼워 넣으면 된다. 문제는 **그렇게 하면 대화가 아니게 된다**는 것이다. 사람이 말을 멈추고 상대가 입을 열기까지 자연스럽다고 느끼는 시간은 500ms 남짓인데, 메모리 검색에만 1.4초가 걸리면 그 예산은 이미 다 써버린 뒤다.

[VoiceMem](https://github.com/xzf-thu/VoiceMem)은 이 지점을 정면으로 잡은 오픈소스 메모리 인프라다. 기술 보고서([arXiv:2608.26005](https://arxiv.org/abs/2608.26005))의 첫 문장이 프로젝트 성격을 그대로 요약한다 — "duplex SLM 같은 대화 시스템에는 아직 스트리밍이면서 정확하고 공감할 줄 아는 메모리 시스템, 즉 **영혼**이 없다." 2026년 8월 공개 후 한 달도 안 돼 스타 800개를 넘겼고, Apache 2.0으로 "영구히 완전 오픈소스"임을 명시하고 있다.

## 좌뇌와 우뇌를 따로 둔다

VoiceMem의 구조적 선택은 이름 그대로다. 기억을 하나의 저장소에 밀어 넣지 않고 **두 개의 병렬 그래프**로 쪼갠다.

- **좌뇌 (Information Graph)** — 사실을 담당한다. 스키마(거친 의미 라우팅) → 엔티티(사람·사건·개념) 2단 계층으로 색인하고, 각 엔티티가 백엔드 메모리 아이템을 가리킨다. 흥미로운 건 **cluster emergence** 메커니즘인데, 카테고리를 규칙으로 미리 쪼개는 대신 "함께 검색되는 빈도"(query coherence)를 보고 하위 클러스터가 저절로 떠오르게 한다. 논문의 시각화에 따르면 저장된 항목의 **49.8%가 사전 정의 카테고리가 아니라 실제 질의 패턴에서 발생**했다.
- **우뇌 (Affect Graph)** — 성격과 감정을 담당한다. 노드가 두 종류다. *독립 노드*는 오래 누적된 근거로 뒷받침되는 지속적 기질(예: "스트레스를 받으면 남이 눈치채길 바란다")을, *교차 엔티티 노드*는 특정 좌뇌 엔티티에 묶인 상황적 감정을 담는다. 여기에 **이중 시간축 귀인**이 붙는다 — 짧은 축은 대화 중 즉각적 감정 맥락을 유지하고, 긴 축은 세션이 끝난 뒤 반복된 패턴을 안정적인 성격 속성으로 응결시킨다.

이 분리가 실제로 무슨 차이를 만드는지는 프로젝트 데모가 잘 보여준다. 사용자가 "요즘 너무 피곤해"라고만 말했는데, 우뇌에서 `Feels stressed (coping)` · `Self-denying mindset`을, 좌뇌에서 `지난 4월 알고리즘 중간고사에서 C를 받음`을 **함께** 끌어와 "지난 4월에 본 알고리즘 중간고사 때문인가요?"라고 되묻는다. 사실 검색만으로는 나오지 않고, 감정 태깅만으로도 나오지 않는 답이다.

## 왜 하필 좌뇌·우뇌인가

이 은유가 신경과학적 주장은 아니다. 논문 related work가 인용하는 건 Hickok & Poeppel(음성 처리의 병렬 경로)과 McGaugh(감정이 기억 공고화를 조절한다) 정도이고, **"왜 좌/우뇌 분할이 더 나은가"는 어디에도 논증되어 있지 않다.** 실제 주장은 더 수수하다 — 사실과 정서는 갱신 리듬이 다른데 기존 메모리 시스템은 둘을 같은 통에 넣는다는 것.

논문 제사가 플라톤이다. *"기억을 통해 영혼은 이전 존재의 흔적을 드러낸다."* 여기서 "soul"은 마케팅 단어가 아니라 논지 그 자체다. 상기설에서 영혼의 증거는 기억의 연속성이고, 저자들의 주장이 그대로 옮겨진다 — 음성 에이전트에 영혼이 없는 건 지능이 부족해서가 아니라 **매번 처음 만나기 때문**이다. 목표는 명시적으로 "지능적인 도구에서 인간 중심의 파트너로"인데, 도구는 기억할 필요가 없고 관계만이 기억을 요구한다.

메타포보다 **슬롯 스키마를 나란히 놓으면** 설계 의도가 더 선명하다.

| 좌뇌 7종 (`SlotV2`) | 우뇌 5종 (`rb_slots`) |
|---|---|
| work / finance / relationships | 감정 |
| health / goals | 표현 방식 |
| daily_life / knowledge | 사고 패턴 |
| | 대처 방식 |
| | 호오(好惡) |

좌뇌는 **인생의 영역**으로 나누고, 우뇌는 **사람의 됨됨이**로 나눈다. 좌뇌 슬롯이 *당신에게 무슨 일이 있었는가*의 분류라면 우뇌 슬롯은 *당신이 어떤 사람인가*의 분류다. 좌/우뇌보다 훨씬 정직하고 방어 가능한 축이다.

동사도 다르다. 좌뇌는 **정확히 유지한다**(중복 제거, 모순 supersede, 사실 병합). 우뇌는 **반복에서 응결시킨다**. `attribution_manager`가 이 설계의 심장인데, 단기 귀인은 3턴마다 엔티티 설명을 갱신하고 장기 귀인은 세션 경계에서 "이 방면에서 드러나는 인격 화상"을 만든다. 주석이 명토 박아 말한다 — *"단기 귀인은 추출이 아니라 공고화다. 누적된 상태를 읽는 것이지 방금 한 말과는 관계없다."* 사실은 한 번 들으면 알지만 성격은 여러 번 겹쳐야 보인다. 두 저장소를 나눈 진짜 이유는 좌/우뇌가 아니라 이 시간축이다.

### 코드에 박힌 가치 판단

이 저장소가 특이한 건 주석이 "무엇을 하는가"가 아니라 **"왜 이렇게 정했는가"를 계속 변호한다**는 점이다. 몇 개는 그대로 옮길 만하다.

- **감정은 인격의 총 스위치가 아니다.** *"원래 여기는 `if not emotion: return` 이었다 — 감정을 우뇌의 총 스위치로 삼은 것. 하지만 감정은 다섯 부류 중 하나일 뿐이다. 「남이 쩝쩝대며 먹는 게 싫다」는 호오고 「결정 전에 장단점을 적는다」는 사고 패턴인데 둘 다 감정이 안 잡힌다."* AI 컴패니언 제품이 흔히 저지르는 축소를 명시적으로 거부한다.
- **틀리게 아는 게 모르는 것보다 나쁘다.** *"잘못 태깅하는 게 태깅 안 하는 것보다 나쁘다 — 이 라벨은 사용자 자신의 말 옆에 찍힌다. 옛 데이터에서 「나 딸기 좋아해」가 【슬픔】으로 태깅된 게 이렇게 나왔다."*
- **공감이 사실을 덮어쓰면 안 된다.** 원문은 `content`에 그대로 두고 공감적 재서술(inner_os)은 metadata로 뺀다 — *"공감적 재서술이 숫자·이름·시간 같은 디테일을 지우는 걸 막기 위해."* 감정 레이어를 원문 위에 덮지 않고 옆에 붙이는 선택이다.
- **모르면 지어내지 않는다.** 소리만 들어왔을 때 *"음악이라고 인식됐거나 본인이 말했을 때만 '음악'이라 부르고, 아니면 사실대로 '한 토막의 소리'라고 쓴다 — 음악이라고 쓰는 건 지어내는 것이다."* 검색 때도 좌우뇌 모두 구체적 증거가 없으면 "증거 부족하면 모른다고 말하라"고 응답 모델에 명시적으로 지시한다.
- **최신성이 이해를 이기지 못하게 한다.** heartnote에 쿼터를 거는 이유 — *"방금 저장한 게 제일 세다. 연달아 세 마디 물으면 세 번째 답의 우뇌 칸이 전부 자기가 앞서 한 말로 찬다. 그 사람에 대한 판단은 하나도 못 낀다."*

### 은유가 치른 값

좌/우뇌 프레임이 한 좋은 일은 분명하다. 정서 쪽에 **독립된 검색 경로·독립된 쿼터·독립된 시간축**을 강제로 줬다. 감정을 사실에 붙는 태그로 취급했다면 나올 수 없는 설계고, ablation에서 우뇌 제거가 사실 정확도까지 6.3점 떨어뜨린 게 이 분리가 실질적이었다는 증거다.

대가는 **고정 분류의 경직성**이다. canonical 감정이 8종(불안/슬픔/억울/외로움/갈등/평온/기쁨/피곤)으로 못 박혀 있는데 여기 "좌절·분노" 버킷이 없다. 뇌 은유는 "감정은 유한한 종류"라는 인상을 주지만 실제로는 그냥 임의의 8개다. 한쪽에서는 "분류를 미리 정하지 말고 질의 패턴에서 떠오르게 하라"(cluster emergence)고 해놓고 감정만은 미리 못 박은 자기모순이기도 하다.

## 지연을 없애는 게 아니라 숨긴다

VoiceMem이 134ms를 만드는 방식은 검색을 빠르게 하는 것이 아니라 **사용자가 아직 말하고 있는 동안 검색을 시작하는 것**이다. 파이프라인이 4단계로 겹쳐 돈다.

| 구간 | 하는 일 |
|---|---|
| Listening (0–200ms) | 전사·엔티티/스키마 매칭·화자 식별을 스트리밍으로 추출 |
| Anticipation (200–400ms) | 침묵이 감지되면 질의를 임베딩하고 양쪽 그래프를 확장 (speculative prefetch) |
| Searching (400–500ms) | VAD 임계값 안에서 백엔드 검색 완료 |
| Generation | 검색된 기억을 얹어 응답 생성 |

전처리 자체도 전부 스트리밍이다 — Voice activity detection과 의미 기반 VAD로 발화를 자르고, 음성 인식·엔티티 추출·스키마 식별·**감정 인식·성문(voiceprint) 추출**·임베딩을 말하는 도중에 병렬로 뽑아 구조화해 쓴다. 결과적으로 메모리를 붙였는데도 대화 지연이 사실상 늘지 않는다.

## 숫자

같은 조건(GPT-4o-mini + text-embedding-3-small, 기본 K=5)에서 측정한 결과다.

| | VoiceMem | Mem0 | EverMemOS |
|---|---|---|---|
| LoCoMo 정확도 | **91.2%** | 61.68% | — |
| 중앙값 검색 지연 | **134ms** | 1,440ms | — |
| 쿼리당 메모리 토큰 | **~430** | 6,956 | 1,899 |

정확도가 30포인트 가까이 높은데 토큰은 1/16을 쓴다는 게 핵심이다. **top-5만 검색해서 baseline의 top-200을 이긴다** — 계층 색인이 그만큼 잘 좁힌다는 뜻이다. 성격 모델링(PersonaMem 69.44%)도 종합 점수 기준 4.29포인트 SOTA를 갱신했다.

Ablation이 설계 의도를 잘 드러낸다(LoCoMo 기준 하락폭): 상위 계층 색인 제거 −9.9, **우뇌 제거 −6.3**, cluster emergence 제거 −5.5, 이중 시간축 갱신 제거 −5.4, 결합 검색 제거 −2.6. 감정 그래프가 "감성적 부가기능"이 아니라 사실 정확도에도 6포인트를 기여한다는 게 눈에 띈다.

평가 벤치마크는 정보 기억(LoCoMo·LongMemEval·Memora), 성격 기억(ES-MemEval·PersonaMem·PersonaLens)에 더해 자체 제작한 **ChatMem-Bench**(316문항·53시간 오디오·14개 카테고리)를 쓴다. 오디오에 실제로 근거를 둔 기억 벤치마크로, 정보/성격/감정 귀인/준언어(paralinguistics)를 나눠 본다. 학습 데이터인 [ChatMem-400k](https://huggingface.co/datasets/zhifeixie/VoiceMem-ChatMem400k)도 함께 공개돼 있다.

## 써보려면

```bash
pip install voicemem
pip install "voicemem[slm]"          # Qwen 계열 SLM 연동 시
hf download zhifeixie/VoiceMem_Default_Models_Env --local-dir ./models
```

```python
from voicemem import VoiceMem

vm = VoiceMem(mode="normal", openai_key="api_xxx", top_k=5)
vm.warmup()
vm.ingest(audio="assets/input.wav")
result = vm.search("What are my dietary restrictions?")
```

Python 3.10+에, 스트리밍 ASR은 FunASR, VAD·화자 검증은 sherpa-onnx, 임베딩은 multilingual-e5를 쓴다. 기본 경로는 OpenAI Chat/TTS/Realtime API에 의존하지만, **백엔드 메모리 엔진이 교체 가능한 구조**라는 게 설계상 중요하다 — 논문은 기존 메모리 시스템 위에 VoiceMem 계층을 얹었을 때 Mem0가 +29.5포인트, LangMem이 +15.8포인트 올랐다고 보고한다. 즉 Mem0를 걷어내는 대신 그 위에 씌우는 사용법도 성립한다.

음성 모델 쪽은 Qwen2.5-Omni · Qwen3-Omni · Step-Audio2-Mini 계열을 지원하고, 파인튜닝된 체크포인트도 [HuggingFace에 공개](https://huggingface.co/zhifeixie/VoiceMem_MF_Qwen3_6_35B_A3B_Qlora)돼 있다.

## 직접 돌려봤다 — M4 맥, OpenAI 키 없이

읽고 넘기기엔 주장이 커서 실제로 세웠다. Apple Silicon 맥북에 `pip install voicemem` + 로컬 모델 3.1GB(ASR 1.4G, 감정 900M, 임베딩 486M, 장면 340M, 성문 38M, VAD 632K)를 받고, 클라우드 LLM 자리에는 OpenAI 호환 엔드포인트를 물려 Claude Haiku로 대체했다. 임베딩·slot·ASR·VAD·성문·감정이 전부 로컬이라 **바꿔 끼울 곳은 쓰기 측 사실 추출용 chat 모델 하나뿐**이었다.

시나리오는 위 데모를 영어로 재현하는 것으로 잡았다. 오디오 3건을 넣고("4월 알고리즘 중간고사에서 C를 받았다" / "다들한테 괜찮다고 하는데 사실 아니다, 남이 걱정하는 게 싫다" / "채식이고 견과 알레르기가 있다"), `"I'm so tired lately"`로 물었다.

**지연은 논문보다 좋았다.** 12회 측정 중앙값 **21.5ms**(최소 15.6, p90 24.4) — 논문의 134ms보다 6배 빠르다. 로컬 E5를 쓰면 검색 경로에 네트워크가 아예 끼지 않으니 남는 건 벡터 연산뿐이고, VAD 예산 500ms의 4%만 쓴다. 다만 이건 검색 단독 시간이고, 오디오 한 건 ingest 는 6~9초씩 걸린다 — 쓰기는 느리고 읽기는 빠른, 실시간 대화에 맞춘 비대칭이다.

**검색 품질도 실물이었다.** 같은 3건을 놓고 질의에 따라 순위가 정확히 뒤집힌다.

| 질의 | 좌뇌 1순위 | 우뇌 |
|---|---|---|
| "I'm so tired lately" | 4월 알고리즘 중간고사 C | `frustrated after intensive effort yields poor results` |
| "What are my dietary restrictions?" | 채식 + 견과 알레르기 | `vegetarian diet` |

우뇌가 저장한 내심 독백(inner_os)은 이 프로젝트가 뭘 노리는지 잘 보여준다 — "괜찮은 척한다"는 발화에 대해 *"they're exhausted from pretending everything's okay when it's really not—**that mask takes so much energy to keep up**"*를 남긴다. 사실이 아니라 가면을 유지하는 데 드는 비용을 기록하는 쪽이다.

### 다만 기본 설정으로는 세 군데서 조용히 실패한다

전부 예외를 던지지 않고 그냥 결과가 비는 종류라, 모르면 "논문이 과장"으로 결론 내리기 딱 좋다.

**① 기본 ASR이 중국어 전용이다.** `funasr-paraformer-zh-streaming` 이 영어를 음소 수프로 만든다 — "I got a C in my algorithms midterm back in April"이 `itta see inmythmsm back inrili`가 된다. 이 상태로는 오디오 3건 중 2건이 사실 0건으로 조용히 넘어간다(뭉개진 텍스트에서 사실 추출이 실패). `VOICEMEM_ASR=sherpa`로 bilingual zh-en zipformer를 쓰면 `I GOT A SEA IN MY ALGORITHMS MIDROOM BACK IN APRIL`까지 올라오고, 이 정도면 LLM이 복원한다. (참고로 `asr.py`에는 중·영을 다 받는 SenseVoice 기반 `Transcriber` 클래스가 정의돼 있지만 패키지 어디서도 호출되지 않는다.)

**② `flush()`를 부르지 않으면 우뇌 장기귀인이 영원히 안 돈다.** `orchestrator.py` 주석에 *"마지막 session은 다음 트리거가 없으므로 ingest 후 호출자가 반드시 Flush()를 한 번 명시적으로 불러야 한다"*고 적혀 있는데, README와 examples 어디에도 그 호출이 없다. 문서대로 따라 하면 우뇌가 비어 있는 게 정상 동작이 된다.

**③ 우뇌 판단표의 유사도 임계값이 중국어 기준으로 잡혀 있다.** 이게 제일 컸다. 코드는 임베딩 차원만 보고 문턱을 정한다 — 로컬 E5(384차원)면 **0.88**, OpenAI(1536차원)면 0.45. 0.88의 근거는 주석에 적힌 *"E5는 짧은 문장 유사도를 전반적으로 끌어올리고 범위를 좁힌다 — 노이즈도 0.86이 나온다"*는 관찰인데, 이건 중국어에서 측정한 값이다. 영어는 분포가 통째로 아래에 있다.

| | 실측 최고 유사도 |
|---|---|
| 관련 질의 4건 | 0.8266 / 0.8433 / 0.8545 / 0.8379 |
| 무관 질의 4건 | 0.7465 / 0.7948 / 0.7452 / 0.7499 |

관련 최저(0.8266)가 무관 최고(0.7948)보다 위라 **영어에서도 분리 자체는 잘 된다**. 문제는 문턱이 0.88이라 정답 최고점(0.8545)조차 잘린다는 것 — 즉 영어에서는 우뇌 판단표가 100% 차단된다. 스윕해 보면 0.80~0.82 구간에서 관련 4/4 통과·오탐 0/4로 깨끗하게 갈린다. `VOICEMEM_RB_TRAIT_MIN_SIM=0.81` 한 줄이면 위 표의 우뇌 결과가 나온다.

버그라기보다 캘리브레이션 미스에 가깝지만, 구조적으로 **차원만 보고 문턱을 정하므로 언어가 바뀐 걸 감지할 수단이 없다**는 게 핵심이다.

### 한국어

지원하지 않는다. `lang.py`가 `en`/`zh` 둘만 받고, 설계 의도가 *"기억 라이브러리는 한 가지 언어여야 한다 — 검색이 벡터 기반이라 혼용하면 절반이 검색되지 않는다"*로 명시돼 있다. 여기에 canonical 감정 8종(`焦虑/悲伤/委屈/孤独/纠结/平静/开心/疲惫`)이 중국어로 고정이고 "좌절/분노" 버킷이 아예 없어서, 영어 `frustrated`도 `委屈`(억울함)으로 강제 매핑된다. 한국어를 붙이려면 언어 스위치만이 아니라 ASR 모델·감정 버킷·임계값을 함께 손봐야 한다.

## 참고할 점

논문이 한계를 명시적으로 나열하진 않지만, 구조상 걸리는 지점은 몇 가지 읽힌다. 스키마 기반 라우팅이 **엔티티/개념 추출 품질에 그대로 종속**되고, 백엔드 이식 시 개선폭 편차가 크며(Mem0 +29.5 vs LangMem +15.8), 오디오 기억을 무엇까지 남길지(성문·음향 임베딩·원본 파형) 보존 정책이 열려 있다. ChatMem-Bench도 "상당한 사람 손"이 들어갔다고 적혀 있어 확장성 면에선 물음표가 남는다.

그럼에도 방향은 분명하다. 지난 1~2년 에이전트 메모리 논의가 "무엇을 저장할까"(save-everything의 실패)에서 "무엇을 검색할까"로 옮겨왔다면, VoiceMem은 여기에 **"언제 검색할까"**라는 축을 하나 더 얹었다. 실시간 대화라는 제약이 걸리는 순간 메모리는 저장·검색 문제가 아니라 스케줄링 문제가 된다는 관찰이 이 프로젝트의 실질적 기여다.

플라톤과 500ms가 만나는 지점도 거기다. **늦게 도착한 기억은 기억이 아니라 조회다.** 상대가 3초 생각한 뒤 "아 맞다, 4월에 시험 못 봤다고 했지"라고 하면 그건 기록을 뒤진 것이지 기억한 게 아니다. 사람이 "저 사람이 나를 안다"고 느끼는 건 내용이 맞아서가 아니라 즉시 나와서인데, 친밀함은 지연을 견디지 못한다. 그래서 이 시스템은 사용자가 아직 말하고 있는 동안 검색을 시작한다 — 사람도 상대 말이 끝나기 전에 이미 떠올리기 때문이다. 실측 21.5ms의 의미는 "빠르다"가 아니라 **기억하는 것처럼 느껴지는 영역에 들어왔다**는 쪽에 가깝다.

사족 하나. 데모 데이터의 인물이 "Jiaqi"인데 논문 2저자가 Jiaqi Lang이고 패키지 author도 같은 사람이다. 자기 삶(4월 알고리즘 시험 C, 채식, 견과 알레르기)을 데모로 썼다. 컴패니언 시스템을 만들면서 첫 사용자를 자기로 둔 셈인데, 위의 가치 판단들이 왜 그렇게 구체적인지 — "연달아 세 마디 물으면 우뇌 칸이 자기 말로 찬다" 같은 건 실제로 써보지 않으면 안 나오는 관찰이다 — 설명이 된다.

</article>

</div>

<!-- ai-related-links -->
<aside class="ai-related-links">
  <p class="ai-eyebrow">관련 학습</p>
  <ul><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260701/"><span class="kdate">2026-07-01</span><span class="ktitle">Google OKF (Open Knowledge Format) — 벤더 중립 에이전트 …</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260805/"><span class="kdate">2026-08-05</span><span class="ktitle">TencentCloud/TencentDB-Agent-Memory — 대화·문서·코드를 …</span></a></li><li><a href="https://altjs4510.github.io/ai_news_blog/knowledge/20260717/"><span class="kdate">2026-07-17</span><span class="ktitle">After a year building agent memory, 'save everyt…</span></a></li></ul>
</aside>
<!-- /ai-related-links -->
