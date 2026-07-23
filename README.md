# Live Oak Bank (live-oak-bank)

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
