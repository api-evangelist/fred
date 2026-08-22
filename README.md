# FRED (fred)

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
