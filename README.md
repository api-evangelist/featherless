# Featherless AI (featherless)

Featherless AI is a serverless LLM inference platform that serves thousands of open-weight models from the Hugging Face catalog behind a single OpenAI-compatible REST API. It uses flat monthly subscription pricing with unlimited tokens rather than per-token billing, exposing chat completions, text completions, an embeddings endpoint, and a large models catalog.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/featherless/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/featherless/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Inference
- Serverless
- Open Models

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Featherless Chat Completions API

OpenAI-compatible chat completions across thousands of open-weight Hugging Face models, with streaming, tool calling, vision messages, and the full set of sampling parameters (temperature, top_p, top_k, min_p, penalties).

- **Human URL:** [https://featherless.ai/docs/completions](https://featherless.ai/docs/completions)
- **Base URL:** `https://api.featherless.ai/v1`

#### Tags

- Chat
- Completions
- LLM

#### Properties

- [Documentation](https://featherless.ai/docs/completions)
- [API Reference](https://featherless.ai/docs/api-examples-and-snippets)
- [OpenAPI](openapi/featherless-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/featherless-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/featherless.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/featherless.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Featherless Completions API

OpenAI-compatible legacy text completions endpoint accepting a prompt string (or array for parallel inference) against any catalog model, with the same sampling controls as chat completions.

- **Human URL:** [https://featherless.ai/docs/completions](https://featherless.ai/docs/completions)
- **Base URL:** `https://api.featherless.ai/v1`

#### Tags

- Completions
- Text Generation

#### Properties

- [Documentation](https://featherless.ai/docs/completions)
- [API Reference](https://featherless.ai/docs/api-examples-and-snippets)
- [OpenAPI](openapi/featherless-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/featherless.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/featherless.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Featherless Models API

Lists the thousands of open-weight models available for serverless inference, surfaced through an OpenAI-compatible models endpoint for runtime discovery.

- **Human URL:** [https://featherless.ai/docs/quickstart-guide](https://featherless.ai/docs/quickstart-guide)
- **Base URL:** `https://api.featherless.ai/v1`

#### Tags

- Models
- Catalog

#### Properties

- [Documentation](https://featherless.ai/docs/quickstart-guide)
- [OpenAPI](openapi/featherless-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/featherless.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/featherless.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Featherless Embeddings API

OpenAI-compatible embeddings endpoint that returns vector representations for a string or array of inputs using open embedding models such as Qwen3-Embedding, with optional encoding_format and dimensions.

- **Human URL:** [https://featherless.ai/docs/embeddings](https://featherless.ai/docs/embeddings)
- **Base URL:** `https://api.featherless.ai/v1`

#### Tags

- Embeddings
- Vectors

#### Properties

- [Documentation](https://featherless.ai/docs/embeddings)
- [OpenAPI](openapi/featherless-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/featherless.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/featherless.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/featherless-ai)
- [LinkedIn](https://www.linkedin.com/company/featherless-ai)
- [Website](https://featherless.ai/)
- [Documentation](https://featherless.ai/docs/quickstart-guide)
- [Plans](plans/featherless-plans-pricing.yml)
- [Rate Limits](rate-limits/featherless-rate-limits.yml)
- [Fin Ops](finops/featherless-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
