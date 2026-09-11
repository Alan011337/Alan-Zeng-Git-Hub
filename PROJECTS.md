# Technical Project Portfolio

This page is a curated map of my public technical work. It is designed to make the evidence easier to inspect without overstating the scope of learning projects.

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
1. [`build_an_ai_agent`](https://github.com/Alan011337/build_an_ai_agent)
2. [`chirpy`](https://github.com/Alan011337/chirpy)
3. [`Build_a_Static_Site_Generator`](https://github.com/Alan011337/Build_a_Static_Site_Generator)

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
**Signal:** Go + PostgreSQL + CLI/backend learning

Learning project centered on feed aggregation, persistence, database interaction, and backend/CLI concepts.

---

### [`Build_a_Static_Site_Generator`](https://github.com/Alan011337/Build_a_Static_Site_Generator)
**Signal:** Python program structure and content-transformation pipeline

Learning project that converts structured source content into generated static pages.

## Recent backend-systems learning

### [`learn-pub-sub-starter`](https://github.com/Alan011337/learn-pub-sub-starter)
**Signal:** asynchronous messaging concepts

Go + RabbitMQ course project covering publish/subscribe, direct/topic exchanges, routing keys, client/server structure, and event-driven communication.

### [`learn-file-storage-s3-golang-starter`](https://github.com/Alan011337/learn-file-storage-s3-golang-starter)
**Signal:** file-delivery and cloud-storage architecture concepts

Go course project covering S3 object storage, CloudFront/CDN concepts, file serving, FFmpeg/FFprobe, SQLite, and AWS tooling.

## Evidence matrix

| Project | Primary technical signal | Best recruiter question it helps answer | Evidence class |
| --- | --- | --- | --- |
| `chirpy` | API / backend / auth / persistence | Can you reason about backend product constraints? | Learning + implementation |
| `build_an_ai_agent` | tool calling / agent loop / bounded execution | Do you understand AI-agent workflows beyond prompting? | Learning + implementation |
| `Build_a_Blog_Aggregator_in_Go` | Go / PostgreSQL / ingestion / state | Can you discuss persistence and backend state? | Learning + implementation |
| `Build_a_Static_Site_Generator` | Python structure / transformation pipeline | Can you structure and explain a software project? | Learning + implementation |
| `learn-pub-sub-starter` | RabbitMQ / asynchronous messaging | Do you understand event-driven communication concepts? | Learning + implementation |
| `learn-file-storage-s3-golang-starter` | S3 / CDN / file delivery | Can you discuss storage and delivery architecture at a foundational level? | Learning + implementation |

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
