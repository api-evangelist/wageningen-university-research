# Wageningen University & Research (wageningen-university-research)

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

Wageningen University & Research (WUR) is a Dutch university and research institution in Wageningen, Netherlands, specializing in healthy food and living environment and ranked #100 in the QS World University Rankings 2025. This repository catalogs WUR's public developer/API footprint as an APIs.json provider profile for the API Evangelist network. WUR's public APIs are concentrated in the agri-food research domain rather than a single central platform.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/wageningen-university-research/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=wageningen-university-research-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Agriculture, Agri-Food, Open Data, Netherlands

## APIs

- **AgroDataCube API v2** — Token-based REST API over a large open/derived agri-food data collection (crop fields, soil, weather, NDVI, altitude, raster). Docs: https://documenter.getpostman.com/view/3284162/TVeqd7aa — Home: https://agrodatacube.wur.nl/
- **AgroDataCube API v1 (legacy)** — Earlier version of the AgroDataCube REST API, still available. Docs: https://documenter.getpostman.com/view/3862510/RVnSHh76
- **WFBR Food API** — API for scientific data about food products, via Wageningen Food & Biobased Research's Azure API Management developer portal. Docs: https://euw-apim-fism-001-p.developer.azure-api.net/apis

## Plans / Rate Limits / FinOps

- Plans: [plans/wageningen-university-research-plans-pricing.yml](plans/wageningen-university-research-plans-pricing.yml)
- Rate Limits: [rate-limits/wageningen-university-research-rate-limits.yml](rate-limits/wageningen-university-research-rate-limits.yml)
- FinOps: [finops/wageningen-university-research-finops.yml](finops/wageningen-university-research-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.wur.nl/
- GitHub: https://github.com/WUR-AI
- LinkedIn: https://www.linkedin.com/school/wageningen-university/
- Developer Portal (WFBR): https://euw-apim-fism-001-p.developer.azure-api.net/
- Review: [review.yml](review.yml)

## Notes

- No central institution-wide API platform was found; cataloged APIs are domain-specific (agri-food).
- AgroDataCube requires a free access token (registration form) sent as an HTTP header; free for non-commercial use under CC BY-NC-SA.
- The Pure-powered Research Portal (research.wur.nl) and eDepot repository resolve, but their web-service/OAI-PMH endpoints returned HTTP 500/400 and are not openly usable, so no Pure/OAI API was cataloged.
- WUR maintains multiple research-group GitHub orgs (e.g. WUR-AI, WUR-ABE); WUR-AI is listed as the representative GitHub property. No fabricated endpoints are included.

## Maintainers

- Kin Lane — kin@apievangelist.com
