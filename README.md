<a href="https://github.com/lestairon">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=FF2D2D&height=230&section=header&text=FERNANDO%20NIETO&fontSize=96&fontColor=0A0A0A&fontAlign=50&fontAlignY=46&desc=BACKEND%20%E2%98%85%20SYSTEM%20ARCHITECTURE%20%E2%98%85%20AI%20PIPELINES&descSize=22&descAlignY=76&animation=fadeIn" alt="Fernando Nieto — Backend · System Architecture · AI Pipelines" />
</a>

<p align="center">
  Backend engineer with <b>5+ years</b> of production systems in HIPAA-regulated, high-availability environments.<br/>
  Billing workflows, event-driven architectures, data migrations, background processing.<br/>
  Lately: <b>AI pipelines that go beyond toy demos.</b>
</p>

<p align="center">
  <b><a href="mailto:fernandonietop9@gmail.com">→ EMAIL</a></b> &nbsp;■&nbsp;
  <b><a href="https://linkedin.com/in/fernandonieto9">↗ LINKEDIN</a></b> &nbsp;■&nbsp;
  <b>● BARRANQUILLA, CO</b>
</p>

## `// 01` &nbsp; [MIRA ↗](https://github.com/mira-js) &nbsp;<sub>MARKET INTELLIGENCE FOR FOUNDERS AND PRODUCT TEAMS</sub>

> **Ask a question about a market. Get a report where every claim links back to its source.**

Ask *"what do people hate about X"* and Mira turns it into a research plan, pulls public discussion from **Reddit, Hacker News, Indie Hackers, RSS/news, Trustpilot and G2**, and runs an LLM pipeline over it. Out comes themes, pain points, competitor weaknesses, sentiment, an executive summary and recommended actions.

`INVITE-ONLY PRE-RELEASE` `AGPL-3.0 OPEN CORE` &nbsp;·&nbsp; `TypeScript` `Hono` `Svelte 5` `PostgreSQL` `Redis`

**The fun part is how it's built.** Every ticket runs through a multi-agent pipeline I designed, with a human approval gate between each stage:

```mermaid
flowchart LR
  P[PLANNER]:::red -->|gate| A[ARCHITECT]:::red -->|gate| T[TEST-WRITER<br/>failing tests first]:::blue -->|gate| I[IMPLEMENTER]:::red -->|gate| R[REVIEWER]:::red
  classDef red fill:#FF2D2D,stroke:#FF2D2D,stroke-width:2px,color:#0A0A0A,font-weight:bold
  classDef blue fill:#2D5BFF,stroke:#2D5BFF,stroke-width:2px,color:#FFFFFF,font-weight:bold
```

Hooks block any commit that adds test failures. Test-tampering checks stop the implementer from editing the tests. ~20 ADRs, versioned prompts with an eval harness, and a run ledger that scores every agent's cost and cache-hit rate per ticket.

## `// 02` &nbsp; DEEPDIVER &nbsp;<sub>TRUE WINRATE CALCULATOR · <code>PRIVATE FOR NOW</code></sub>

> **Pre-computed game analytics. Never computed on-request.**

Turborepo monorepo (API, crawler, analyzer, Riot API client, rate limiter). BullMQ batches every metric in the background; Redis serves every request.

## `// 03` &nbsp; TRACK RECORD

<table>
<tr>
<td align="center" width="33%"><h1>−76%</h1><b>DEPLOY TIME</b><br/><sub>17 → 4 min via CI/CD</sub></td>
<td align="center" width="33%"><h1>−17%</h1><b>INFRA COSTS</b><br/><sub>AWS ECS/EC2 right-sizing</sub></td>
<td align="center" width="33%"><h1>$2M+</h1><b>B2B PARTNERSHIP</b><br/><sub>tech constraints → stakeholder language</sub></td>
</tr>
</table>

**Gorilla Logic** · Healthcare (US) · `2024–2025` &nbsp;■&nbsp; **Rootstrap** · EdTech (US) · `2021–2023` &nbsp;■&nbsp; **Ayenda** · Hospitality · `2019–2021`

## `// 04` &nbsp; STACK

`Ruby on Rails` `TypeScript` `Node.js` `PostgreSQL` `Redis` `BullMQ` `AWS` `Docker` `Terraform`

<details>
<summary><b>THE FULL ARSENAL ↓</b></summary>

**Languages** Ruby · TypeScript · JavaScript · PHP
**Backend** Rails · Node.js · Deno · Laravel · REST · GraphQL
**AWS** EC2 · ECS · S3 · Lambda · SQS · SNS · EventBridge · Step Functions · DynamoDB · CloudWatch
**Data** PostgreSQL · MongoDB · Redis · Sidekiq · BullMQ · transactional migrations · caching
**AI** multi-source LLM pipelines · semantic embeddings · multi-agent orchestration · model routing · MCP servers
**DevOps** Docker · Terraform · Semaphore · CircleCI · Jenkins
**Testing** RSpec · Capybara · Jest · Testing Library · TDD/BDD
</details>

<p align="center"><sub>TECHNICAL DEGREE IN COMPUTER SCIENCE, SENA (2018) &nbsp;■&nbsp; HIPAA COMPLIANCE TRAINING</sub></p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=FF2D2D&height=14&section=footer" />
