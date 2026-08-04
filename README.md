# ItsaCheckmate (itsacheckmate)

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

ItsaCheckmate (Checkmate) is restaurant middleware that connects point-of-sale systems to delivery marketplaces and ordering channels, providing two-way integration, menu management, and consolidated reporting across 50+ POS systems and 100+ ordering platforms for tens of thousands of restaurant locations. Through its Marketplace for Developers, Checkmate offers a self-service open REST API that lets technology partners build a single integration to read and write menus, orders, and locations across many POS systems. The API uses OAuth-style token authentication with short-lived, scoped access and refresh tokens, ready-to-use Postman collections, and an llms.txt index for AI agents.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/itsacheckmate/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/itsacheckmate/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Restaurant
- Point Of Sale
- Online Ordering
- Delivery
- Menus
- Orders
- Integration

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-02

## APIs

### Marketplace for Developers API

An open REST API that lets developers build one integration and read and write menus, orders, and locations across 50+ POS systems. Resources include location activation, menu retrieval, single and group order submission, special hours and closures, and token management. Authentication uses OAuth-style short-lived, scoped access tokens with refresh tokens, defaulting to 24-hour token expiry.

- **Human URL:** [https://openapi-itsacheckmate.readme.io/reference/getting-started](https://openapi-itsacheckmate.readme.io/reference/getting-started)
- **Base URL:** `https://sandbox-api.itsacheckmate.com`

#### Tags

- Point Of Sale
- Menus
- Orders
- Locations

#### Properties

- [OpenAPI](openapi/itsacheckmate-marketplace-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itsacheckmate-marketplace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itsacheckmate-marketplace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://openapi-itsacheckmate.readme.io/reference/getting-started)
- [Getting Started](https://openapi-itsacheckmate.readme.io/reference/getting-started)
- [Postman](https://openapi-itsacheckmate.readme.io/reference/get-started-with-postman-api) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Webhook](https://openapi-itsacheckmate.readme.io/reference/update-notice)
- [L L Ms Txt](https://openapi-itsacheckmate.readme.io/llms.txt)

## Common Properties

- [Website](https://www.itsacheckmate.com/)
- [Documentation](https://www.itsacheckmate.com/solutions/marketplace-for-developers)
- [API Reference](https://openapi-itsacheckmate.readme.io/reference/getting-started)
- [Pricing](https://support.itsacheckmate.com/hc/en-us/articles/8105450179867-Checkmate-Pricing)
- [Support](https://support.itsacheckmate.com/hc/en-us)
- [Blog](https://www.itsacheckmate.com/blog)
- [LinkedIn](https://www.linkedin.com/company/itsacheckmate)
- [L L Ms Txt](https://openapi-itsacheckmate.readme.io/llms.txt)
- [Rules](rules/itsacheckmate-spectral-rules.yml)
- [Vocabulary](vocabulary/itsacheckmate-vocabulary.yml)
- [JSON-LD](json-ld/itsacheckmate-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Plans](plans/itsacheckmate-plans-pricing.yml)
- [Rate Limits](rate-limits/itsacheckmate-rate-limits.yml)
- [Fin Ops](finops/itsacheckmate-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
