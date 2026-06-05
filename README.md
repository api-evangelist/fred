# FRED (fred)

The Federal Reserve Economic Data (FRED) API is a public web service operated by the Research Division of the Federal Reserve Bank of St. Louis. It provides programmatic access to more than 800,000 economic time series drawn from 100+ data sources (BLS, BEA, OECD, World Bank, Census, Treasury, Eurostat, Federal Reserve Board, and others). The API exposes five primary endpoint families — Categories, Releases, Series, Sources, and Tags — plus an Observations endpoint that returns the underlying data values for any series, with optional frequency aggregation, unit transformations, and real-time / ALFRED vintage support. A companion Maps (GeoFRED) API surfaces regional data and GeoJSON shape files. All endpoints are HTTPS, return XML or JSON (CSV / Excel for observations), and require a free API key.

**APIs.json:** [https://fred.stlouisfed.org/docs/api/fred/](https://fred.stlouisfed.org/docs/api/fred/)

## Tags

- Finance
- Government
- Economic Data
- Federal Reserve
- Time Series
- Open Data
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-28

## APIs

### FRED API

Core REST API for the Federal Reserve Economic Data (FRED) database. Five endpoint families — Categories, Releases, Series, Sources, Tags — plus Series Observations for the underlying time-series values. Supports XML and JSON response formats, real-time periods (ALFRED), frequency aggregation, and unit transformations.

- **Human URL:** [https://fred.stlouisfed.org/docs/api/fred/](https://fred.stlouisfed.org/docs/api/fred/)
- **Base URL:** `https://api.stlouisfed.org/fred`

#### Tags

- Finance
- Economic Data
- Time Series
- Categories
- Releases
- Series
- Sources
- Tags

#### Properties

- [Documentation](https://fred.stlouisfed.org/docs/api/fred/)
- [Overview](https://fred.stlouisfed.org/docs/api/fred/overview.html)
- [A P I Key](https://fred.stlouisfed.org/docs/api/api_key.html)
- [Terms of Service](https://fred.stlouisfed.org/legal/)
- [Authentication](https://fred.stlouisfed.org/docs/api/api_key.html)
- [Real Time Periods](https://fred.stlouisfed.org/docs/api/fred/realtime_period.html)
- [OpenAPI](openapi/fred-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fred.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fred.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### FRED Maps API (GeoFRED)

Geographic / regional view of FRED economic data. Exposes series-group metadata, regional-data lookups across geographies (state, county, MSA, country, census tract, etc.), and GeoJSON shape files for cartographic rendering of FRED indicators.

- **Human URL:** [https://fred.stlouisfed.org/docs/api/geofred/](https://fred.stlouisfed.org/docs/api/geofred/)
- **Base URL:** `https://api.stlouisfed.org/geofred`

#### Tags

- Finance
- Economic Data
- Geographic
- Maps
- GeoJSON

#### Properties

- [Documentation](https://fred.stlouisfed.org/docs/api/geofred/)
- [A P I Key](https://fred.stlouisfed.org/docs/api/api_key.html)
- [OpenAPI](openapi/fred-geofred-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fred-geofred.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fred-geofred.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://fred.stlouisfed.org)
- [Documentation](https://fred.stlouisfed.org/docs/api/fred/)
- [A P I Key](https://fred.stlouisfed.org/docs/api/api_key.html)
- [Terms of Service](https://fred.stlouisfed.org/legal/)
- [Privacy Policy](https://www.stlouisfed.org/privacy-notice-and-terms-of-use)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Blog](https://fredblog.stlouisfed.org/)
- [Twitter](https://twitter.com/stlouisfed)
- [Git Hub](https://github.com/stlouisfed)
- [Tools](https://github.com/stefanoamorelli/fred-mcp-server)
- [Tools](https://github.com/Jaldekoa/mcp-fredapi)
- [Tools](https://github.com/cfdude/mcp-fred)
- [Tools](https://github.com/kablewy/fred-mcp-server)
- [Tools](https://github.com/shanehull/fred-mcp)
- [Tools](https://github.com/QuentinCody/fred-mcp-server)
- [Tools](https://github.com/lzinga/us-gov-open-data-mcp)
- [SDK](https://pypi.org/project/fredapi/)
- [SDK](https://pypi.org/project/pyfredapi/)
- [SDK](https://pypi.org/project/fred-py-api/)
- [SDK](https://pypi.org/project/pystlouisfed/)
- [SDK](https://cran.r-project.org/package=fredr)
- [SDK](https://github.com/ChrisSwanson/fred)
- [SDK](https://crates.io/crates/fred-rs)
- [SDK](https://github.com/iamkanishka/fred-api-client)
- [SDK](https://www.nuget.org/packages/Xaye.Fred)
- [SDK](https://hex.pm/packages/fred)
- [Rules](rules/fred-rules.yml)
- [Vocabulary](vocabulary/fred-vocabulary.yml)
- [Rate Limits](rate-limits/fred-rate-limits.yml)
- [Plans](plans/fred-plans-pricing.yml)
- [JSON-LD](json-ld/fred-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/fred-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/fred-geofred-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/)
- [Examples](examples/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
