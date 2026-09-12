# Technical Project Portfolio

This page is a curated map of my public technical work. It is designed to make the evidence easier to inspect without overstating the scope of learning projects.

## 5-minute reviewer path

If you only have a few minutes, use this order:

1. [`chirpy`](https://github.com/Alan011337/chirpy) — inspect API structure, PostgreSQL persistence, authentication, refresh tokens, and webhooks.
2. [`build_an_ai_agent`](https://github.com/Alan011337/build_an_ai_agent) — inspect tool calling, function dispatch, bounded execution, and agent-loop concepts.
3. [Haven Product Portfolio](https://somber-tamarillo-df3.notion.site/Haven-AI-native-Product-Portfolio-3d8ad9856018811b96ffe8e33a7d48ef) — inspect how product ownership, requirements, QA, release-readiness, privacy, and safety connect to software and AI constraints.

**Intended conclusion:** I have inspectable technical fluency that supports product work close to AI and software execution. **Do not infer:** senior engineering depth, production-scale infrastructure ownership, or that I hand-coded Haven end-to-end.

## Complementary proof map

The selected repositories are intentionally complementary rather than a technology-count portfolio. Each one should answer a different technical product question:

| Evidence surface | Primary reasoning surface | Product / TPM question it helps answer |
| --- | --- | --- |
| [`Alan-Zeng-Git-Hub`](https://github.com/Alan011337/Alan-Zeng-Git-Hub) | navigation + evidence boundaries | Can the reviewer quickly distinguish product evidence, implementation evidence, and learning provenance? |
| [`chirpy`](https://github.com/Alan011337/chirpy) | API · auth · persistence · webhooks | Can I reason about request flows, state, authorization, and backend-facing product constraints? |
| [`build_an_ai_agent`](https://github.com/Alan011337/build_an_ai_agent) | tool calling · bounded execution · failure-aware agent loops | Can I reason about AI systems as tools, boundaries, orchestration, and failure modes rather than only prompts? |
| [`Build_a_Blog_Aggregator_in_Go`](https://github.com/Alan011337/Build_a_Blog_Aggregator_in_Go) | ingestion · PostgreSQL · background state | Can I reason about persistent state and recurring ingestion work beyond a single request/response? |
| [`learn-pub-sub-starter`](https://github.com/Alan011337/learn-pub-sub-starter) | asynchronous messaging · routing · consumers | Can I reason about decoupling, event flow, delivery risk, retries, and idempotency requirements? |
| [`learn-file-storage-s3-golang-starter`](https://github.com/Alan011337/learn-file-storage-s3-golang-starter) | object storage · media lifecycle · CDN delivery | Can I reason about metadata, file bytes, processing, permissions, caching, and lifecycle consistency? |

The point is **coverage of distinct reasoning surfaces**, not breadth for its own sake. If a repository does not add a new hiring-relevant question or stronger evidence, it should not be promoted into the default reviewer path.

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
3. [`learn-pub-sub-starter`](https://github.com/Alan011337/learn-pub-sub-starter) — RabbitMQ and event-driven messaging.
4. [`learn-file-storage-s3-golang-starter`](https://github.com/Alan011337/learn-file-storage-s3-golang-starter) — file storage, S3, CloudFront, media delivery.

### Product / technical generalist
Recommended path:
1. [`build_an_ai_agent`](https://github.com/Alan011337/build_an_ai_agent) — AI/tool orchestration.
2. [`chirpy`](https://github.com/Alan011337/chirpy) — API/auth/persistence.
3. [`Build_a_Blog_Aggregator_in_Go`](https://github.com/Alan011337/Build_a_Blog_Aggregator_in_Go) — ingestion/state/background work.

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

### [`learn-pub-sub-starter`](https://github.com/Alan011337/learn-pub-sub-starter)
**Signal:** asynchronous messaging concepts

Go + RabbitMQ course project covering publish/subscribe, direct/topic exchanges, routing keys, client/server structure, and event-driven communication.

Use this repository when evaluating my ability to discuss decoupling, asynchronous delivery, routing, retry/idempotency requirements, and failure propagation at a foundational level.

---

### [`learn-file-storage-s3-golang-starter`](https://github.com/Alan011337/learn-file-storage-s3-golang-starter)
**Signal:** file-delivery and cloud-storage architecture concepts

Go course project covering S3 object storage, CloudFront/CDN concepts, file serving, FFmpeg/FFprobe, SQLite, and AWS tooling.

Use this repository when evaluating my ability to reason about metadata versus file bytes, storage lifecycle, permissions, caching, delivery, and product-facing media constraints.

## Evidence matrix

| Project | Primary technical signal | Best recruiter question it helps answer | Evidence class |
| --- | --- | --- | --- |
| `chirpy` | API / backend / auth / persistence | Can you reason about backend product constraints? | Learning + implementation |
| `build_an_ai_agent` | tool calling / agent loop / bounded execution | Do you understand AI-agent workflows beyond prompting? | Learning + implementation |
| `Build_a_Blog_Aggregator_in_Go` | Go / PostgreSQL / ingestion / state | Can you discuss persistence and recurring backend state? | Learning + implementation |
| `learn-pub-sub-starter` | RabbitMQ / asynchronous messaging | Do you understand event-driven communication concepts? | Learning + implementation |
| `learn-file-storage-s3-golang-starter` | S3 / CDN / file delivery | Can you discuss storage and delivery architecture at a foundational level? | Learning + implementation |

## What to inspect — and what not to infer

| Evidence | Reasonable inference | Do not infer |
| --- | --- | --- |
| Go API / PostgreSQL projects | familiarity with HTTP, persistence, auth, data flow, backend trade-offs | production ownership at scale |
| AI-agent project | familiarity with function calling, tool schemas, dispatch, bounded execution | production agent-platform expertise |
| RabbitMQ / S3 / CloudFront projects | foundational systems vocabulary and implementation exposure | distributed-systems or cloud-architecture expertise |
| Haven + repositories together | ability to connect product requirements with technical constraints and QA | sole hand-coding of the entire Haven implementation |

## Supporting learning repositories

Supporting projects such as [`Build_a_Static_Site_Generator`](https://github.com/Alan011337/Build_a_Static_Site_Generator), plus other freeCodeCamp, Boot.dev, Full Stack Open, and computer-science learning repositories, remain useful evidence of learning and implementation practice. They are intentionally not promoted into the default reviewer path when another repository answers a more distinct hiring-relevant question.

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
