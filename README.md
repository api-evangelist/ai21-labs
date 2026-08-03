# AI21 Labs (ai21-labs)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AI21 Labs is an enterprise foundation-model company best known for the Jamba family of open-weight hybrid Mamba/Transformer models and AI21 Maestro, a dynamic planning system that orchestrates tools, retrieval, and validated output during inference. The platform exposes a Bearer-token REST API at api.ai21.com covering chat completions, conversational RAG over a managed file library, batch processing, fine-tuning, and function calling. Official Python and TypeScript SDKs wrap the API with sync and async clients and integrate natively into LangChain and LlamaIndex. Jamba weights are also published on Hugging Face for self-hosted vLLM deployment.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ai21-labs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ai21-labs/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- AI
- Foundation Models
- LLM
- Jamba
- Mamba
- RAG
- Agents
- Maestro
- Inference
- Enterprise AI
- Fine-Tuning

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-29

## APIs

### AI21 Jamba Chat Completions API

Conversational completions endpoint backed by the Jamba family of hybrid Mamba/Transformer models (Jamba 1.5 Mini, Jamba 1.5 Large, Jamba 1.6). Accepts a message array, system prompts, temperature, max tokens, tools, and streaming, returning assistant messages with usage metadata.

- **Human URL:** [https://docs.ai21.com/reference](https://docs.ai21.com/reference)
- **Base URL:** `https://api.ai21.com/studio/v1`

#### Tags

- Chat
- Completions
- Jamba
- LLM

#### Properties

- [Documentation](https://docs.ai21.com/reference)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/ai21-labs/refs/heads/main/asyncapi/ai21-labs-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/ai21-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai21-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AI21 Maestro API

Dynamic planning system that, at inference time, determines the optimal sequence of actions to solve a task. Exposes run creation and retrieval endpoints, supports validated output for strict instruction following, and orchestrates RAG, web search, file libraries, MCP tools, and custom HTTP tools.

- **Human URL:** [https://docs.ai21.com/docs/maestro](https://docs.ai21.com/docs/maestro)
- **Base URL:** `https://api.ai21.com/studio/v1`

#### Tags

- Maestro
- Planning
- Agents
- Validated Output

#### Properties

- [Documentation](https://docs.ai21.com/docs/maestro)
- [Postman Collection](collections/ai21-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai21-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AI21 File Library API

Managed file storage for RAG workflows. Upload, list, retrieve, update, and delete documents that Maestro and Jamba endpoints can ground on at inference time.

- **Human URL:** [https://docs.ai21.com/reference](https://docs.ai21.com/reference)
- **Base URL:** `https://api.ai21.com/studio/v1`

#### Tags

- Files
- RAG
- Library
- Documents

#### Properties

- [Documentation](https://docs.ai21.com/reference)
- [Postman Collection](collections/ai21-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai21-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AI21 Batch API

Asynchronous batch processing for large volumes of Jamba completions. Submit a batch job, poll for status, and download results when the run completes.

- **Human URL:** [https://docs.ai21.com/reference](https://docs.ai21.com/reference)
- **Base URL:** `https://api.ai21.com/studio/v1`

#### Tags

- Batch
- Async
- Inference

#### Properties

- [Documentation](https://docs.ai21.com/reference)
- [Postman Collection](collections/ai21-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai21-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AI21 Fine-Tuning API

Fine-tuning service for Jamba models supporting full, LoRA, and QLoRA strategies. Create training jobs from uploaded datasets and deploy the resulting model variants behind the standard chat completions endpoint.

- **Human URL:** [https://docs.ai21.com/docs/fine-tuning](https://docs.ai21.com/docs/fine-tuning)
- **Base URL:** `https://api.ai21.com/studio/v1`

#### Tags

- Fine-Tuning
- LoRA
- QLoRA
- Training

#### Properties

- [Documentation](https://docs.ai21.com/docs/fine-tuning)
- [Postman Collection](collections/ai21-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai21-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AI21 Python SDK

Official Python SDK (ai21 on PyPI) wrapping the AI21 Studio REST API with sync and async clients, streaming support, LangChain / LlamaIndex integrations, and helpers for chat, Maestro, library, and batch.

- **Human URL:** [https://github.com/AI21Labs/ai21-python](https://github.com/AI21Labs/ai21-python)
- **Base URL:** `https://github.com/AI21Labs/ai21-python`

#### Tags

- SDK
- Python
- PyPI

#### Properties

- [Repository](https://github.com/AI21Labs/ai21-python)
- [Postman Collection](collections/ai21-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai21-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AI21 TypeScript / JavaScript SDK

Official TypeScript and JavaScript client for the AI21 Studio API, with typed request and response models and streaming helpers for browser and Node.js runtimes.

- **Human URL:** [https://github.com/AI21Labs/ai21-typescript](https://github.com/AI21Labs/ai21-typescript)
- **Base URL:** `https://github.com/AI21Labs/ai21-typescript`

#### Tags

- SDK
- TypeScript
- JavaScript

#### Properties

- [Repository](https://github.com/AI21Labs)
- [Postman Collection](collections/ai21-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai21-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AI21 Jamba on Hugging Face

Open-weight releases of the Jamba family on Hugging Face for self-hosted inference via vLLM, Transformers, and other runtimes.

- **Human URL:** [https://huggingface.co/ai21labs](https://huggingface.co/ai21labs)
- **Base URL:** `https://huggingface.co/ai21labs`

#### Tags

- Hugging Face
- Open Weights
- Jamba
- Self-Hosted

#### Properties

- [Repository](https://huggingface.co/ai21labs)
- [Postman Collection](collections/ai21-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai21-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.ai21.com/)
- [Documentation](https://docs.ai21.com/)
- [API Reference](https://docs.ai21.com/reference)
- [GitHub Organization](https://github.com/AI21Labs)
- [Hugging Face](https://huggingface.co/ai21labs)
- [Blog](https://www.ai21.com/blog/)
- [Pricing](https://www.ai21.com/pricing/)
- [Changelog](https://docs.ai21.com/changelog)
- [LinkedIn](https://www.linkedin.com/company/ai21/)
- [X (Twitter)](https://x.com/AI21Labs)
- [L L Ms Txt](https://docs.ai21.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
