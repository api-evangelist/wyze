# Wyze

Wyze Labs, Inc. is a Kirkland, Washington consumer smart-home company founded in 2017 by
former Amazon employees, selling value-priced connected hardware — security cameras, video
doorbells, locks, sensors, plugs, bulbs, robot vacuums, thermostats, sprinkler controllers,
scales and wearables — operated through the Wyze app and backed by subscription cloud
services (Cam Plus, Cam Unlimited, Wyze Home Monitoring).

- Website: https://www.wyze.com
- Developer API Console: https://developer-api-console.wyze.com/
- API key documentation: https://support.wyze.com/hc/en-us/articles/16129834216731-Creating-an-API-Key
- Security & trust: https://www.wyze.com/pages/security-trust

## API surface

Wyze does **not** publish an OpenAPI, AsyncAPI, GraphQL schema or A2A agent card, and has
no first-party SDK in any package registry. It does operate:

| Surface | Host | Contract |
|---|---|---|
| Wyze Developer API | `api.wyzecam.com` / `auth-prod.api.wyze.com` | Support-article documented; personal API Key + Key ID exchanged for bearer tokens |
| Storefront MCP server | `www.wyze.com/api/mcp` | Live MCP `tools/list` — 5 tools, captured verbatim |
| Customer Account MCP server | `account.wyze.com/customer/api/mcp` | Live MCP `tools/list` — 4 tools, captured verbatim |
| UCP shopping endpoint | `www.wyze.com/api/ucp/mcp` | Universal Commerce Protocol `2026-04-08`; `tools/list` gated behind an agent profile |

Notable for agents: the `api.wyzecam.com` host returns **HTTP 200 on failure** and signals
errors through a body `code` field — see `errors/wyze-problem-types.yml`.

## Artifacts

`llms/` · `mcp/` · `well-known/` · `packages/` · `authentication/` · `scopes/` ·
`conventions/` · `errors/` · `lifecycle/` · `conformance/` · `security/`
