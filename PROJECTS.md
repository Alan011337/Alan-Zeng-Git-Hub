# Technical Project Portfolio

This page is a curated map of my public technical work. It is designed to make the evidence easier to inspect without overstating the scope of learning projects.

## 5-minute reviewer path

If you only have a few minutes, use this order:

1. [`chirpy`](https://github.com/Alan011337/chirpy) — inspect API structure, PostgreSQL persistence, authentication, refresh tokens, and webhooks.
2. [`build_an_ai_agent`](https://github.com/Alan011337/build_an_ai_agent) — inspect tool calling, function dispatch, bounded execution, and agent-loop concepts.
3. [Haven Product Portfolio](https://somber-tamarillo-df3.notion.site/Haven-AI-native-Product-Portfolio-3d8ad9856018811b96ffe8e33a7d48ef) — inspect how product ownership, requirements, QA, release-readiness, privacy, and safety connect to software and AI constraints.

**Intended conclusion:** I have inspectable technical fluency that supports product work close to AI and software execution. **Do not infer:** senior engineering depth, production-scale infrastructure ownership, or that I hand-coded Haven end-to-end.

## First-screen GitHub pin strategy

The GitHub profile does not need every available pin slot filled. Prefer **five high-signal, independently owned repositories** as the default first-screen set:

1. [`Alan-Zeng-Git-Hub`](https://github.com/Alan011337/Alan-Zeng-Git-Hub) — recruiter navigation and evidence boundaries.
2. [`chirpy`](https://github.com/Alan011337/chirpy) — API, authentication, persistence, and webhooks.
3. [`build_an_ai_agent`](https://github.com/Alan011337/build_an_ai_agent) — tool calling, bounded execution, and agent-loop reasoning.
4. [`Build_a_Blog_Aggregator_in_Go`](https://github.com/Alan011337/Build_a_Blog_Aggregator_in_Go) — persistent state, ingestion, and recurring backend work.
5. [`Build_a_Static_Site_Generator`](https://github.com/Alan011337/Build_a_Static_Site_Generator) — source-of-truth, derived artifacts, transformation pipeline, testing, and failure localization.

Do not fill a sixth slot merely for visual completeness. A sixth pin should be added only when another repository provides clearly stronger or genuinely different evidence.

`learn-pub-sub-starter` and `learn-file-storage-s3-golang-starter` remain useful systems-learning artifacts, but both are course forks. Their systems breadth is valuable inside this technical map; their provenance makes them weaker default first-screen proof than the non-fork projects above.

## Complementary proof map

The selected repositories are intentionally complementary rather than a technology-count portfolio. Each one should answer a different technical product question:

| Evidence surface | Primary reasoning surface | Product / TPM question it helps answer |
| --- | --- | --- |
| [`Alan-Zeng-Git-Hub`](https://github.com/Alan011337/Alan-Zeng-Git-Hub) | navigation + evidence boundaries | Can the reviewer quickly distinguish product evidence, implementation evidence, and learning provenance? |
| [`chirpy`](https://github.com/Alan011337/chirpy) | API · auth · persistence · webhooks | Can I reason about request flows, state, authorization, and backend-facing product constraints? |
| [`build_an_ai_agent`](https://github.com/Alan011337/build_an_ai_agent) | tool calling · bounded execution · failure-aware agent loops | Can I reason about AI systems as tools, boundaries, orchestration, and failure modes rather than only prompts? |
| [`Build_a_Blog_Aggregator_in_Go`](https://github.com/Alan011337/Build_a_Blog_Aggregator_in_Go) | ingestion · PostgreSQL · background state | Can I reason about persistent state and recurring ingestion work beyond a single request/response? |
| [`Build_a_Static_Site_Generator`](https://github.com/Alan011337/Build_a_Static_Site_Generator) | source → transform → template → generated artifact | Can I reason about source-of-truth, derived state, repeatable builds, tests, and failure localization? |

### Supporting systems evidence

| Evidence surface | Primary reasoning surface | Why it remains supporting rather than a default pin |
| --- | --- | --- |
| [`learn-pub-sub-starter`](https://github.com/Alan011337/learn-pub-sub-starter) | asynchronous messaging · routing · consumers | Useful RabbitMQ/event-flow practice, but it is explicitly a Boot.dev course fork. |
| [`learn-file-storage-s3-golang-starter`](https://github.com/Alan011337/learn-file-storage-s3-golang-starter) | object storage · media lifecycle · CDN delivery | Useful S3/CloudFront/storage practice, but it is explicitly a Boot.dev course fork. |

The point is **coverage of distinct reasoning surfaces with credible provenance**, not breadth for its own sake. If a repository does not add a new hiring-relevant question, stronger evidence, or cleaner provenance, it should not be promoted into the default reviewer path.

## Start here by hiring lens

### AI Product Manager
Use the repositories to verify technical fluency, then return to the product context in the [Haven Product Portfolio](https://somber-tamarillo-df3.notion.site/Haven-AI-native-Product-Portfolio-3d8ad9856018811b96ffe8e33a7d48ef).

Recommended path:
1. [`build_an_ai_agent`](https://github.com/Alan011337/build_an_ai_agent) — AI-agent/tool-calling concepts.
2. [`chirpy`](https://github.com/Alan011337/chirpy) — APIs, persistence, auth, and backend flows.
3. Haven Portfolio — how technical constraints connect back to product decisions.

### Technical Product Manager
Recommended path:
1. [`chirpy`](https://github.com/Alan011337/chirpy) — HTTP API, PostgreSQL, JWT / refresh tokens, webhooks.
2. [`Build_a_Blog_Aggregator_in_Go`](https://github.com/Alan011337/Build_a_Blog_Aggregator_in_Go) — persistence, RSS ingestion, CLI/backend state.
3. [`Build_a_Static_Site_Generator`](https://github.com/Alan011337/Build_a_Static_Site_Generator) — canonical source vs. generated state, transformation pipeline, testing.
4. Use the RabbitMQ / S3 course forks only when the hiring conversation specifically benefits from messaging or storage-system examples.

### Product / technical generalist
Recommended path:
1. [`build_an_ai_agent`](https://github.com/Alan011337/build_an_ai_agent) — AI/tool orchestration.
2. [`chirpy`](https://github.com/Alan011337/chirpy) — API/auth/persistence.
3. [`Build_a_Blog_Aggregator_in_Go`](https://github.com/Alan011337/Build_a_Blog_Aggregator_in_Go) — ingestion/state/background work.
4. [`Build_a_Static_Site_Generator`](https://github.com/Alan011337/Build_a_Static_Site_Generator) — transformation/build pipeline.

The goal is not to inspect every repository. It is to see enough implementation evidence to judge whether I can reason clearly about technical constraints, interfaces, data flow, and trade-offs.

## Primary implementation evidence

### [`chirpy`](https://github.com/Alan011337/chirpy)
**Signal:** backend/API fluency

Go HTTP API project covering PostgreSQL persistence, authentication, refresh tokens, webhooks, and API design.

Use this repository when evaluating my ability to discuss backend concepts, request/response flows, persistence, authentication, and implementation trade-offs.

---

### [`build_an_ai_agent`](https://github.com/Alan011337/build_an_ai_agent)
**Signal:** AI-agent implementation fluency

Python tool-calling agent project using Gemini function calling to inspect files, read/write content, and run Python inside a bounded working directory.

Use this repository when evaluating my understanding of agent loops, tool schemas, function dispatch, bounded execution, and failure-aware AI workflows.

---

### [`Build_a_Blog_Aggregator_in_Go`](https://github.com/Alan011337/Build_a_Blog_Aggregator_in_Go)
**Signal:** ingestion, persistence, and recurring backend state

Go + PostgreSQL learning project centered on feed aggregation, persisted user/feed/post state, database interaction, and recurring ingestion workflows.

Use this repository when evaluating my ability to reason about durable state, external data, background work, freshness, and failure boundaries.

---

### [`Build_a_Static_Site_Generator`](https://github.com/Alan011337/Build_a_Static_Site_Generator)
**Signal:** source-of-truth and transformation-pipeline reasoning

Python learning project that separates source content, parsing/transformation logic, templates, generated output, build scripts, and tests.

Use this repository when evaluating my ability to reason about canonical inputs versus derived artifacts, reproducible pipelines, testing boundaries, and failure localization.

## Supporting systems learning

### [`learn-pub-sub-starter`](https://github.com/Alan011337/learn-pub-sub-starter)
**Signal:** asynchronous messaging concepts

Go + RabbitMQ course fork covering publish/subscribe, direct/topic exchanges, routing keys, client/server structure, and event-driven communication.

### [`learn-file-storage-s3-golang-starter`](https://github.com/Alan011337/learn-file-storage-s3-golang-starter)
**Signal:** file-delivery and cloud-storage architecture concepts

Go course fork covering S3 object storage, CloudFront/CDN concepts, file serving, FFmpeg/FFprobe, SQLite, and AWS tooling.

## Evidence matrix

| Project | Primary technical signal | Best recruiter question it helps answer | Evidence class |
| --- | --- | --- | --- |
| `chirpy` | API / backend / auth / persistence | Can you reason about backend product constraints? | Learning + implementation |
| `build_an_ai_agent` | tool calling / agent loop / bounded execution | Do you understand AI-agent workflows beyond prompting? | Learning + implementation |
| `Build_a_Blog_Aggregator_in_Go` | Go / PostgreSQL / ingestion / state | Can you discuss persistence and recurring backend state? | Learning + implementation |
| `Build_a_Static_Site_Generator` | source / transformation / generated state / testing | Can you reason about canonical inputs, derived artifacts, and failure localization? | Learning + implementation |
| `learn-pub-sub-starter` | RabbitMQ / asynchronous messaging | Do you understand event-driven communication concepts? | Supporting course-fork evidence |
| `learn-file-storage-s3-golang-starter` | S3 / CDN / file delivery | Can you discuss storage and delivery architecture at a foundational level? | Supporting course-fork evidence |

## What to inspect — and what not to infer

| Evidence | Reasonable inference | Do not infer |
| --- | --- | --- |
| Go API / PostgreSQL projects | familiarity with HTTP, persistence, auth, data flow, backend trade-offs | production ownership at scale |
| AI-agent project | familiarity with function calling, tool schemas, dispatch, bounded execution | production agent-platform expertise |
| Static-site generator | familiarity with source/transformation/rendering boundaries and basic testing discipline | production CMS/frontend-platform expertise |
| RabbitMQ / S3 / CloudFront course forks | foundational systems vocabulary and implementation exposure | distributed-systems or cloud-architecture expertise |
| Haven + repositories together | ability to connect product requirements with technical constraints and QA | sole hand-coding of the entire Haven implementation |

## Supporting learning repositories

Other repositories on this account include projects from freeCodeCamp, Boot.dev, Full Stack Open, and other computer-science learning tracks. They are intentionally not presented as equivalent to production engineering experience.

## How to interpret this portfolio

My target is not to claim senior software-engineering depth. I am building the technical fluency needed to work effectively at the intersection of **users, product, AI, and technical execution**.

The strongest interpretation of these repositories is:

- I learn by building and inspecting real implementation artifacts.
- I can discuss software and AI concepts beyond surface-level product terminology.
- I am increasingly able to reason about constraints, interfaces, data flow, architecture, testing, and trade-offs.
- I distinguish coursework and learning evidence from production-scale engineering claims.

## Evidence boundary

These repositories are strongest as **inspectable learning and implementation evidence**. They do not by themselves prove production-scale reliability, large-team engineering ownership, or senior infrastructure expertise. For product ownership and 0→1 product-system evidence, use Haven as the primary source.

For product ownership and 0→1 product evidence, see the [Haven Product Portfolio](https://somber-tamarillo-df3.notion.site/Haven-AI-native-Product-Portfolio-3d8ad9856018811b96ffe8e33a7d48ef).
