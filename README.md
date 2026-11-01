# Wageningen University & Research

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

Wageningen University & Research (WUR) is the Dutch public research university and research foundation for healthy food and the living environment, in Wageningen, Netherlands, and ranked #100 in the QS World University Rankings 2025. Its programmable footprint is real but small, and it sits in the research institutes rather than in a central developer platform: AgroDataCube, run by Wageningen Environmental Research at agrodatacube.wur.nl, is a token-gated REST API over an open agri-food data collection for the Netherlands; the WFBR API Portal, run by Wageningen Food & Biobased Research on its own Azure API Management instance, publishes a Food API behind registration and WUR's own terms of use; the university library operates a complete, keyless OAI-PMH 2.0 endpoint at library.wur.nl/oai over "Wageningen University & Research Publications", serving Dublin Core, MODS, DIDL and OpenAIRE/DataCite metadata; and Wageningen Marine Research runs an OGC WMS/WFS GeoServer at opengeodata.wmr.wur.nl. WUR also operates two SAML identity providers registered in SURFconext and therefore eduGAIN. What WUR does not have is a central API programme: there is no institution-wide developer portal, no course-catalog or registrar API (api.wur.nl and ssc.wur.nl resolve but time out from the public internet), and no published OpenAPI of its own — every OpenAPI in this repository is ours, derived from WUR's Postman collections and from live probes. The Research Portal at research.wur.nl is an Elsevier Pure tenancy: WUR's data and DOIs, Elsevier's contract, and it is recorded here as a tenant relationship rather than credited to WUR as engineering.

**Areas:** Education · Higher Education · University · Research · Research Data · Agriculture · Agrifood · Geospatial · Library · Open Data · Identity Federation · Netherlands

## Wageningen University & Research on APIs.io

Everything profiled for Wageningen University & Research is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/wageningen-university-research/](https://apis.io/providers/wageningen-university-research/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [WFBR Food API](https://apis.io/apis/wageningen-university-research/wfbr-food-api/) — API for scientific data about food products, published by Wageningen Food & Biobased Research (WFBR) through WUR's own Azure API Management instance.…
- [Wageningen University & Research Altitude API](https://apis.io/apis/wageningen-university-research/wageningen-university-research-altitude-api/) — The Altitude API from AgroDataCube v2, operated by Wageningen Environmental Research — 1 operation for altitude zonal statistics.
- [Wageningen University & Research KPI API](https://apis.io/apis/wageningen-university-research/wageningen-university-research-kpi-api/) — The KPI API from AgroDataCube v2, operated by Wageningen Environmental Research — 2 operations for crop-rotation and greenness indicators.
- [Wageningen University & Research Raster API](https://apis.io/apis/wageningen-university-research/wageningen-university-research-raster-api/) — The Raster API from AgroDataCube v2, operated by Wageningen Environmental Research — 4 operations returning GeoTIFF altitude and NDVI imagery.
- [Wageningen University & Research Retrieve API](https://apis.io/apis/wageningen-university-research/wageningen-university-research-retrieve-api/) — The Retrieve API from AgroDataCube v2, operated by Wageningen Environmental Research — 18 operations over fields, crops, soils, meteo data and code lists.
- [Wageningen University & Research Return API](https://apis.io/apis/wageningen-university-research/wageningen-university-research-return-api/) — The Return API from AgroDataCube v2, operated by Wageningen Environmental Research — 9 operations returning meteo stations, regions, soil types and source…
- [WUR Research Portal (Elsevier Pure tenancy)](https://apis.io/apis/wageningen-university-research/wageningen-research-portal-pure/) — Institutional research portal and CRIS for WUR publications, projects, datasets and researcher profiles, running on Elsevier Pure. Listed as a tenant…
- [Wageningen University & Research OAI PMH API](https://apis.io/apis/wageningen-university-research/wageningen-university-research-oai-pmh-api/) — The six OAI-PMH 2.0 verbs, all served from the single /oai route.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Wageningen University Research Agentic Access](https://apis.io/agentic-access/wageningen-university-research/wageningen-university-research-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [AgroDataCube Field FeatureCollection](https://apis.io/schemas/wageningen-university-research/wageningen-university-research-field/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Wageningen University Research Field Structure](https://apis.io/json-structure/wageningen-university-research/wageningen-university-research-field-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Wageningen University Research Context](https://apis.io/jsonld/wageningen-university-research/wageningen-university-research-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [AgroDataCube Vocabulary](https://apis.io/vocabularies/wageningen-university-research/wageningen-university-research-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Wageningen University Research Cropcodes Example](https://apis.io/examples/wageningen-university-research/wageningen-university-research-cropcodes-example/)
- [Wageningen University Research Fields Example](https://apis.io/examples/wageningen-university-research/wageningen-university-research-fields-example/)

#### Collections (5)

Postman and Open Collection request collections.

- [AgroDataCube API v2 Altitude API](https://apis.io/collections/wageningen-university-research/open-wageningen-university-research-altitude-api/)
- [AgroDataCube API v2 KPI API](https://apis.io/collections/wageningen-university-research/open-wageningen-university-research-kpi-api/)
- [AgroDataCube API v2 Raster API](https://apis.io/collections/wageningen-university-research/open-wageningen-university-research-raster-api/)
- [AgroDataCube API v2 Retrieve API](https://apis.io/collections/wageningen-university-research/open-wageningen-university-research-retrieve-api/)
- [AgroDataCube API v2 Return API](https://apis.io/collections/wageningen-university-research/open-wageningen-university-research-return-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Wageningen University & Research — jsonschema rules](https://apis.io/rules/wageningen-university-research/wageningen-university-research-jsonschema-spectral-rules/)
- [Wageningen University & Research API Rules](https://apis.io/rules/wageningen-university-research/wageningen-university-research-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Wageningen University Research Authentication](https://apis.io/security/wageningen-university-research/wageningen-university-research-authentication/)
- [Wageningen University Research Domain Security](https://apis.io/security/wageningen-university-research/wageningen-university-research-domain-security/)
- [Wageningen University Research Vulnerability Disclosure](https://apis.io/security/wageningen-university-research/wageningen-university-research-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Wageningen University Research Plans Pricing](https://apis.io/plans/wageningen-university-research/wageningen-university-research-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Wageningen University Research Rate Limits](https://apis.io/rate-limits/wageningen-university-research/wageningen-university-research-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Wageningen University Research Finops](https://apis.io/finops/wageningen-university-research/wageningen-university-research-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.wur.nl/)
- [API reference](https://documenter.getpostman.com/view/3284162/TVeqd7aa)
- [Terms of service](https://euw-apim-fism-001-p.developer.azure-api.net/terms-of-use)
- [Privacy policy](https://www.wur.nl/en/about-wur/organisation-profile/privacy-cookie-statement-wur)

## API Evangelist rating

**Kin Score 46.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 61.3 |
| Contract governance | 28.0 |
| Operational transparency | 21.1 |
| Developer ergonomics | 38.1 |
| Access clarity | 39.5 |

**Agent readiness 25.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | — |

**Regulatory alignment 38.2** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/wageningen-university-research/](https://apis.io/providers/wageningen-university-research/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Wageningen University & Research: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/wageningen-university-research/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
