# sec-edgar (sec-edgar)

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

SEC EDGAR (Electronic Data Gathering, Analysis, and Retrieval) is the U.S. Securities and Exchange Commission's online database where public companies file mandatory disclosures and other corporate filings.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### SEC EDGAR Full-Text Search API

The SEC EDGAR Full-Text Search API (EFTS) allows searching the full text of all EDGAR filings. Supports keyword search, date range filtering, form type filtering, and entity-based queries returning metadata for matching filings.

- **Human URL:** [https://efts.sec.gov/LATEST/search-index](https://efts.sec.gov/LATEST/search-index)
- **Base URL:** `https://efts.sec.gov`

#### Tags

- Filings
- Finance
- Regulatory
- Search
- SEC

#### Properties

- [Documentation](https://efts.sec.gov/LATEST/search-index)
- [OpenAPI](openapi/sec-edgar-submissions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sec-edgar-submissions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sec-edgar-submissions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEC EDGAR Submissions API

The SEC EDGAR Submissions API returns all company filing metadata (10-K, 10-Q, 8-K, etc.) in JSON format for a given CIK number. Returns recent and historical submission data including form type, filing date, accession numbers, and document indexes.

- **Human URL:** [https://data.sec.gov/submissions/](https://data.sec.gov/submissions/)
- **Base URL:** `https://data.sec.gov`

#### Tags

- Filings
- Finance
- Regulatory
- SEC

#### Properties

- [Documentation](https://data.sec.gov/submissions/)
- [Reference](https://www.sec.gov/developer)
- [OpenAPI](openapi/sec-edgar-submissions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sec-edgar-submissions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sec-edgar-submissions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEC EDGAR XBRL Company Facts API

The SEC EDGAR XBRL Company Facts API delivers structured financial data extracted from XBRL-tagged filings. Returns all reported facts for a company including income statement, balance sheet, and cash flow data in JSON format organized by taxonomy concept.

- **Human URL:** [https://data.sec.gov/api/xbrl/companyfacts/](https://data.sec.gov/api/xbrl/companyfacts/)
- **Base URL:** `https://data.sec.gov/api/xbrl`

#### Tags

- Filings
- Finance
- Regulatory
- SEC
- XBRL

#### Properties

- [Documentation](https://data.sec.gov/api/xbrl/companyfacts/)
- [Reference](https://www.sec.gov/developer)
- [OpenAPI](openapi/sec-edgar-submissions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sec-edgar-submissions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sec-edgar-submissions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEC EDGAR Company Filings API

The SEC EDGAR (Electronic Data Gathering, Analysis, and Retrieval) system provides REST APIs for accessing company filings, XBRL financial data, and full-text search across SEC submissions. APIs deliver 10-K, 10-Q, 8-K, and other filing data in JSON, XML, and XBRL formats.

- **Human URL:** [https://www.sec.gov/developer](https://www.sec.gov/developer)
- **Base URL:** `https://efts.sec.gov`

#### Tags

- Filings
- Finance
- Regulatory
- SEC
- XBRL

#### Properties

- [Documentation](https://www.sec.gov/developer)
- [Reference](https://www.sec.gov/developer)
- [Postman Collection](collections/sec-edgar-submissions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sec-edgar-submissions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/sec-edgar)
- [Portal](https://www.sec.gov/developer)
- [Documentation](https://www.sec.gov/developer)
- [Getting Started](https://www.sec.gov/developer)
- [Privacy Policy](https://www.sec.gov/privacy-policy)
- [Website](https://www.sec.gov/)
- [JSON Schema](json-schema/sec-edgar-filing-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sec-edgar-company-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/sec-edgar-context.jsonld)

## Maintainers

**Email:** kin@apievangelist.com
