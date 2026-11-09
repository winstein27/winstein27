# Winstein Martins

Backend engineer in Brasília, Brazil. I build and run 24/7 TypeScript and Node.js systems: real-time services, integrations between systems that were never meant to talk to each other, and the observability that keeps them up.

## Some of what I've built

- **Hefesto.** Lead developer of the 24/7 call platform behind the 190 and 193 emergency lines in Brazil's Federal District (about 1.8M calls a year): real-time call queues, telephony integration, a heartbeat so no emergency call waits at an empty desk, and an on-premises LLM assistant in the live workflow, with the dispatcher in control.
- **Gateway to Brazil's national dispatch system.** NestJS service with mTLS, OIDC, retries and structured logs, plus a client SDK generated from OpenAPI and checked in CI.
- **Incident data on crews' phones.** A progressive web app used by 1,000+ firefighters on the way to a call.
- **Shared platform.** The React component library used across the department's systems, with end-to-end tests in CI, and per-branch test environments that other projects adopted.
- **CONAT.** A system shared by two agencies to query police incidents (Next.js, NestJS, MongoDB, SQL Server).

These were built for government agencies, so the code is not public.

Before software, I was a firefighter.

## Working on in public

- **[RAG over public incident postmortems](https://github.com/winstein27/postmortem-rag)** (in progress). Queue-based ingestion with idempotent workers, hybrid search, answers with citations, and an automated evaluation that measures retrieval and answer quality.
- **[Backend katas, test-first](https://github.com/winstein27/backend-practice).** Small backend exercises in TypeScript, built red, green, refactor, one commit per step.

## Stack

TypeScript, Node.js, NestJS · PostgreSQL, SQL Server, MongoDB, Redis · REST, OpenAPI, Socket.IO · Docker, Kubernetes, GitLab CI · Grafana, Loki · LLM integration

## Contact

[LinkedIn](https://www.linkedin.com/in/winstein-martins)
