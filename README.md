# chucknorris.io (chucknorris-io)

Free JSON REST API for hand-curated Chuck Norris jokes (facts) maintained by
@matchilling. Supports random retrieval, category filtering, full-text search,
and direct lookup by joke identifier. Hosted at api.chucknorris.io with an
open-source Spring Boot service (chuck-api) and official client SDKs in
Node.js and Java.

**APIs.yml:** [apis.yml](apis.yml)

## Type

- **x-type:** opensource
- **x-tier:** 3 (bulk-registered from public-apis, enriched 2026-05-30)
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Entertainment
- **license:** GPL-3.0 (chuck-api service source)

## APIs

### Chuck Norris Jokes API

JSON REST API exposing hand-curated Chuck Norris jokes. No authentication
required, no documented rate limits.

| Operation | Method | Path |
|---|---|---|
| Get Random Joke | GET | `/jokes/random` |
| Get Random Joke (by category) | GET | `/jokes/random?category={category}` |
| List Joke Categories | GET | `/jokes/categories` |
| Search Jokes | GET | `/jokes/search?query={query}` |
| Get Joke By Id | GET | `/jokes/{id}` |

Categories: `animal`, `career`, `celebrity`, `dev`, `explicit`, `fashion`,
`food`, `history`, `money`, `movie`, `music`, `political`, `religion`,
`science`, `sport`, `travel`.

## Artifacts

| Folder | Files |
|---|---|
| `openapi/` | `chucknorris-io-openapi.yml` |
| `rules/` | `chucknorris-io-rules.yml` |
| `capabilities/` | `chucknorris-io-jokes.yaml`, `chucknorris-io-categories.yaml`, `chucknorris-io-search.yaml` |
| `json-schema/` | `chucknorris-io-joke-schema.json`, `chucknorris-io-category-list-schema.json`, `chucknorris-io-search-result-schema.json`, `chucknorris-io-error-schema.json` |
| `json-structure/` | `chucknorris-io-joke-structure.json`, `chucknorris-io-category-list-structure.json`, `chucknorris-io-search-result-structure.json`, `chucknorris-io-error-structure.json` |
| `json-ld/` | `chucknorris-io-context.jsonld` |
| `examples/` | 5 operation examples + 4 entity examples |
| `vocabulary/` | `chucknorris-io-vocabulary.yml` |

## Ecosystem

The [chucknorris-io](https://github.com/chucknorris-io) GitHub organization
publishes:

- **chuck-api** — Java/Spring Boot service powering api.chucknorris.io.
- **chuck-db** — PostgreSQL schema, stored procedures, and migrations.
- **client-nodejs** — Official Node.js client library.
- **client-java** — Official Java client library.
- **google-chrome-extension** — Official Chrome extension.
- **storybook-addon** — Storybook addon injecting Chuck Norris facts.
- **app-facebook-messenger** — Messenger bot wrapping the API.
- **app-alexa-skill** — Alexa skill wrapping the API.
- **chuck-infra-tools** — Postman collection and dev utilities.
- **swear-words** — Curated profanity dictionary used to flag explicit jokes.

No first-party MCP server or Anthropic Skill exists; several third-party MCP
servers wrap the API (e.g., thomasma/chuckjokes-mcpserver,
BACH-AI-Tools/chuck_norris).

## Tags

Entertainment, Jokes, Chuck Norris, Open Source, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## Maintainers

- **Kin Lane** — kin@apievangelist.com
