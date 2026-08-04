# chucknorris.io (chucknorris-io)

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

Free JSON REST API for hand-curated Chuck Norris jokes (facts) maintained by @matchilling. Supports random retrieval, category filtering, full-text search, and direct lookup by joke identifier. Hosted at api.chucknorris.io with an open-source Spring Boot service (chuck-api), official Node.js and Java client SDKs, a Chrome extension, a Storybook addon, and Messenger / Alexa companion apps published under the chucknorris-io GitHub organization.

**APIs.json:** [https://api.chucknorris.io](https://api.chucknorris.io)

## Tags

- Entertainment
- Jokes
- Chuck Norris
- Open Source
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Chuck Norris Jokes API

JSON REST API exposing hand-curated Chuck Norris jokes. Endpoints cover random retrieval, category-constrained random retrieval, listing of the 16 supported categories, free-text search, and lookup by joke id. No authentication is required and no rate limits are documented.

- **Human URL:** [https://api.chucknorris.io](https://api.chucknorris.io)
- **Base URL:** `https://api.chucknorris.io`

#### Tags

- Entertainment
- Jokes
- Chuck Norris

#### Properties

- [Documentation](https://api.chucknorris.io)
- [OpenAPI](openapi/chucknorris-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chucknorris-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chucknorris-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/chucknorris-io-joke-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/chucknorris-io-category-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/chucknorris-io-search-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/chucknorris-io-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/chucknorris-io-joke-structure.json)
- [JSON Structure](json-structure/chucknorris-io-category-list-structure.json)
- [JSON Structure](json-structure/chucknorris-io-search-result-structure.json)
- [JSON Structure](json-structure/chucknorris-io-error-structure.json)
- [J S O N- L D](json-ld/chucknorris-io-context.jsonld)
- [Example](examples/chucknorris-io-getRandomJoke-example.json)
- [Example](examples/chucknorris-io-getRandomJoke-by-category-example.json)
- [Example](examples/chucknorris-io-listCategories-example.json)
- [Example](examples/chucknorris-io-searchJokes-example.json)
- [Example](examples/chucknorris-io-getJokeById-example.json)
- [Example](examples/chucknorris-io-joke-example.json)
- [Example](examples/chucknorris-io-category-list-example.json)
- [Example](examples/chucknorris-io-search-result-example.json)
- [Example](examples/chucknorris-io-error-example.json)
- [Authentication](https://api.chucknorris.io)
- [Rate Limits](https://api.chucknorris.io)

## Common Properties

- [Website](https://api.chucknorris.io)
- [GitHub Organization](https://github.com/chucknorris-io)
- [GitHub Repository](https://github.com/chucknorris-io/chuck-api)
- [License](https://github.com/chucknorris-io/chuck-api/blob/master/LICENSE)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Spectral Rules](rules/chucknorris-io-rules.yml)
- [Vocabulary](vocabulary/chucknorris-io-vocabulary.yml)
- [SDK](https://github.com/chucknorris-io/client-nodejs)
- [SDK](https://github.com/chucknorris-io/client-java)
- [Integrations](undefined)
- [Features](undefined)
- [Use Cases](undefined)
- [Tools](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
