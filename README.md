# AlphaAI

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

A REST API and agent-native platform for relevance-scored, ticker-linked financial news, built for trading bots, agent backends, and dashboards. Every article is enriched at ingest with a 1-10 relevance score, one of fourteen categories, validated ticker links, and per-ticker sentiment with an impact analysis and confidence rating, plus structured SEC Form 4 insider data sourced from EDGAR. The same data core is served three ways — an OpenAPI 3.1 REST API at api.alphai.io, a hosted MCP server with OAuth 2.1 and dynamic client registration at mcp.alphai.io, and HMAC-signed webhooks on the Pro tier — alongside first-party Python, TypeScript and Rust clients and a provider-published pack of Claude Code agent skills.

**Areas:** Financial News · Stock Market · SEC Filings · Insider Trading · Fintech · Market Data · Sentiment · AI Agents · MCP · LLM · Trading

## AlphaAI on APIs.io

Everything profiled for AlphaAI is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/alphaai/](https://apis.io/providers/alphaai/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [AlphaAI MCP Server](https://apis.io/apis/alphaai/alphaai-mcp-server/) — Hosted MCP server over Streamable HTTP exposing fifteen tools for news search, ticker news, trending, actionable-now, macro, economic calendar, insider…
- [AlphaAI Claude Code Skills](https://apis.io/apis/alphaai/alphaai-claude-code-skills/) — Provider-published open-source pack of five Claude Code agent skills wrapping the MCP tools into ready-made workflows: one-ticker brief, market pulse,…
- [AlphaAI Calendar API](https://apis.io/apis/alphaai/alphaai-calendar-api/) — Scheduled US macro releases (FOMC, CPI, jobs, GDP, PCE…).
- [AlphaAI News API](https://apis.io/apis/alphaai/alphaai-news-api/) — Relevance-scored, ticker-linked news.
- [AlphaAI Symbols API](https://apis.io/apis/alphaai/alphaai-symbols-api/) — Active equity, crypto, and foreign symbols (tickers).

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Alphaai Webhooks](https://apis.io/asyncapis/alphaai/alphaai-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [mcp](https://apis.io/servers/alphaai/mcp/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Alphaai Agentic Access](https://apis.io/agentic-access/alphaai/alphaai-agentic-access/)

#### Collections (1)

Postman and Open Collection request collections.

- [alphai REST API](https://apis.io/collections/alphaai/open-alphaai-rest-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Alphaai Rest Api Overlay](https://apis.io/overlays/alphaai/alphaai-rest-api-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Alphaai Authentication](https://apis.io/security/alphaai/alphaai-authentication/)
- [Alphaai Domain Security](https://apis.io/security/alphaai/alphaai-domain-security/)
- [Alphaai Vulnerability Disclosure](https://apis.io/security/alphaai/alphaai-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Alphaai Scopes](https://apis.io/scopes/alphaai/alphaai-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Alphaai Plans Pricing](https://apis.io/plans/alphaai/alphaai-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Alphaai Rate Limits](https://apis.io/rate-limits/alphaai/alphaai-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Documentation](https://alphai.io/developers)
- [Getting started](https://alphai.io/developers)
- [API reference](https://api.alphai.io/api/schema/swagger-ui/)
- [Pricing](https://alphai.io/pricing)
- [Sign up](https://alphai.io/account/api-keys)
- [Support](https://alphai.io/contact)
- [Changelog](https://alphai.io/changelog)
- [Blog](https://alphai.io/research)
- [Security](https://api.alphai.io/.well-known/security.txt)
- [Terms of service](https://alphai.io/terms)
- [Privacy policy](https://alphai.io/privacy)
- [GitHub](https://github.com/makeev)
- [Status](https://status.alphai.io)

## API Evangelist rating

**Unrated** — no public website could be reached for this company, so there was almost nothing to measure and nothing a reader could check.

This is not a score of zero. No rating is published for this company. If that is wrong because something public exists that we missed, say so on this repository or email [info@apievangelist.com](mailto:info@apievangelist.com) and it will be re-run — free, and no justification needed.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for AlphaAI: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/alphaai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
