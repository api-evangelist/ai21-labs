# AI21 Labs

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AI21 Labs is an enterprise foundation-model company best known for the Jamba family of open-weight hybrid Mamba/Transformer models and AI21 Maestro, a dynamic planning system that orchestrates tools, retrieval, and validated output during inference. The platform exposes a Bearer-token REST API at api.ai21.com covering chat completions, conversational RAG over a managed file library, batch processing, fine-tuning, and function calling. Official Python and TypeScript SDKs wrap the API with sync and async clients and integrate natively into LangChain and LlamaIndex. Jamba weights are also published on Hugging Face for self-hosted vLLM deployment.

**Areas:** Artificial Intelligence · Foundation Models · LLM · Jamba · Mamba · RAG · Agents · Maestro · Inference · Enterprise AI · Fine-Tuning

## AI21 Labs on APIs.io

Everything profiled for AI21 Labs is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ai21-labs/](https://apis.io/providers/ai21-labs/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [AI21 Jamba Chat Completions API](https://apis.io/apis/ai21-labs/chat-completions/) — Conversational completions endpoint backed by the Jamba family of hybrid Mamba/Transformer models (Jamba 1.5 Mini, Jamba 1.5 Large, Jamba 1.6). Accepts a…
- [AI21 Maestro API](https://apis.io/apis/ai21-labs/maestro/) — Dynamic planning system that, at inference time, determines the optimal sequence of actions to solve a task. Exposes run creation and retrieval endpoints,…
- [AI21 File Library API](https://apis.io/apis/ai21-labs/library/) — Managed file storage for RAG workflows. Upload, list, retrieve, update, and delete documents that Maestro and Jamba endpoints can ground on at inference time.
- [AI21 Batch API](https://apis.io/apis/ai21-labs/batch/) — Asynchronous batch processing for large volumes of Jamba completions. Submit a batch job, poll for status, and download results when the run completes.
- [AI21 Fine-Tuning API](https://apis.io/apis/ai21-labs/fine-tuning/) — Fine-tuning service for Jamba models supporting full, LoRA, and QLoRA strategies. Create training jobs from uploaded datasets and deploy the resulting model…
- [AI21 Python SDK](https://apis.io/apis/ai21-labs/python-sdk/) — Official Python SDK (ai21 on PyPI) wrapping the AI21 Studio REST API with sync and async clients, streaming support, LangChain / LlamaIndex integrations,…
- [AI21 TypeScript / JavaScript SDK](https://apis.io/apis/ai21-labs/typescript-sdk/) — Official TypeScript and JavaScript client for the AI21 Studio API, with typed request and response models and streaming helpers for browser and Node.js…
- [AI21 Jamba on Hugging Face](https://apis.io/apis/ai21-labs/huggingface/) — Open-weight releases of the Jamba family on Hugging Face for self-hosted inference via vLLM, Transformers, and other runtimes.
- [AI21 Labs Library API](https://apis.io/apis/ai21-labs/ai21-labs-library-api/) — The Library API from AI21 Labs — 1 operation(s) for library.
- [AI21 Labs Maestro API](https://apis.io/apis/ai21-labs/ai21-labs-maestro-api/) — The Maestro API from AI21 Labs — 2 operation(s) for maestro.
- [AI21 Labs Chat Completions API](https://apis.io/apis/ai21-labs/ai21-labs-chat-completions-api/) — The Chat Completions API from AI21 Labs — 1 operation(s) for chat completions.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [AI21 Studio Streaming API](https://apis.io/asyncapis/ai21-labs/ai21-labs-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [chat/completions](https://apis.io/channels/ai21-labs/chat-completions/)

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/ai21-labs/](https://apis.io/graphqls/ai21-labs/ai21-labs-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [ai21-labs](https://apis.io/servers/ai21-labs/ai21-labs/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ai21 Labs Agentic Access](https://apis.io/agentic-access/ai21-labs/ai21-labs-agentic-access/)

#### Collections (4)

Postman and Open Collection request collections.

- [AI21 Studio API](https://apis.io/collections/ai21-labs/open-ai21-labs/)
- [AI21 Studio Chat API](https://apis.io/collections/ai21-labs/open-ai21-labs-chat-api/)
- [AI21 Studio Chat Library API](https://apis.io/collections/ai21-labs/open-ai21-labs-library-api/)
- [AI21 Studio Chat Maestro API](https://apis.io/collections/ai21-labs/open-ai21-labs-maestro-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [AI21 Labs — asyncapi rules](https://apis.io/rules/ai21-labs/ai21-labs-asyncapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ai21 Labs Authentication](https://apis.io/security/ai21-labs/ai21-labs-authentication/)
- [Ai21 Labs Domain Security](https://apis.io/security/ai21-labs/ai21-labs-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ai21 Labs Plans Pricing](https://apis.io/plans/ai21-labs/ai21-labs-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ai21 Labs Rate Limits](https://apis.io/rate-limits/ai21-labs/ai21-labs-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ai21 Labs Finops](https://apis.io/finops/ai21-labs/ai21-labs-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ai21.com/)
- [Documentation](https://docs.ai21.com/)
- [API reference](https://docs.ai21.com/reference)
- [Pricing](https://www.ai21.com/pricing/)
- [Changelog](https://docs.ai21.com/changelog)
- [Blog](https://www.ai21.com/blog/)
- [GitHub](https://github.com/AI21Labs)

## API Evangelist rating

**Kin Score 39.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 55.7 |
| Contract governance | 11.4 |
| Operational transparency | 23.7 |
| Developer ergonomics | 31.0 |
| Access clarity | 42.1 |

**Agent readiness 29.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 10.9** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ai21-labs/](https://apis.io/providers/ai21-labs/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for AI21 Labs: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ai21-labs/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
