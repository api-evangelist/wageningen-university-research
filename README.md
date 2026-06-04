# Wageningen University & Research (wageningen-university-research)

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
