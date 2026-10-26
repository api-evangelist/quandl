# Quandl (Nasdaq Data Link) (quandl)

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

Nasdaq Data Link (formerly Quandl) provides REST and streaming APIs for financial and economic data including time-series datasets, tabular datasets, and real-time market data feeds. Datasets cover stock prices, economic indicators, interest rates, commodities, equity fundamentals, options data, and alternative data sets.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/quandl/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/quandl/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Finance
- Market Data
- Economic Data
- Time Series
- Streaming

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-19

## APIs

### Nasdaq Data Link REST API (Time-Series)

Nasdaq Data Link REST API (formerly Quandl) provides access to financial and economic time-series datasets including stock prices, economic indicators, interest rates, and commodity data in JSON, XML, and CSV formats. Authenticated users receive up to 50,000 calls per day.

- **Human URL:** [https://docs.data.nasdaq.com/](https://docs.data.nasdaq.com/)
- **Base URL:** `https://data.nasdaq.com/api/v3`

#### Tags

- Finance
- Economic Data
- Time Series
- Market Data
- REST

#### Properties

- [Documentation](https://docs.data.nasdaq.com/)
- [Reference](https://docs.data.nasdaq.com/)
- [Getting Started](https://docs.data.nasdaq.com/docs/getting-started)
- [Rate Limits](https://docs.data.nasdaq.com/docs/rate-limits)
- [S D Ks](https://docs.data.nasdaq.com/docs/python-installation)
- [OpenAPI](openapi/nasdaq-data-link-timeseries-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nasdaq-data-link-timeseries.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nasdaq-data-link-timeseries.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nasdaq Data Link Tables REST API

Nasdaq Data Link Tables API provides access to tabular financial datasets including equity fundamentals, options data, and alternative data sets. Limited to 10,000 rows per call with pagination support up to 1,000,000 rows via the Python client.

- **Human URL:** [https://docs.data.nasdaq.com/](https://docs.data.nasdaq.com/)
- **Base URL:** `https://data.nasdaq.com/api/v3`

#### Tags

- Finance
- Market Data
- Tables
- REST

#### Properties

- [Documentation](https://docs.data.nasdaq.com/)
- [Rate Limits](https://docs.data.nasdaq.com/docs/rate-limits-1)
- [Postman Collection](collections/nasdaq-data-link-timeseries.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nasdaq-data-link-timeseries.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nasdaq Cloud Data Service (NCDS) Streaming API

Nasdaq Cloud Data Service (NCDS) provides streaming and REST APIs for real-time and delayed market data delivery including equities, options, and fixed income from Nasdaq exchange feeds.

- **Human URL:** [https://github.com/Nasdaq/NasdaqCloudDataService-REST-API](https://github.com/Nasdaq/NasdaqCloudDataService-REST-API)

#### Tags

- Finance
- Market Data
- Streaming
- Real-time
- REST

#### Properties

- [Documentation](https://github.com/Nasdaq/NasdaqCloudDataService-REST-API)
- [S D Ks](https://github.com/Nasdaq/NasdaqCloudDataService-SDK-Python)
- [S D Ks](https://github.com/Nasdaq/NasdaqCloudDataService-SDK-Java)
- [Postman Collection](collections/nasdaq-data-link-timeseries.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nasdaq-data-link-timeseries.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/quandl)
- [Portal](https://data.nasdaq.com/)
- [Documentation](https://docs.data.nasdaq.com/)
- [Getting Started](https://docs.data.nasdaq.com/docs/getting-started)
- [Rate Limits](https://docs.data.nasdaq.com/docs/rate-limits)
- [Website](https://data.nasdaq.com/)
- [Support](https://docs.data.nasdaq.com/docs/contact-support)
- [GitHub Organization](https://github.com/Nasdaq)
- [GitHub Organization](https://github.com/quandl)
- [S D Ks](https://github.com/Nasdaq/data-link-python)
- [S D Ks](https://github.com/Nasdaq/NasdaqCloudDataService-SDK-Python)
- [S D Ks](https://github.com/Nasdaq/NasdaqCloudDataService-SDK-Java)
- [OpenAPI](openapi/nasdaq-data-link-timeseries-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/nasdaq-data-link-dataset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/nasdaq-data-link-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
