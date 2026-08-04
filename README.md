# Commodity Futures Trading Commission (commodity-futures-trading-commission)

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

The Commodity Futures Trading Commission (CFTC) is the U.S. federal regulator for commodity futures and options markets. The CFTC publishes the weekly Commitments of Traders (COT) report and other public data through a Socrata Open Data API at publicreporting.cftc.gov, providing programmatic access to Legacy, Disaggregated, Traders in Financial Futures, and Supplemental Commodity Index Trader datasets, as well as swap data and large trader reports.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/commodity-futures-trading-commission/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/commodity-futures-trading-commission/refs/heads/main/apis.yml)

## Tags

- CFTC
- Commitments of Traders
- Federal Government
- Financial
- Futures
- Open Data
- SODA
- Trading

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### CFTC Commitments of Traders SODA API

Programmatic access to the CFTC Commitments of Traders weekly reports via the Socrata Open Data API hosted at publicreporting.cftc.gov. Datasets cover Legacy, Disaggregated, Traders in Financial Futures, and Supplemental Commodity Index Trader formats for both futures-only and combined futures-and-options positions.

- **Human URL:** [https://publicreporting.cftc.gov/](https://publicreporting.cftc.gov/)
- **Base URL:** `https://publicreporting.cftc.gov/resource`

#### Tags

- COT
- Open Data
- SODA
- Trading

#### Properties

- [Documentation](https://publicreporting.cftc.gov/)
- [Reference](https://www.cftc.gov/MarketReports/CommitmentsofTraders/index.htm)
- [Reference](https://dev.socrata.com/foundry/publicreporting.cftc.gov)
- [OpenAPI](openapi/cftc-cot-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cftc-cot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cftc-cot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/cftc-cot-schema.json) — [JSON Schema](https://json-schema.org/specification)

### CFTC Swap Data Repositories

The CFTC oversees Swap Data Repositories (SDRs) that collect and maintain swap transaction records as required by the Dodd-Frank Act. SDRs publish certain real-time public data and the CFTC publishes aggregate weekly swap reports.

- **Human URL:** [https://www.cftc.gov/MarketReports/SwapsReports/index.htm](https://www.cftc.gov/MarketReports/SwapsReports/index.htm)
- **Base URL:** `https://www.cftc.gov`

#### Tags

- Dodd-Frank
- Swaps
- SDR
- Reporting

#### Properties

- [Documentation](https://www.cftc.gov/MarketReports/SwapsReports/index.htm)
- [Reference](https://www.cftc.gov/IndustryOversight/DataRepositories/index.htm)
- [Postman Collection](collections/cftc-cot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cftc-cot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CFTC Bank Participation and Large Trader Reports

The CFTC publishes monthly Bank Participation reports and other aggregate large trader reports that complement the weekly COT data. These reports are released as PDFs and HTML tables on cftc.gov.

- **Human URL:** [https://www.cftc.gov/MarketReports/BankParticipationReports/index.htm](https://www.cftc.gov/MarketReports/BankParticipationReports/index.htm)
- **Base URL:** `https://www.cftc.gov`

#### Tags

- Bank Participation
- Large Trader
- Reporting

#### Properties

- [Documentation](https://www.cftc.gov/MarketReports/BankParticipationReports/index.htm)
- [Reference](https://www.cftc.gov/MarketReports/index.htm)
- [Postman Collection](collections/cftc-cot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cftc-cot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/commodity-futures-trading-commission)
- [Website](https://www.cftc.gov/)
- [JSON-LD](json-ld/cftc-cot-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/cftc-cot-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](vocabulary/cftc-cot-vocabulary.yml)
- [Spectral Rules](rules/cftc-cot-rules.yml)
- [Capability](capabilities/query-commitments-of-traders.yml)
- [Documentation](https://publicreporting.cftc.gov/)
- [Reference](https://www.cftc.gov/MarketReports/CommitmentsofTraders/index.htm)
- [Privacy Policy](https://www.cftc.gov/About/AbouttheCFTC/Privacy.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
