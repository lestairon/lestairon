# Fernando Nieto

**Backend Engineer · System Architecture · AI Pipelines**

5+ years building production systems in regulated (HIPAA) and high-availability environments. I specialize in billing workflows, event-driven architectures, data migrations, and background processing — and lately in building real AI pipelines that go beyond toy demos: async queues, semantic clustering, multi-source data collection, and multi-agent orchestration.

📍 Barranquilla, Colombia · [linkedin.com/in/fernandonieto9](https://linkedin.com/in/fernandonieto9) · fernandonietop9@gmail.com

---

## Projects

### [MIRA](https://github.com/lestairon/mira) — Market Intelligence Research Assistant
> Ask a question. Get structured insight from 7 sources at once.

MIRA helps indie founders and SaaS teams understand what real users are struggling with — without manually reading through Reddit threads, HN comments, and review sites.

You type a query like *"invoice automation pain points for freelancers"* and MIRA fans out to Reddit, Hacker News, IndieHackers, RSS feeds, G2, Trustpilot, and Product Hunt simultaneously. It runs each result through a multi-stage AI pipeline: per-item LLM extraction → Jina AI semantic embeddings → cosine-similarity clustering → synthesis report. Cross-source correlation is the key filter: a complaint that surfaces independently across Reddit, G2, and HN is a real signal; a single thread is just noise.

The whole pipeline runs async via BullMQ + Redis — long queries (25-50 items/source) don't block the API. One `docker compose up` brings up Postgres, Redis, the API, and a Svelte 5 dashboard.

Open-core: self-hosted under AGPL v3.0 · cloud tier for teams.

`TypeScript` `Node.js` `Hono` `Svelte 5` `PostgreSQL` `Redis` `BullMQ` `Jina AI`

---

### [DeepDiver](https://github.com/lestairon/deepdiver) — True Winrate Calculator
> Pre-computed game analytics. Never computed on-request.

Turborepo monorepo with dedicated packages for API, crawler, analyzer, Riot API client, rate limiter, and shared contracts. BullMQ pipelines batch all metric computation in the background; results are served from Redis on every request. File-based canonical memory keeps agent context lean across sessions.

`TypeScript` `Node.js` `Fastify` `React` `PostgreSQL` `Redis` `BullMQ` `Turborepo`

---

## Experience

| | |
|---|---|
| **Software Engineer** | Gorilla Logic · Healthcare (US) · *Mar 2024 – Oct 2025* |
| **Software Engineer** | Rootstrap · EdTech (US) · *Oct 2021 – Jun 2023* |
| **Software Engineer** | Ayenda · Hospitality · *Dec 2019 – Oct 2021* |

**Selected impact:**
- Reduced deployment time 76% (17 → 4 min) through CI/CD pipeline improvements
- Reduced infrastructure costs 17% via AWS ECS/EC2 right-sizing
- Supported a $2M+ B2B partnership by translating technical constraints for stakeholders

---

## Skills

**Languages:** Ruby · TypeScript · JavaScript · PHP

**Backend:** Ruby on Rails · Node.js · Deno · Laravel · REST · GraphQL

**AWS:** EC2 · ECS · S3 · Lambda · SQS · SNS · EventBridge · Step Functions · DynamoDB · CloudWatch

**Data:** PostgreSQL · MongoDB · Redis · Sidekiq · BullMQ · transactional migrations · caching

**AI:** multi-source LLM pipelines · semantic embeddings · BullMQ async queues · multi-agent orchestration · model routing · MCP servers

**DevOps:** Docker · Terraform · Semaphore · CircleCI · Jenkins

**Testing:** RSpec · Capybara · Jest · Testing Library · TDD/BDD

---

*Technical Degree in Computer Science, SENA (2018) · HIPAA Compliance Training*
