# Maastricht University (maastricht)

Maastricht University (UM) is an international research university in Maastricht, Netherlands, known for its Problem-Based Learning model and ranked #230 in the QS World University Rankings 2025. UM does not run a unified public developer portal; its confirmed public, machine-readable footprint is standards-based research infrastructure rather than a productized API program.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/maastricht/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=maastricht-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Netherlands, Europe

## APIs

- **Maastricht University Research Portal (Pure) OAI-PMH** — Live OAI-PMH metadata harvesting endpoint for the Pure (Elsevier) CRIS, serving OpenAIRE CERIF 1.2 metadata. Docs: https://cris.maastrichtuniversity.nl/ — Endpoint: https://cris.maastrichtuniversity.nl/ws/oai
- **DataverseNL Research Data API (Maastricht collection)** — Research datasets published through the shared DataverseNL Dataverse instance, which exposes a public native/REST API. Docs: https://guides.dataverse.org/en/latest/api/ — Collection: https://dataverse.nl/dataverse/maastricht
- **Maastricht University Institute of Data Science (Open Source)** — Active public GitHub org with open-source data-science tooling (MOD-API conformance, DSRI docs, SPARQL libraries). https://github.com/MaastrichtU-IDS

## Plans

- [plans/maastricht-plans-pricing.yml](plans/maastricht-plans-pricing.yml)

## Rate Limits

- [rate-limits/maastricht-rate-limits.yml](rate-limits/maastricht-rate-limits.yml)

## FinOps

- [finops/maastricht-finops.yml](finops/maastricht-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.maastrichtuniversity.nl/
- GitHub: https://github.com/MaastrichtU-IDS
- LinkedIn: https://www.linkedin.com/school/maastricht-university/
- Authentication: https://login.maastrichtuniversity.nl/ (Shibboleth/SAML federated SSO)
- Plans, Rate Limits, FinOps, Review pointers (see above and review.yml)

## Notes

All entries were verified against live HTTP responses where possible. The Pure CRIS OAI-PMH endpoint was confirmed live (ListMetadataFormats returns valid OpenAIRE CERIF 1.2 XML); the bare `/ws/` path returns 403 and the Identify verb intermittently 500s. The DataverseNL `/api/info/version` endpoint returns 200, while the Maastricht collection UI sits behind an anti-bot challenge for automated clients. No endpoints, docs URLs, or properties were fabricated — only live-confirmed or documented-standard URLs are listed. UM publishes no general-purpose, self-service public API program.

## Maintainers

- Kin Lane — kin@apievangelist.com
