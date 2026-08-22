# University of Cambridge (university-of-cambridge)

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
