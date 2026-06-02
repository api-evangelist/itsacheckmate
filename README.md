# ItsaCheckmate (itsacheckmate)

ItsaCheckmate (Checkmate) is restaurant middleware that connects point-of-sale systems to delivery marketplaces and ordering channels, providing two-way integration, menu management, and consolidated reporting across 50+ POS systems and 100+ ordering platforms for tens of thousands of restaurant locations. Through its Marketplace for Developers, Checkmate offers a self-service open REST API that lets technology partners build a single integration to read and write menus, orders, and locations across many POS systems. The API uses OAuth-style token authentication with short-lived, scoped access and refresh tokens, ready-to-use Postman collections, and an llms.txt index for AI agents.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/itsacheckmate/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

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

**Human URL:** [https://openapi-itsacheckmate.readme.io/reference/getting-started](https://openapi-itsacheckmate.readme.io/reference/getting-started)

#### Tags:

 - Point Of Sale
 - Menus
 - Orders
 - Locations

#### Properties

- [OpenAPI](openapi/itsacheckmate-marketplace-api.yml)
- [Documentation](https://openapi-itsacheckmate.readme.io/reference/getting-started)
- [GettingStarted](https://openapi-itsacheckmate.readme.io/reference/getting-started)
- [Postman](https://openapi-itsacheckmate.readme.io/reference/get-started-with-postman-api)
- [Update Notice Webhook](https://openapi-itsacheckmate.readme.io/reference/update-notice)
- [LLMsTxt](https://openapi-itsacheckmate.readme.io/llms.txt)
- [NaftikoCapability](capabilities/marketplace-api-oauth.yaml)
- [NaftikoCapability](capabilities/marketplace-api-locations.yaml)
- [NaftikoCapability](capabilities/marketplace-api-menus.yaml)
- [NaftikoCapability](capabilities/marketplace-api-orders.yaml)

## Common Properties

- [Website](https://www.itsacheckmate.com/)
- [Documentation](https://www.itsacheckmate.com/solutions/marketplace-for-developers)
- [APIReference](https://openapi-itsacheckmate.readme.io/reference/getting-started)
- [Pricing](https://support.itsacheckmate.com/hc/en-us/articles/8105450179867-Checkmate-Pricing)
- [Support](https://support.itsacheckmate.com/hc/en-us)
- [Blog](https://www.itsacheckmate.com/blog)
- [LinkedIn](https://www.linkedin.com/company/itsacheckmate)
- [LLMsTxt](https://openapi-itsacheckmate.readme.io/llms.txt)
- [Rules](rules/itsacheckmate-spectral-rules.yml)
- [Vocabulary](vocabulary/itsacheckmate-vocabulary.yml)
- [JSONLD](json-ld/itsacheckmate-context.jsonld)
- [Plans](plans/itsacheckmate-plans-pricing.yml)
- [RateLimits](rate-limits/itsacheckmate-rate-limits.yml)
- [FinOps](finops/itsacheckmate-finops.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [ItsaCheckmate Marketplace for Developers API](openapi/itsacheckmate-marketplace-api.yml)

### JSON Schema

14 schema files derived from the OpenAPI components in [json-schema/](json-schema/).

### JSON Structure

14 JSON Structure files derived from the JSON Schemas in [json-structure/](json-structure/).

### JSON-LD

- [ItsaCheckmate Context](json-ld/itsacheckmate-context.jsonld)

### Examples

14 example payloads in [examples/](examples/).

## Capabilities

Self-contained Naftiko capabilities, one per business surface, each with inline REST and MCP adapters.

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [ItsaCheckmate — OAuth](capabilities/marketplace-api-oauth.yaml) | Marketplace for Developers API | 2 | Integration Partner |
| [ItsaCheckmate — Locations](capabilities/marketplace-api-locations.yaml) | Marketplace for Developers API | 2 | Integration Partner |
| [ItsaCheckmate — Menus](capabilities/marketplace-api-menus.yaml) | Marketplace for Developers API | 1 | Menu Manager |
| [ItsaCheckmate — Orders](capabilities/marketplace-api-orders.yaml) | Marketplace for Developers API | 1 | Order Integrator |

## Vocabulary

- [ItsaCheckmate Vocabulary](vocabulary/itsacheckmate-vocabulary.yml) — Unified taxonomy mapping 4 resources, 4 actions, 4 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [ItsaCheckmate Spectral Ruleset](rules/itsacheckmate-spectral-rules.yml) — 34 rules across 11 categories enforcing ItsaCheckmate API conventions

## Plans, Rate Limits & FinOps

- [Plans & Pricing](plans/itsacheckmate-plans-pricing.yml) — API Commons Plans 0.1
- [Rate Limits](rate-limits/itsacheckmate-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/itsacheckmate-finops.yml) — FinOps Framework / FOCUS aligned

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
