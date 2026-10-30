# Maastricht University

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

Maastricht University (UM) is a public research university in Maastricht, Netherlands, founded in 1976 and known internationally for its Problem-Based Learning model. Measured honestly, UM operates no API programme: there is no developer portal, no api.maastrichtuniversity.nl, no status page, no published versioning or deprecation policy, and no first-party OpenAPI anywhere on its estate. What it does operate is a small set of standards-based surfaces on its own domain — a live, keyless OAI-PMH 2.0 harvesting endpoint at cris.maastrichtuniversity.nl serving 798,420 records across six metadata profiles including OpenAIRE CERIF 1.2 with resolvable ORCID iDs; a self-hosted GitLab whose REST API answers unauthenticated project queries; and its own ADFS identity provider publishing both OpenID Connect discovery and signed SAML 2.0 federation metadata, with its entity carried in SURFconext and thereby eduGAIN. Everything else that looks like a Maastricht API is a purchase: research data lives in a collection inside the shared national DataverseNL installation, the CRIS is Elsevier Pure, the LMS is Instructure Canvas, and library discovery is OCLC WorldCat. Those are recorded here as tenant relationships, not as Maastricht's engineering.

**Areas:** University · Higher Education · Education · Netherlands · Europe · Research Data · Research Repository · Identity Federation · OAI-PMH · Open Access · Public Research University

## Maastricht University on APIs.io

Everything profiled for Maastricht University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/maastricht/](https://apis.io/providers/maastricht/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Maastricht University Identity Provider (ADFS / SURFconext / eduGAIN)](https://apis.io/apis/maastricht/identity-federation/) — Maastricht University runs its own identity provider on login.maastrichtuniversity.nl and publishes two machine-readable discovery documents without…
- [Maastricht University GitLab](https://apis.io/apis/maastricht/gitlab/) — Self-hosted GitLab instance on the university's own domain, serving UM research and teaching projects. Its REST API v4 answers unauthenticated…
- [Maastricht University Institute of Data Science (Open Source)](https://apis.io/apis/maastricht/ids-github/) — The Institute of Data Science maintains an active public GitHub organization (220 public repositories) with institution-authored open-source data-science…
- [DataHub Maastricht (Research IT) Open Source](https://apis.io/apis/maastricht/datahub-github/) — DataHub is Maastricht University's own research data management service, built and maintained by UM Research IT on an iRODS foundation. Its GitHub…
- [Maastricht University Library Open Source](https://apis.io/apis/maastricht/library-github/) — The University Library publishes 46 public repositories of research-data-management support material, open training content and open-source software,…
- [Maastricht University research data collection on DataverseNL](https://apis.io/apis/maastricht/dataversenl/) — Maastricht University's published research data lives in a collection (alias "maastricht") inside DataverseNL, the shared national Dataverse installation.…
- [Maastricht University Research Portal (Pure) REST API](https://apis.io/apis/maastricht/pure-ws-api/) — The Elsevier Pure web service on the university's CRIS host. Its documentation page canonicalises to…
- [Maastricht University Canvas LMS](https://apis.io/apis/maastricht/canvas/) — Instructure Canvas tenant on the university's own hostname. GET /api/v1/accounts returned 401 on 2026-08-30, confirming a live Canvas REST API gated behind…
- [Maastricht University Library discovery (OCLC WorldCat)](https://apis.io/apis/maastricht/worldcat-discovery/) — Library discovery runs on OCLC's hosted WorldCat Discovery under an institution-specific subdomain. A textbook tenant: Maastricht's holdings, OCLC's…
- [Maastricht University Harvesting API](https://apis.io/apis/maastricht/maastricht-harvesting-api/) — OAI-PMH 2.0 verbs. Every response is an application/xml OAI-PMH envelope.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Vocabulary (1)

The provider's domain terms, defined.

- [Maastricht University DataverseNL API Vocabulary](https://apis.io/vocabularies/maastricht/maastricht-vocabulary/)

#### Examples (1)

Example requests and responses.

- [Maastricht Adfs Openid Configuration Example](https://apis.io/examples/maastricht/maastricht-adfs-openid-configuration-example/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Maastricht Authentication](https://apis.io/security/maastricht/maastricht-authentication/)
- [Maastricht Domain Security](https://apis.io/security/maastricht/maastricht-domain-security/)
- [Maastricht Vulnerability Disclosure](https://apis.io/security/maastricht/maastricht-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Maastricht Scopes](https://apis.io/scopes/maastricht/maastricht-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Maastricht Plans Pricing](https://apis.io/plans/maastricht/maastricht-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Maastricht Rate Limits](https://apis.io/rate-limits/maastricht/maastricht-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Maastricht Finops](https://apis.io/finops/maastricht/maastricht-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.maastrichtuniversity.nl/)
- [Support](https://www.maastrichtuniversity.nl/contact)
- [Blog](https://www.maastrichtuniversity.nl/news)
- [Terms of service](https://www.maastrichtuniversity.nl/disclaimer)
- [Privacy policy](https://www.maastrichtuniversity.nl/privacy)
- [GitHub](https://github.com/MaastrichtUniversity)

## API Evangelist rating

**Kin Score 26.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 14.3 |
| Contract governance | 13.6 |
| Operational transparency | 7.9 |
| Developer ergonomics | 28.6 |
| Access clarity | 26.3 |

**Agent readiness 18.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
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

**Regulatory alignment 40.2** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/maastricht/](https://apis.io/providers/maastricht/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Maastricht University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/maastricht/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
