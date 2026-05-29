# FRED (fred)

Economic data from the Federal Reserve Bank of St. Louis — the Federal Reserve Economic Data (FRED) API. Programmatic access to 800,000+ time series across Categories, Releases, Series, Sources, and Tags endpoint families, plus the underlying Series Observations endpoint and the companion GeoFRED Maps API.

**URL:** [https://fred.stlouisfed.org/docs/api/fred/](https://fred.stlouisfed.org/docs/api/fred/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Finance, Government, Economic Data, Federal Reserve, Time Series, Open Data, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-28

## APIs

### FRED API

Core REST API for the Federal Reserve Economic Data (FRED) database. Five endpoint families — Categories, Releases, Series, Sources, Tags — plus Series Observations for the underlying time-series values. Supports XML and JSON response formats, real-time periods (ALFRED), frequency aggregation, and unit transformations.

**Human URL:** [https://fred.stlouisfed.org/docs/api/fred/](https://fred.stlouisfed.org/docs/api/fred/)

**Base URL:** `https://api.stlouisfed.org/fred`

#### Tags

- Finance, Economic Data, Time Series, Categories, Releases, Series, Sources, Tags

#### Properties

- [Documentation](https://fred.stlouisfed.org/docs/api/fred/)
- [Overview](https://fred.stlouisfed.org/docs/api/fred/overview.html)
- [API Key](https://fred.stlouisfed.org/docs/api/api_key.html)
- [Terms of Service](https://fred.stlouisfed.org/legal/)
- [Real-Time Periods](https://fred.stlouisfed.org/docs/api/fred/realtime_period.html)
- [OpenAPI](openapi/fred-openapi.yml)

#### Naftiko Capabilities

- [FRED Categories](capabilities/fred-categories.yaml) — 6 operations
- [FRED Releases](capabilities/fred-releases.yaml) — 9 operations
- [FRED Series](capabilities/fred-series.yaml) — 9 operations
- [FRED Observations](capabilities/fred-observations.yaml) — 1 operation
- [FRED Sources](capabilities/fred-sources.yaml) — 3 operations
- [FRED Tags](capabilities/fred-tags.yaml) — 3 operations

### FRED Maps API (GeoFRED)

Geographic / regional view of FRED economic data. Series-group metadata, regional-data lookups across geographies (state, county, MSA, country, census tract, etc.), and GeoJSON shape files for cartographic rendering of FRED indicators.

**Human URL:** [https://fred.stlouisfed.org/docs/api/geofred/](https://fred.stlouisfed.org/docs/api/geofred/)

**Base URL:** `https://api.stlouisfed.org/geofred`

#### Tags

- Finance, Economic Data, Geographic, Maps, GeoJSON

#### Properties

- [Documentation](https://fred.stlouisfed.org/docs/api/geofred/)
- [API Key](https://fred.stlouisfed.org/docs/api/api_key.html)
- [OpenAPI](openapi/fred-geofred-openapi.yml)

#### Naftiko Capabilities

- [GeoFRED Shapes](capabilities/geofred-shapes.yaml) — 1 operation
- [GeoFRED Series Group](capabilities/geofred-series-group.yaml) — 1 operation
- [GeoFRED Series Data](capabilities/geofred-series-data.yaml) — 1 operation
- [GeoFRED Regional Data](capabilities/geofred-regional-data.yaml) — 1 operation

## Common Properties

- [Website](https://fred.stlouisfed.org)
- [Documentation](https://fred.stlouisfed.org/docs/api/fred/)
- [API Key](https://fred.stlouisfed.org/docs/api/api_key.html)
- [Terms of Service](https://fred.stlouisfed.org/legal/)
- [Privacy Policy](https://www.stlouisfed.org/privacy-notice-and-terms-of-use)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Blog](https://fredblog.stlouisfed.org/)
- [Twitter](https://twitter.com/stlouisfed)
- [GitHub (stlouisfed)](https://github.com/stlouisfed)
- [MCP Server (stefanoamorelli/fred-mcp-server)](https://github.com/stefanoamorelli/fred-mcp-server)
- [MCP Server (Jaldekoa/mcp-fredapi)](https://github.com/Jaldekoa/mcp-fredapi)
- [MCP Server (cfdude/mcp-fred)](https://github.com/cfdude/mcp-fred)
- [MCP Server (kablewy/fred-mcp-server)](https://github.com/kablewy/fred-mcp-server)
- [MCP Server (shanehull/fred-mcp — full coverage)](https://github.com/shanehull/fred-mcp)
- [MCP Server (QuentinCody/fred-mcp-server)](https://github.com/QuentinCody/fred-mcp-server)
- [US Gov Open Data MCP (includes FRED)](https://github.com/lzinga/us-gov-open-data-mcp)
- [Python SDK — fredapi](https://pypi.org/project/fredapi/)
- [Python SDK — pyfredapi](https://pypi.org/project/pyfredapi/)
- [Python SDK — fred-py-api](https://pypi.org/project/fred-py-api/)
- [Python SDK — pystlouisfed](https://pypi.org/project/pystlouisfed/)
- [R SDK — fredr](https://cran.r-project.org/package=fredr)
- [Go SDK — ChrisSwanson/fred](https://github.com/ChrisSwanson/fred)
- [Rust SDK — fred-rs](https://crates.io/crates/fred-rs)
- [Node.js / TypeScript SDK — fred-api-client](https://github.com/iamkanishka/fred-api-client)
- [.NET SDK — Xaye.Fred (archived)](https://www.nuget.org/packages/Xaye.Fred)
- [Elixir SDK — Fred](https://hex.pm/packages/fred)

## Features

| Name | Description |
|------|-------------|
| 800,000+ Time Series | Programmatic access to more than 800,000 US and international economic time series, sourced from 100+ data providers. |
| Real-Time / ALFRED Vintages | Every endpoint supports realtime_start and realtime_end parameters, letting consumers reproduce the data as it existed on a historical date (Archival FRED). |
| Frequency Aggregation | The series/observations endpoint can resample higher-frequency data into lower-frequency series using average, sum, or end-of-period aggregation. |
| Unit Transformations | Built-in transformations (level, change, percent change, percent change from year ago, compounded annual rate, natural log) applied at request time. |
| Multiple Response Formats | XML (default), JSON, CSV, and Excel (xlsx) responses controlled by the file_type query parameter. |
| Five-Family Endpoint Surface | Discoverable taxonomy via Categories (hierarchy), Releases (publication schedule), Series (indicators), Sources (originating institutions), and Tags (faceted classification). |
| GeoFRED Maps API | Companion geographic API returning regional indicator values and GeoJSON shape files for state, county, MSA, country, and census-tract geographies. |
| Free Public API | Single self-service tier. Free API key with a 120 req/min cap. |

## Use Cases

| Name | Description |
|------|-------------|
| Macroeconomic Dashboards | Pull GDP, CPI, unemployment, federal funds rate, and related indicators on a scheduled cadence. |
| Investment Research and Backtesting | Pull historical series (Treasury yields, commodity prices, FX rates) to backtest trading strategies or seed macro factor models. |
| Academic and Policy Research | Reproduce published research using point-in-time ALFRED vintages. |
| AI / LLM Tool Use | Connect a FRED MCP server to Claude, Cursor, or another MCP host so an agent can answer ad-hoc economic questions with authoritative data. |
| Embedded Economic Charts | Hydrate charts in news sites, fintech apps, or government dashboards directly from the FRED observations endpoint. |
| Regional Economic Analysis | Use the GeoFRED API to render state-level or county-level heat maps. |

## Integrations

| Name | Description |
|------|-------------|
| Bureau of Labor Statistics (BLS) | A large share of FRED series originates with BLS (CPI, employment, productivity). |
| Bureau of Economic Analysis (BEA) | National-accounts series (GDP, personal income, trade balance). |
| U.S. Census Bureau | Demographic, housing, and survey series. |
| U.S. Treasury | Daily Treasury yield curve and debt series. |
| Federal Reserve Board (FRB H.15) | Interest-rate releases (H.15) and balance-sheet series (H.4.1). |
| OECD | International cross-country series. |
| World Bank | Global development indicators republished through FRED. |
| Eurostat | European Union economic and demographic statistics. |
| International Monetary Fund (IMF) | Cross-country financial-soundness and balance-of-payments series. |

## Solutions

| Name | Description |
|------|-------------|
| FRED Add-In for Microsoft Excel | Official Excel plug-in that pulls FRED series into spreadsheets without writing API calls. |
| FRED Mobile Apps | Free FRED iOS and Android apps for browsing series, releases, and categories on mobile. |
| FRED Graph Embeds | Interactive charts that can be embedded directly into web pages. |
| FRASER Historical Archive | Companion archive of historical economic data and policy documents. |
| ALFRED (Archival FRED) | Point-in-time vintages of every FRED series. |
| FRED API MCP Ecosystem | A dozen community-built MCP servers expose the FRED API to AI agents (Claude Desktop, Cursor, VS Code Copilot). |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI (2 specs, 35 operations)

- [FRED API](openapi/fred-openapi.yml) — 31 operations across Categories, Releases, Series, Observations, Sources, Tags
- [FRED Maps API (GeoFRED)](openapi/fred-geofred-openapi.yml) — 4 operations across Shapes, Series Group, Series Data, Regional Data

### JSON Schema (21 schemas)

Stored in [`json-schema/`](json-schema/). Includes Category, CategoryList, Release, ReleaseList, ReleaseDate, ReleaseDateList, ReleaseTable, Series, SeriesList, Observation, ObservationList, Source, SourceList, Tag, TagList, VintageDateList, Shape, ShapeCollection, SeriesGroup, RegionalDatum, RegionalDataResult.

### JSON Structure (21 structures)

Stored in [`json-structure/`](json-structure/). 1:1 conversion of the JSON Schema files into the JSON Structure (json-structure.org) format with first-class typing.

### JSON-LD (3 contexts)

- [Unified FRED + GeoFRED context](json-ld/fred-context.jsonld) — 21 types, 59 terms
- [FRED API context](json-ld/fred-api-context.jsonld) — 16 types, 44 terms
- [GeoFRED Maps API context](json-ld/fred-geofred-api-context.jsonld) — 5 types, 20 terms

### Examples (21 example payloads)

Stored in [`examples/`](examples/). One realistic JSON example per schema, suitable for fixtures, mock data, and SDK tests.

## Capabilities

Naftiko capabilities — each file is a self-contained business surface that bundles a `consumes` block (FRED HTTP), a `rest` exposer (Spectral-compliant /v1 resources), and an `mcp` exposer (verb-noun tools).

| Capability | API | Operations | File |
|------------|-----|-----------:|------|
| FRED Categories | FRED API | 6 | [capabilities/fred-categories.yaml](capabilities/fred-categories.yaml) |
| FRED Releases | FRED API | 9 | [capabilities/fred-releases.yaml](capabilities/fred-releases.yaml) |
| FRED Series | FRED API | 9 | [capabilities/fred-series.yaml](capabilities/fred-series.yaml) |
| FRED Observations | FRED API | 1 | [capabilities/fred-observations.yaml](capabilities/fred-observations.yaml) |
| FRED Sources | FRED API | 3 | [capabilities/fred-sources.yaml](capabilities/fred-sources.yaml) |
| FRED Tags | FRED API | 3 | [capabilities/fred-tags.yaml](capabilities/fred-tags.yaml) |
| GeoFRED Shapes | FRED Maps API (GeoFRED) | 1 | [capabilities/geofred-shapes.yaml](capabilities/geofred-shapes.yaml) |
| GeoFRED Series Group | FRED Maps API (GeoFRED) | 1 | [capabilities/geofred-series-group.yaml](capabilities/geofred-series-group.yaml) |
| GeoFRED Series Data | FRED Maps API (GeoFRED) | 1 | [capabilities/geofred-series-data.yaml](capabilities/geofred-series-data.yaml) |
| GeoFRED Regional Data | FRED Maps API (GeoFRED) | 1 | [capabilities/geofred-regional-data.yaml](capabilities/geofred-regional-data.yaml) |

Total: 10 capabilities, 35 operations, every operation exposed as both a REST endpoint and an MCP tool.

## Vocabulary

- [FRED Vocabulary](vocabulary/fred-vocabulary.yml) — Unified taxonomy mapping 9 resources, 20 actions, 10 workflows, and 7 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [FRED Spectral Ruleset](rules/fred-rules.yml) — 36 rules across info, paths, operations, parameters, responses, schemas, security, HTTP methods, and general quality enforcing FRED API conventions (snake_case parameters, HTTPS, api_key query, "FRED" prefixed summaries, GET-only, etc.).

## Plans

- [FRED Plans & Pricing](plans/fred-plans-pricing.yml) — Single free public tier (`fred-free`). No paid SKUs, no metering. Access is gated only by a free API key.

## Rate Limits

- [FRED Rate Limits](rate-limits/fred-rate-limits.yml) — 120 requests / minute / key, shared across the FRED API and the GeoFRED Maps API. HTTP 429 on throttling; HTTP 503 for transient issues. Bulk downloads recommended for warehouse-scale ingestion.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
