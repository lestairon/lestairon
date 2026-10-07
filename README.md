<a href="https://github.com/lestairon">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=FF2D2D&height=230&section=header&text=FERNANDO%20NIETO&fontSize=96&fontColor=0A0A0A&fontAlign=50&fontAlignY=46&desc=BACKEND%20%E2%98%85%20SYSTEM%20ARCHITECTURE%20%E2%98%85%20AI%20PIPELINES&descSize=22&descAlignY=76&animation=fadeIn" alt="Fernando Nieto — Backend · System Architecture · AI Pipelines" />
</a>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Archivo+Black&size=30&duration=2200&pause=700&color=0A0A0A&background=E8FF00&center=true&vCenter=true&width=880&height=60&lines=I+BUILD+SYSTEMS+THAT+DON'T+FLINCH.;BILLING.+EVENTS.+MIGRATIONS.+QUEUES.;AI+PIPELINES+BEYOND+TOY+DEMOS." alt="I build systems that don't flinch" />
</p>

<p align="center">
  <a href="mailto:fernandonietop9@gmail.com"><img src="https://img.shields.io/badge/→_EMAIL-FF2D2D?style=for-the-badge&logo=gmail&logoColor=0A0A0A" /></a>
  <a href="https://linkedin.com/in/fernandonieto9"><img src="https://img.shields.io/badge/↗_LINKEDIN-2D5BFF?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/●_BARRANQUILLA,_CO-E8FF00?style=for-the-badge&labelColor=0A0A0A" />
</p>

<p align="center">
  Backend engineer with <b>5+ years</b> of production systems in HIPAA-regulated, high-availability environments.<br/>
  Billing workflows, event-driven architectures, data migrations, background processing.<br/>
  Lately: <b>AI pipelines that go beyond toy demos.</b>
</p>

## `// 01` &nbsp; [MIRA ↗](https://github.com/mira-js) &nbsp;<sub>MARKET INTELLIGENCE FOR FOUNDERS AND PRODUCT TEAMS</sub>

> **Ask a question about a market. Get a report where every claim links back to its source.**

Ask *"what do people hate about X"* and Mira turns it into a research plan, pulls public discussion from **Reddit, Hacker News, Indie Hackers, RSS/news, Trustpilot and G2**, and runs an LLM pipeline over it. Out comes themes, pain points, competitor weaknesses, sentiment, an executive summary and recommended actions.

<img src="https://img.shields.io/badge/STATUS-INVITE--ONLY_PRE--RELEASE-E8FF00?style=flat-square&labelColor=0A0A0A" /> <img src="https://img.shields.io/badge/OPEN_CORE-AGPL--3.0-19E68C?style=flat-square&labelColor=0A0A0A" /> <img src="https://img.shields.io/badge/STACK-TS_·_HONO_·_SVELTE_5_·_POSTGRES_·_REDIS-2D5BFF?style=flat-square&labelColor=0A0A0A" />

**The fun part is how it's built.** Every ticket runs through a multi-agent pipeline I designed, with a human approval gate between each stage:

```mermaid
flowchart LR
  P[PLANNER]:::red -->|gate| A[ARCHITECT]:::acid -->|gate| T[TEST-WRITER<br/>failing tests first]:::blue -->|gate| I[IMPLEMENTER]:::acid -->|gate| R[REVIEWER]:::red
  classDef red fill:#FF2D2D,stroke:#0A0A0A,stroke-width:3px,color:#0A0A0A
  classDef acid fill:#E8FF00,stroke:#0A0A0A,stroke-width:3px,color:#0A0A0A
  classDef blue fill:#2D5BFF,stroke:#0A0A0A,stroke-width:3px,color:#FFFDF7
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

<p>
  <img src="https://img.shields.io/badge/RUBY_ON_RAILS-FF2D2D?style=for-the-badge&logo=rubyonrails&logoColor=0A0A0A" />
  <img src="https://img.shields.io/badge/TYPESCRIPT-2D5BFF?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/NODE.JS-0A0A0A?style=for-the-badge&logo=nodedotjs&logoColor=E8FF00" />
  <img src="https://img.shields.io/badge/POSTGRESQL-E8FF00?style=for-the-badge&logo=postgresql&logoColor=0A0A0A" />
  <img src="https://img.shields.io/badge/REDIS-FF2D2D?style=for-the-badge&logo=redis&logoColor=0A0A0A" />
  <img src="https://img.shields.io/badge/AWS-0A0A0A?style=for-the-badge&logoColor=E8FF00" />
  <img src="https://img.shields.io/badge/DOCKER-2D5BFF?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/TERRAFORM-E8FF00?style=for-the-badge&logo=terraform&logoColor=0A0A0A" />
</p>

<details>
<summary><b>▓▓ THE FULL ARSENAL ▓▓</b></summary>

**Languages** Ruby · TypeScript · JavaScript · PHP
**Backend** Rails · Node.js · Deno · Laravel · REST · GraphQL
**AWS** EC2 · ECS · S3 · Lambda · SQS · SNS · EventBridge · Step Functions · DynamoDB · CloudWatch
**Data** PostgreSQL · MongoDB · Redis · Sidekiq · BullMQ · transactional migrations · caching
**AI** multi-source LLM pipelines · semantic embeddings · multi-agent orchestration · model routing · MCP servers
**DevOps** Docker · Terraform · Semaphore · CircleCI · Jenkins
**Testing** RSpec · Capybara · Jest · Testing Library · TDD/BDD
</details>

<p align="center"><sub>★ TECHNICAL DEGREE IN COMPUTER SCIENCE, SENA (2018) ★ HIPAA COMPLIANCE TRAINING ★</sub></p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=FF2D2D&height=14&section=footer" />
