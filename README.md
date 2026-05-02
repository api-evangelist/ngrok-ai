# ngrok AI Gateway (ngrok-ai)

ngrok AI Gateway provides traffic management and security for AI APIs including multi-provider routing, automatic failover, LLM prompt inspection, rate limiting, caching, observability, PII redaction, and access control. It enables teams to manage, secure, and monitor traffic to AI model providers (OpenAI, Anthropic, Google, DeepSeek) and self-hosted models such as Ollama and vLLM through an OpenAI-compatible interface.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ngrok-ai/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

 - AI, AI Gateway, API Gateway, LLM, OpenAI Compatible, Routing, Security, Traffic Management

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-28

## APIs

### ngrok AI Gateway

ngrok AI Gateway exposes an OpenAI-compatible HTTP interface for routing requests across multiple AI providers and self-hosted models. Each AI Gateway instance has a unique base URL of the form `https://your-ai-gateway.ngrok.app/v1` and accepts standard OpenAI SDK calls including chat completions. Traffic policies provide rate limiting, prompt inspection, PII redaction, response sanitization, model access control, cost-based routing, and automatic provider failover.

**Human URL:** [https://ngrok.com/docs/ai-gateway/](https://ngrok.com/docs/ai-gateway/)

**Base URL:** `https://your-ai-gateway.ngrok.app/v1`

#### Tags

 - AI Gateway, API Gateway, LLM, OpenAI Compatible, Routing, Security

#### Properties

- [Documentation](https://ngrok.com/docs/ai-gateway/)
- [GettingStarted](https://ngrok.com/docs/ai-gateway/quickstart/)
- [APIReference](https://ngrok.com/docs/ai-gateway/)

## Common Properties

- [Website](https://ngrok.com/ai-gateway)
- [Documentation](https://ngrok.com/docs/ai-gateway/)
- [GettingStarted](https://ngrok.com/docs/ai-gateway/quickstart/)
- [Blog](https://ngrok.com/blog)
- [Pricing](https://ngrok.com/pricing)
- [Support](https://ngrok.com/support)
- [StatusPage](https://status.ngrok.com)
- [GitHubOrganization](https://github.com/ngrok)

## Features

| Name | Description |
|---|---|
| Multi-Provider Routing | Direct requests to AI providers including OpenAI, Anthropic, Google, and DeepSeek through a single gateway endpoint. |
| Automatic Failover | If one provider or model fails, the gateway automatically tries the next configured model. |
| OpenAI SDK Compatibility | Works with official and third-party OpenAI SDKs by changing only the base URL. |
| Self-Hosted Model Support | Route requests to local systems such as Ollama or vLLM alongside hosted providers. |
| Automatic Model Selection | Use ngrok/auto for intelligent model picking based on configured strategies. |
| CEL-Based Selection Strategies | Define custom routing logic using Common Expression Language expressions. |
| Cost-Based Routing | Direct traffic to the cheapest available model option meeting requirements. |
| Access Control | Restrict which providers and models clients can use by API key, identity, or policy. |
| PII Redaction | Inspect and modify content to remove personally identifiable information from prompts and responses. |
| Response Sanitization | Modify and filter responses before they reach clients. |
| No Provider Account Required | Access OpenAI and Anthropic models without individual provider signup, using ngrok credits. |

## Use Cases

| Name | Description |
|---|---|
| Centralized AI API Management | Manage all AI provider traffic through a single gateway with unified observability and policy enforcement. |
| Cost Optimization | Route traffic to the most cost-effective model that meets quality requirements. |
| Compliance and Data Protection | Enforce PII redaction and prompt inspection policies before requests leave the organization. |
| Multi-Provider Resilience | Failover automatically across providers to maintain AI service availability. |
| Local and Hybrid Model Routing | Route between hosted providers and self-hosted models such as Ollama or vLLM. |

## Integrations

| Name | Description |
|---|---|
| OpenAI | Native OpenAI-compatible interface and routing to OpenAI models. |
| Anthropic | Routing and access to Anthropic Claude models through the gateway. |
| Google | Routing to Google AI models. |
| DeepSeek | Routing to DeepSeek models. |
| Ollama | Routing to self-hosted Ollama instances. |
| vLLM | Routing to self-hosted vLLM inference servers. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
