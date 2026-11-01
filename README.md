# Wyze

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

Wyze Labs, Inc. is a Kirkland, Washington consumer smart-home company founded in 2017 by former Amazon employees, known for value-priced connected hardware: indoor and outdoor security cameras, video doorbells, smart locks, contact and motion sensors, plugs, bulbs and light strips, robot vacuums, thermostats, sprinkler controllers, scales and wearables. Devices are operated through the Wyze app and backed by cloud services sold as subscriptions (Cam Plus, Cam Unlimited, Wyze Home Monitoring). Wyze does not publish a general-purpose public developer platform, but it does operate a first-party Developer API Console at developer-api-console.wyze.com that issues a personal API Key / Key ID pair so owners can authenticate against the Wyze cloud API (auth-prod.api.wyze.com and api.wyzecam.com) from Home Assistant, Homebridge and other third-party integrations. Its Shopify-hosted storefront additionally exposes agent-facing commerce surfaces: a published llms.txt/agents.md, a Universal Commerce Protocol (UCP) discovery document, and two live Model Context Protocol servers.

**Areas:** Company · Smart Home · IoT · Home Security · Camera · Consumer Electronics · Home Automation · Video · Sensors · Commerce

## Wyze on APIs.io

Everything profiled for Wyze is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/wyze/](https://apis.io/providers/wyze/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Wyze Developer API](https://apis.io/apis/wyze/developer-api/) — The first-party Wyze cloud API reached with a personal API Key and Key ID generated from the Wyze Developer API Console. Authentication posts credentials to…
- [Wyze Storefront MCP Server](https://apis.io/apis/wyze/storefront-mcp/) — A live, anonymously reachable Model Context Protocol server on the Wyze storefront host that lets agents search the Wyze product catalog, read and update a…
- [Wyze Customer Account MCP Server](https://apis.io/apis/wyze/customer-account-mcp/) — A live Model Context Protocol server on account.wyze.com exposing customer order-status lookup, store-credit balances and return requests. tools/list…
- [Wyze UCP Commerce Endpoint](https://apis.io/apis/wyze/ucp/) — The Universal Commerce Protocol (UCP) merchant surface published by the Wyze storefront. The /.well-known/ucp discovery document declares supported UCP…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [wyze-mcp.yml](https://apis.io/servers/wyze/wyze-mcp-yml/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Wyze Authentication](https://apis.io/security/wyze/wyze-authentication/)
- [Wyze Domain Security](https://apis.io/security/wyze/wyze-domain-security/)
- [Wyze Trust Center](https://apis.io/security/wyze/wyze-trust-center/)
- [Wyze Vulnerability Disclosure](https://apis.io/security/wyze/wyze-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Wyze Scopes](https://apis.io/scopes/wyze/wyze-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.wyze.com)
- [Documentation](https://support.wyze.com/hc/en-us/articles/16129834216731-Creating-an-API-Key)
- [Getting started](https://support.wyze.com/hc/en-us/articles/16129834216731-Creating-an-API-Key)
- [Pricing](https://www.wyze.com/pages/service-plans)
- [Support](https://support.wyze.com/hc/en-us)
- [Blog](https://www.wyze.com/blogs/news)
- [Security](https://www.wyze.com/pages/wyzes-vulnerability-disclosure)
- [Compliance](https://www.wyze.com/pages/security-trust)
- [Terms of service](https://www.wyze.com/policies/terms-of-service)
- [Privacy policy](https://www.wyze.com/policies/privacy-policy)
- [GitHub](https://github.com/wyzelabs-inc)
- [Status](https://support.wyze.com/hc/en-us/articles/360015979872-Service-Status-Known-Issues)

## API Evangelist rating

**Kin Score 39.2** — thin · rubric 0.24.0 · scored 2026-10-20

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 28.9 |
| Developer ergonomics | 50.0 |
| Access clarity | 53.9 |

**Agent readiness 13.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | platform (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | platform (partial credit) |

**Regulatory alignment 45.1** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/wyze/](https://apis.io/providers/wyze/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Wyze: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/wyze/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
