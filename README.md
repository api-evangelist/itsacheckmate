# ItsaCheckmate

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

ItsaCheckmate (Checkmate) is restaurant middleware that connects point-of-sale systems to delivery marketplaces and ordering channels, providing two-way integration, menu management, and consolidated reporting across 50+ POS systems and 100+ ordering platforms for tens of thousands of restaurant locations. Through its Marketplace for Developers, Checkmate offers a self-service open REST API that lets technology partners build a single integration to read and write menus, orders, and locations across many POS systems. The API uses OAuth-style token authentication with short-lived, scoped access and refresh tokens, ready-to-use Postman collections, and an llms.txt index for AI agents.

**Areas:** Restaurant · Point-of-Sale · Online Ordering · Delivery · Menus · Order · Integration

## ItsaCheckmate on APIs.io

Everything profiled for ItsaCheckmate is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/itsacheckmate/](https://apis.io/providers/itsacheckmate/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [ItsaCheckmate Locations API](https://apis.io/apis/itsacheckmate/itsacheckmate-locations-api/) — Location activation and location detail retrieval.
- [ItsaCheckmate Menus API](https://apis.io/apis/itsacheckmate/itsacheckmate-menus-api/) — Menu retrieval per ordering platform.
- [ItsaCheckmate Orders API](https://apis.io/apis/itsacheckmate/itsacheckmate-orders-api/) — Standard and group order submission into the POS.
- [ItsaCheckmate O Auth API](https://apis.io/apis/itsacheckmate/itsacheckmate-oauth-api/) — Token issuance, refresh, and introspection.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Itsacheckmate Agentic Access](https://apis.io/agentic-access/itsacheckmate/itsacheckmate-agentic-access/)

#### JSON Schema (14)

The data models the API reads and writes.

- [ActivationResult](https://apis.io/schemas/itsacheckmate/marketplace-api-activation-result/)
- [Address](https://apis.io/schemas/itsacheckmate/marketplace-api-address/)
- [Customer](https://apis.io/schemas/itsacheckmate/marketplace-api-customer/)
- [Location](https://apis.io/schemas/itsacheckmate/marketplace-api-location/)
- [Menu](https://apis.io/schemas/itsacheckmate/marketplace-api-menu/)
- [MenuCategory](https://apis.io/schemas/itsacheckmate/marketplace-api-menu-category/)
- [MenuItem](https://apis.io/schemas/itsacheckmate/marketplace-api-menu-item/)
- [Order](https://apis.io/schemas/itsacheckmate/marketplace-api-order/)
- [OrderConfirmation](https://apis.io/schemas/itsacheckmate/marketplace-api-order-confirmation/)
- [OrderItem](https://apis.io/schemas/itsacheckmate/marketplace-api-order-item/)
- [OrderTotals](https://apis.io/schemas/itsacheckmate/marketplace-api-order-totals/)
- [TokenInfo](https://apis.io/schemas/itsacheckmate/marketplace-api-token-info/)
- [TokenRequest](https://apis.io/schemas/itsacheckmate/marketplace-api-token-request/)
- [TokenResponse](https://apis.io/schemas/itsacheckmate/marketplace-api-token-response/)

#### JSON Structure (14)

Data models expressed in JSON Structure.

- [Marketplace Api Activation Result Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-activation-result-structure/)
- [Marketplace Api Address Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-address-structure/)
- [Marketplace Api Customer Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-customer-structure/)
- [Marketplace Api Location Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-location-structure/)
- [Marketplace Api Menu Category Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-menu-category-structure/)
- [Marketplace Api Menu Item Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-menu-item-structure/)
- [Marketplace Api Menu Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-menu-structure/)
- [Marketplace Api Order Confirmation Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-order-confirmation-structure/)
- [Marketplace Api Order Item Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-order-item-structure/)
- [Marketplace Api Order Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-order-structure/)
- [Marketplace Api Order Totals Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-order-totals-structure/)
- [Marketplace Api Token Info Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-token-info-structure/)
- [Marketplace Api Token Request Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-token-request-structure/)
- [Marketplace Api Token Response Structure](https://apis.io/json-structure/itsacheckmate/marketplace-api-token-response-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Itsacheckmate Context](https://apis.io/jsonld/itsacheckmate/itsacheckmate-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Itsacheckmate Vocabulary](https://apis.io/vocabularies/itsacheckmate/itsacheckmate-vocabulary/)

#### Examples (14)

Example requests and responses.

- [Marketplace Api Activation Result Example](https://apis.io/examples/itsacheckmate/marketplace-api-activation-result-example/)
- [Marketplace Api Address Example](https://apis.io/examples/itsacheckmate/marketplace-api-address-example/)
- [Marketplace Api Customer Example](https://apis.io/examples/itsacheckmate/marketplace-api-customer-example/)
- [Marketplace Api Location Example](https://apis.io/examples/itsacheckmate/marketplace-api-location-example/)
- [Marketplace Api Menu Category Example](https://apis.io/examples/itsacheckmate/marketplace-api-menu-category-example/)
- [Marketplace Api Menu Example](https://apis.io/examples/itsacheckmate/marketplace-api-menu-example/)
- [Marketplace Api Menu Item Example](https://apis.io/examples/itsacheckmate/marketplace-api-menu-item-example/)
- [Marketplace Api Order Confirmation Example](https://apis.io/examples/itsacheckmate/marketplace-api-order-confirmation-example/)
- [Marketplace Api Order Example](https://apis.io/examples/itsacheckmate/marketplace-api-order-example/)
- [Marketplace Api Order Item Example](https://apis.io/examples/itsacheckmate/marketplace-api-order-item-example/)
- [Marketplace Api Order Totals Example](https://apis.io/examples/itsacheckmate/marketplace-api-order-totals-example/)
- [Marketplace Api Token Info Example](https://apis.io/examples/itsacheckmate/marketplace-api-token-info-example/)
- [Marketplace Api Token Request Example](https://apis.io/examples/itsacheckmate/marketplace-api-token-request-example/)
- [Marketplace Api Token Response Example](https://apis.io/examples/itsacheckmate/marketplace-api-token-response-example/)

#### Collections (5)

Postman and Open Collection request collections.

- [ItsaCheckmate Marketplace for Developers Locations API](https://apis.io/collections/itsacheckmate/open-itsacheckmate-locations-api/)
- [ItsaCheckmate Marketplace for Developers API](https://apis.io/collections/itsacheckmate/open-itsacheckmate-marketplace-api/)
- [ItsaCheckmate Marketplace for Developers Locations Menus API](https://apis.io/collections/itsacheckmate/open-itsacheckmate-menus-api/)
- [ItsaCheckmate Marketplace for Developers Locations OAuth API](https://apis.io/collections/itsacheckmate/open-itsacheckmate-oauth-api/)
- [ItsaCheckmate Marketplace for Developers Locations Orders API](https://apis.io/collections/itsacheckmate/open-itsacheckmate-orders-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [ItsaCheckmate — jsonschema rules](https://apis.io/rules/itsacheckmate/itsacheckmate-jsonschema-spectral-rules/)
- [ItsaCheckmate API Rules](https://apis.io/rules/itsacheckmate/itsacheckmate-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Itsacheckmate Authentication](https://apis.io/security/itsacheckmate/itsacheckmate-authentication/)
- [Itsacheckmate Domain Security](https://apis.io/security/itsacheckmate/itsacheckmate-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Itsacheckmate Plans Pricing](https://apis.io/plans/itsacheckmate/itsacheckmate-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Itsacheckmate Rate Limits](https://apis.io/rate-limits/itsacheckmate/itsacheckmate-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Itsacheckmate Finops](https://apis.io/finops/itsacheckmate/itsacheckmate-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.itsacheckmate.com/)
- [Documentation](https://www.itsacheckmate.com/solutions/marketplace-for-developers)
- [API reference](https://openapi-itsacheckmate.readme.io/reference/getting-started)
- [Pricing](https://support.itsacheckmate.com/hc/en-us/articles/8105450179867-Checkmate-Pricing)
- [Support](https://support.itsacheckmate.com/hc/en-us)
- [Blog](https://www.itsacheckmate.com/blog)

## API Evangelist rating

**Kin Score 32.3** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 22.3 |
| Contract governance | 27.3 |
| Operational transparency | 11.8 |
| Developer ergonomics | 40.5 |
| Access clarity | 18.4 |

**Agent readiness 26.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/itsacheckmate/](https://apis.io/providers/itsacheckmate/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for ItsaCheckmate: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/itsacheckmate/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
