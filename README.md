# University of Cambridge (university-of-cambridge)

The University of Cambridge (QS World 2025 #5) has a real, documented developer footprint operated mainly by University Information Services (UIS): a central API Gateway / developer portal, the Lookup/Ibis directory web service, the Raven authentication service (OAuth2 / OpenID Connect), and the Apollo institutional repository (DSpace).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/university-of-cambridge/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-cambridge-api-evangelist&utm_content=repo)

## Type
- **x-type:** Index (Consumer / 3rd-Party)

## Tags
- Education, Higher Education, University, Research, United Kingdom, Identity, API Gateway, Developer Portal

## APIs
- **Lookup / Ibis Web Service API** — Read/write HTTP API over the University people/institutions directory (XML/JSON/text); OpenAPI specs + client libs. Base `https://www.lookup.cam.ac.uk/api/v1/`. [Docs](https://www.lookup.cam.ac.uk/doc/ws-doc/)
- **Raven Authentication** — Central web SSO; OAuth2 / OpenID Connect. [Docs](https://docs.raven.cam.ac.uk/)
- **Cambridge API Gateway** — Card, Student (CamSIS), and HR (CHRIS) REST APIs (ALPHA). [Portal](https://developer.api.apps.cam.ac.uk/)
- **Apollo Repository API (DSpace)** — Open-access repository OAI-PMH + DSpace REST. Base `https://api.repository.cam.ac.uk/server/`.

## Plans, Rate Limits, FinOps
- [Plans](plans/university-of-cambridge-plans-pricing.yml) — Free/open public endpoints; affiliation/credentialed identity APIs.
- [RateLimits](rate-limits/university-of-cambridge-rate-limits.yml) — No published global limit; harvest politely.
- [FinOps](finops/university-of-cambridge-finops.yml) — Non-commercial; no usage-based API billing.

## Timestamps
- **Created:** 2026-06-03
- **Modified:** 2026-06-03

## Common Properties
- [Website](https://www.cam.ac.uk/)
- [Developer Portal](https://developer.api.apps.cam.ac.uk/)
- [Source Code (GitLab)](https://gitlab.developers.cam.ac.uk/)

## Notes
- Apollo OAI-PMH endpoint verified live (HTTP 200). Lookup, Raven, and gateway docs verified live. Gateway Student/HR APIs are documented ALPHA and "not under active development." See [review.yml](review.yml).
- UIS open source migrated from GitHub (github.com/uisautomation, now 404) to a self-hosted GitLab — use GitLab as the canonical source-code property.
- No public API-platform status page was found.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
