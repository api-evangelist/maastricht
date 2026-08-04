# Maastricht University (maastricht)

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
