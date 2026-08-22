# Featherless AI (featherless)

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
