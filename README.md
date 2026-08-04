# Live Oak Bank (live-oak-bank)

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

Live Oak Bank (Live Oak Banking Company) is a digital, branchless, North Carolina state-chartered commercial bank founded in 2008 and headquartered in Wilmington, NC, operating as the primary subsidiary of Live Oak Bancshares, Inc. (NYSE: LOB). It is the largest originator of U.S. SBA 7(a) loans in the country and serves small businesses in all 50 states with SBA and commercial lending, high-yield savings, CDs, and business checking with treasury services. It runs a cloud-native Finxact (Fiserv) core with an Apiture digital banking platform, and in 2024 launched an in-house embedded-banking / Banking-as-a-Service program.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/live-oak-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/live-oak-bank/refs/heads/main/apis.yml)

## Open-Finance / API Posture

Live Oak Bank's API surface is **real but partner-gated**. A production AWS API gateway operates at `api.liveoak.bank` — it returns `MissingAuthenticationToken` (HTTP 403) to unauthenticated callers and advertises Live-Oak-specific `lob-identity-id` / `lob-foreign-entity-id` CORS headers, consistent with its embedded-banking / BaaS program. However:

- **No public developer portal.** `developer.liveoak.bank` does not resolve, and `/developers` on the main site returns 404.
- **No downloadable OpenAPI/Swagger** and **no public API reference** are published.
- The official GitHub organization ([liveoakbank](https://github.com/liveoakbank)) has **0 public repositories**.
- Embedded-banking access is contractual (partner onboarding via sales), not self-serve.
- Consumer-permissioned data access is available through **account aggregators**, not a first-party public API.
- **No documented FDX participation** and **no stated CFPB Section 1033** data-access posture were found publicly as of this profile.

As such, this is an **identity + honest posture** record. There are no public `apis[]` entries because Live Oak exposes no publicly documented API surface.

## Tags

- Financial Services
- Banking
- United States
- Small Business Lending
- SBA
- Embedded Banking
- Banking-as-a-Service
- Digital Bank
- Open Finance

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None publicly documented. Live Oak's embedded-banking API (`api.liveoak.bank`) is partner-gated with no public documentation, OpenAPI, or self-serve onboarding.

## Common Properties

- [Website](https://www.liveoak.bank/)
- [Blog](https://resources.liveoak.bank/blog)
- [Support](https://support.liveoak.bank/)
- [Privacy Policy](https://www.liveoak.bank/online-privacy-notice/)
- [LinkedIn](https://www.linkedin.com/company/live-oak-bank)
- [GitHub Organization](https://github.com/liveoakbank)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
