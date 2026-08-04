# ngrok AI Gateway (ngrok-ai)

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

ngrok AI Gateway provides traffic management and security for AI APIs including multi-provider routing, automatic failover, LLM prompt inspection, rate limiting, caching, observability, PII redaction, and access control. It enables teams to manage, secure, and monitor traffic to AI model providers (OpenAI, Anthropic, Google, DeepSeek) and self-hosted models such as Ollama and vLLM through an OpenAI-compatible interface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ngrok-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ngrok-ai/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI
- AI Gateway
- API Gateway
- LLM
- OpenAI Compatible
- Routing
- Security
- Traffic Management

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-28

## APIs

### ngrok AI Gateway

ngrok AI Gateway exposes an OpenAI-compatible HTTP interface for routing requests across multiple AI providers and self-hosted models. Each AI Gateway instance has a unique base URL of the form https://your-ai-gateway.ngrok.app/v1 and accepts standard OpenAI SDK calls including chat completions. Traffic policies provide rate limiting, prompt inspection, PII redaction, response sanitization, model access control, cost-based routing, and automatic provider failover.

- **Human URL:** [https://ngrok.com/docs/ai-gateway/](https://ngrok.com/docs/ai-gateway/)
- **Base URL:** `https://your-ai-gateway.ngrok.app/v1`

#### Tags

- AI Gateway
- API Gateway
- LLM
- OpenAI Compatible
- Routing
- Security

#### Properties

- [Documentation](https://ngrok.com/docs/ai-gateway/)
- [Getting Started](https://ngrok.com/docs/ai-gateway/quickstart/)
- [API Reference](https://ngrok.com/docs/ai-gateway/)
- [Postman Collection](collections/ngrok-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ngrok-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/ngrok)
- [Website](https://ngrok.com/ai-gateway)
- [Documentation](https://ngrok.com/docs/ai-gateway/)
- [Getting Started](https://ngrok.com/docs/ai-gateway/quickstart/)
- [Blog](https://ngrok.com/blog)
- [Pricing](https://ngrok.com/pricing)
- [Support](https://ngrok.com/support)
- [Status Page](https://status.ngrok.com)
- [GitHub Organization](https://github.com/ngrok)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://ngrok.com/docs/integrations)
- [L L Ms Txt](https://ngrok.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
