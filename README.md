# Commodity Futures Trading Commission (commodity-futures-trading-commission)

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
