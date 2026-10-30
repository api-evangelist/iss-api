# ISS Location API (Open Notify)

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

Open Notify is a free, open-source project by Nathan Bergey that exposes real-time NASA and ISS data as simple REST endpoints. The service provides the current latitude and longitude of the International Space Station (updated every five seconds as the ISS travels at roughly 28,000 km/h), a count and roster of all humans currently in space across all spacecraft, and historical ISS pass-time predictions for any point on Earth. All endpoints are unauthenticated, return JSON, and are free to use without registration. The ISS pass-time prediction endpoint has been retired; the location and astronaut endpoints remain live and operational.

**Areas:** Space · ISS · International Space Station · NASA · Location · Geolocation · Astronauts · Real-Time · Open Source · Public APIs · Free

## ISS Location API (Open Notify) on APIs.io

Everything profiled for ISS Location API (Open Notify) is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/iss-api/](https://apis.io/providers/iss-api/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [People in Space Right Now](https://apis.io/apis/iss-api/astronauts-in-space/) — Returns a JSON object containing the total count of humans currently in space and an array of crew member objects, each with the person's name and the…
- [ISS Location API (Open Notify) Astronauts API](https://apis.io/apis/iss-api/iss-api-astronauts-api/) — Endpoints for retrieving information about humans currently in space
- [ISS Location API (Open Notify) ISS Location API](https://apis.io/apis/iss-api/iss-api-iss-location-api/) — Endpoints for retrieving the current position of the International Space Station

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Iss Api Agentic Access](https://apis.io/agentic-access/iss-api/iss-api-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Astronauts Response](https://apis.io/schemas/iss-api/astronauts-response/)
- [ISS Location Response](https://apis.io/schemas/iss-api/iss-location-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [context Context](https://apis.io/jsonld/iss-api/context/)

#### Examples (2)

Example requests and responses.

- [Astronauts Response](https://apis.io/examples/iss-api/astronauts-response/)
- [Iss Location Response](https://apis.io/examples/iss-api/iss-location-response/)

#### Collections (2)

Postman and Open Collection request collections.

- [ISS Location API (Open Notify) Astronauts API](https://apis.io/collections/iss-api/open-iss-api-astronauts-api/)
- [API (Open Notify) Astronauts ISS Location API](https://apis.io/collections/iss-api/open-iss-api-iss-location-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [ISS Location API (Open Notify) — jsonschema rules](https://apis.io/rules/iss-api/iss-api-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Iss Api Domain Security](https://apis.io/security/iss-api/iss-api-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Iss Api Plans](https://apis.io/plans/iss-api/iss-api-plans/)

#### Rate limits (1)

Published request limits.

- [Iss Api Rate Limits](https://apis.io/rate-limits/iss-api/iss-api-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Iss Api Finops](https://apis.io/finops/iss-api/iss-api-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](http://open-notify.org/)
- [Documentation](http://open-notify.org/Open-Notify-API/)
- [GitHub](https://github.com/open-notify)

## API Evangelist rating

**Kin Score 23.3** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 48.7 |
| Contract governance | 9.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 9.5 |
| Access clarity | 5.3 |

**Agent readiness 23.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 10.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/iss-api/](https://apis.io/providers/iss-api/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for ISS Location API (Open Notify): the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/iss-api/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
