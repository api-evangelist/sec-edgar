# Unknown (sec-edgar)

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-03-18 

## APIs

### SEC EDGAR Full-Text Search API
The SEC EDGAR Full-Text Search API (EFTS) allows searching the full text of all EDGAR filings. Supports keyword search, date range filtering, form type filtering, and entity-based queries returning metadata for matching filings.

**Human URL:** [https://efts.sec.gov/LATEST/search-index](https://efts.sec.gov/LATEST/search-index)


#### Tags:

 - Finance, Regulatory, SEC, Filings, Search

#### Properties

- [Documentation](https://efts.sec.gov/LATEST/search-index)
- [OpenAPI](openapi/sec-edgar-submissions-openapi.yml)

### SEC EDGAR Submissions API
The SEC EDGAR Submissions API returns all company filing metadata (10-K, 10-Q, 8-K, etc.) in JSON format for a given CIK number. Returns recent and historical submission data including form type, filing date, accession numbers, and document indexes.

**Human URL:** [https://data.sec.gov/submissions/](https://data.sec.gov/submissions/)


#### Tags:

 - Finance, Regulatory, SEC, Filings

#### Properties

- [Documentation](https://data.sec.gov/submissions/)
- [Reference](https://www.sec.gov/developer)
- [OpenAPI](openapi/sec-edgar-submissions-openapi.yml)

### SEC EDGAR XBRL Company Facts API
The SEC EDGAR XBRL Company Facts API delivers structured financial data extracted from XBRL-tagged filings. Returns all reported facts for a company including income statement, balance sheet, and cash flow data in JSON format organized by taxonomy concept.

**Human URL:** [https://data.sec.gov/api/xbrl/companyfacts/](https://data.sec.gov/api/xbrl/companyfacts/)


#### Tags:

 - Finance, Regulatory, XBRL, SEC, Filings

#### Properties

- [Documentation](https://data.sec.gov/api/xbrl/companyfacts/)
- [Reference](https://www.sec.gov/developer)
- [OpenAPI](openapi/sec-edgar-submissions-openapi.yml)

### SEC EDGAR Company Filings API
The SEC EDGAR (Electronic Data Gathering, Analysis, and Retrieval) system provides REST APIs for accessing company filings, XBRL financial data, and full-text search across SEC submissions. APIs deliver 10-K, 10-Q, 8-K, and other filing data in JSON, XML, and XBRL formats.

**Human URL:** [https://www.sec.gov/developer](https://www.sec.gov/developer)


#### Tags:

 - Finance, Regulatory, XBRL, SEC, Filings

#### Properties

- [Documentation](https://www.sec.gov/developer)
- [Reference](https://www.sec.gov/developer)

## Common Properties

- [Portal](https://www.sec.gov/developer)
- [Documentation](https://www.sec.gov/developer)
- [GettingStarted](https://www.sec.gov/developer)
- [PrivacyPolicy](https://www.sec.gov/privacy-policy)
- [Website](https://www.sec.gov/)
- [JSONSchema](json-schema/sec-edgar-filing-schema.json)
- [JSONSchema](json-schema/sec-edgar-company-schema.json)
- [JSONLDContext](json-ld/sec-edgar-context.jsonld)

## Maintainers

**Email:** kin@apievangelist.com
