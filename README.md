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

Maastricht University (UM) is a public research university in Maastricht, Netherlands, founded in 1976 and known for its Problem-Based Learning model. **UM operates no API programme** — no developer portal, no `api.maastrichtuniversity.nl`, no status page, no published versioning or deprecation policy, and no first-party OpenAPI anywhere on its estate. This profile says so plainly, because that is the measurement.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/maastricht/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=maastricht-api-evangelist&utm_content=repo

## Type

- Index
- University — Public Research University
- Consumer / Public

## Tags

University, Higher Education, Education, Netherlands, Europe, Research Data, Research Repository, Identity Federation, OAI-PMH, Open Access, Public Research University

## Who operates what

Every surface below carries an **operator**. `x-operator` says who runs the thing the artifact describes — for a university that is almost never the same answer as who the data belongs to.

### Institution-operated

- **Maastricht University Research Portal OAI-PMH** — `https://cris.maastrichtuniversity.nl/ws/oai`. Keyless OAI-PMH 2.0. Verified live 2026-08-30: all six verbs return 200; six metadata profiles (`oai_dc`, `qdc`, `mods`, `nl_didl`, `xmetadiss`, `oai_cerif_openaire`); OpenAIRE CRIS sets plus year-partitioned and `withFiles` publication sets; `completeListSize` 798,420; resolvable ORCID iDs in the CERIF person records. The CRIS software underneath is Elsevier Pure, but this harvesting surface carries Maastricht's own sets, profiles and administrative contact on Maastricht's own domain.
- **Maastricht University Identity Provider (ADFS / SURFconext / eduGAIN)** — `https://login.maastrichtuniversity.nl/adfs`. Publishes OpenID Connect discovery **and** signed SAML 2.0 federation metadata, both unauthenticated. Its entityID is carried in SURFconext's national IdP metadata with `shibmd:Scope` values `maastrichtuniversity.nl` and `unimaas.nl`, placing it in eduGAIN. This is the surface class universities operate by definition and almost never appears in an API catalog.
- **Maastricht University GitLab** — `https://gitlab.maastrichtuniversity.nl/api/v4`. Self-hosted; `GET /api/v4/projects` returns 200 with real project JSON to an unauthenticated client.
- **Institute of Data Science open source** — 220 public repositories of institution-authored data-science tooling.
- **DataHub Maastricht (Research IT) open source** — 38 repositories behind UM's own iRODS-based research data service. The `mdr.datahubmaastricht.nl` front end is an SPA that returns 200 with an HTML shell on every path including `/openapi.json` — a soft-200, not an API.
- **University Library open source** — 46 repositories of RDM support material and open-source software.

### Tenant relationships (their data, a vendor's contract)

- **DataverseNL** — Maastricht's research data lives in a collection (alias `maastricht`) inside the shared national Dataverse installation. There is no `maastricht.dataverse.nl`; it is a path-based collection on a multi-institution platform.
- **Elsevier Pure REST API** — `/ws/api` canonicalises to `api.elsevierpure.com`; `/ws/api/524/openapi.yaml` returns 401. Elsevier's contract, Elsevier's version numbering.
- **Instructure Canvas** — `canvas.maastrichtuniversity.nl`, `GET /api/v1/accounts` returns 401.
- **OCLC WorldCat Discovery** — `maastrichtuniversity.on.worldcat.org`. No institution-operated library API exists.

## What changed on 2026-08-30

This repository was first profiled on 2026-06-03, before the enrichment pipeline had an ownership check. What it catalogued was **upstream Dataverse's contract**: one DataverseNL OpenAPI split by `refine-openapis` into 36 per-tag specifications, each registered as a separate "Maastricht University *tag* API" entry carrying a **fabricated `baseURL` of `https://cris.maastrichtuniversity.nl/ws/oai`** — the Pure OAI-PMH endpoint, which is not a Dataverse REST API and does not serve those paths. Thirty-six times the apparent footprint, on a host that does not run the software, for a contract at least six other institutions in this catalog also ship.

Removed: 36 per-tag OpenAPIs, the pristine `_original` Dataverse source, 73 collections, and every JSON Schema, JSON Structure, example, Spectral ruleset, vocabulary, JSON-LD context and agentic-access file derived from them — 123 files.

Added: one **derived** OpenAPI for the live OAI-PMH endpoint (derived by API Evangelist from probes, not published by Maastricht), plus conformance, authentication, scopes, errors, vocabulary and lifecycle artifacts built from live responses.

**A correct re-profile of a vendor-attributed institution lowers its score. That is the pipeline working.**

## Domain standards (Kin Score `education` regime)

| Standard | Status | Evidence |
|---|---|---|
| `oai-pmh` | conformant | `?verb=Identify` returns `protocolVersion 2.0`; all six verbs 200; `?verb=Bogus` returns `badVerb` |
| `orcid` | conformant | `<cerif:ORCID>` elements in `openaire_cris_persons` records |
| `saml` | conformant | Signed SAML 2.0 metadata at `login.maastrichtuniversity.nl`, entity in SURFconext/eduGAIN |
| `shibboleth` | partial | `shibmd:Scope` in the federation entry — the metadata profile conforms, the IdP is ADFS |

Not found, recorded explicitly: `scim`, `lti`, `oneroster`, `ed-fi`, `caliper`, `qti`, `datacite`, `crossref`. See [conformance/maastricht-conformance.yml](conformance/maastricht-conformance.yml).

## Artifacts

- [openapi/maastricht-oai-pmh-openapi.yml](openapi/maastricht-oai-pmh-openapi.yml) — derived, method `derived`
- [conformance/maastricht-conformance.yml](conformance/maastricht-conformance.yml)
- [authentication/maastricht-authentication.yml](authentication/maastricht-authentication.yml)
- [scopes/maastricht-scopes.yml](scopes/maastricht-scopes.yml)
- [errors/maastricht-errors.yml](errors/maastricht-errors.yml)
- [vocabulary/maastricht-vocabulary.yml](vocabulary/maastricht-vocabulary.yml)
- [lifecycle/maastricht-lifecycle.yml](lifecycle/maastricht-lifecycle.yml)
- [plans/maastricht-plans-pricing.yml](plans/maastricht-plans-pricing.yml)
- [rate-limits/maastricht-rate-limits.yml](rate-limits/maastricht-rate-limits.yml)
- [finops/maastricht-finops.yml](finops/maastricht-finops.yml)
- [security/maastricht-domain-security.yml](security/maastricht-domain-security.yml)

## Absences confirmed by probe

No `api.`, `data.`, `open.`, `developer.`, `developers.`, `sis.`, `portal.` or `status.` host resolves under `maastrichtuniversity.nl`. No course catalog, timetable or registrar API. No CKAN or Socrata open-data portal. `dataverse.nl` serves an Anubis bot-challenge to scripted clients on every path — live, but unreadable without solving it, and a vendor's surface regardless.

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-30

## Maintainers

- Kin Lane — kin@apievangelist.com
