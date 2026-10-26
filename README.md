# Yale University (yale)

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

Yale University is a private Ivy League research university in New Haven, Connecticut, United States,
ranked #16 in the QS World University Rankings. This repository catalogs Yale's public developer and
API footprint as an [APIs.json](https://apisjson.org) profile. It is maintained under the API
Evangelist **university pipeline**, which settles *who operates* each surface before saving any
contract — because for a university most apparent APIs are a vendor's contract running under the
institution's name.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/yale/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=yale-api-evangelist&utm_content=repo

## Type

- university / Private Research University / Index / Consumer / 3rd-Party

## Tags

University, Higher Education, Education, United States, Ivy League, Research, Research Data,
Research Repository, Identity Federation, Library, Cultural Heritage, Linked Data, IIIF, Course
Catalog

## Surfaces, by operator

Every entry in `apis.yml` carries `x-operator`. `institution` means Yale runs the thing the contract
describes. `tenant` means the data and the identity are Yale's but a vendor operates the endpoint.

### Institution-operated and publicly callable

- **LUX Collections Discovery API** (Search, Documents, Facets, Related, Configuration) — Linked Art
  JSON-LD over 41M+ cultural-heritage records at `lux.collections.yale.edu`. The whole stack is
  Yale-built and openly published by the `project-lux` organization. Verified 200; a search for
  `gold` returned 53,387 objects.
  [Docs](https://github.com/project-lux/lux-marklogic/blob/main/docs/lux-backend-api-usage.md) ·
  [Source](https://github.com/project-lux)
- **Yale Dataverse Repository API** — self-hosted Dataverse 6.10.1 at `dataverse.yale.edu` on Yale's
  own AWS infrastructure, 279 published datasets, DOIs minted under Yale's own DataCite prefix
  `10.60600`. [Site](https://dataverse.yale.edu/)
- **Digital Collections IIIF** — IIIF Presentation 3.0 manifests from `collections.library.yale.edu`,
  operated by Yale University Library on its own infrastructure with the stack published by
  `yalelibrary`. [Docs](https://iiif.io/guides/guides/collections.library.yale.edu/)
- **Identity Federation metadata** — signed SAML 2.0 EntityDescriptor at
  `auth.yale.edu/idp/shibboleth`, registered in InCommon and reachable through eduGAIN. Universities
  publish this consistently and catalog it almost never.

### Institution-operated and gated

- **Yale Portal APIs** — Buildings, Courses, Course Subjects, GatewayServiceMetrics. Live; an
  anonymous call returns HTTP 400 `Invalid API Key`. A key requires a Yale NetID.
  [Docs](https://developers.yale.edu/api-documentation/portal-apis)
- **Yale Courses Web Service v3** — course offerings by term and subject.
  [Docs](https://developers.yale.edu/courseswebservicev3)
- **Yale Enterprise (SOA) Services** — eleven ICC-delivered services (People Hub, Chart of Accounts,
  Workday Supervisory Orgs), basic auth via provisioned service account.
  [Docs](https://developers.yale.edu/api-documentation/enterprise-soa-services)

### Tenant — Yale's data, a vendor's contract

- **EliScholar OAI-PMH** — live OAI-PMH 2.0 at `elischolar.library.yale.edu`, but the host CNAMEs to
  `dcyalelib.bepress.com` and Identify gives `dc-support@elsevier.com`. Elsevier bepress Digital
  Commons. The relationship is recorded; the vendor's contract is not saved here.
- **Yale Course Search / University Publications** — `courses.yale.edu` and `catalog.yale.edu` are
  Leepfrog CourseLeaf tenancies.

## Artifacts

- [OpenAPI](openapi/) (+ [pristine pre-refine copies](openapi/_original/))
- [Authentication](authentication/yale-authentication.yml) · [Scopes](scopes/yale-scopes.yml) ·
  [Errors](errors/yale-errors.yml) · [Lifecycle](lifecycle/yale-lifecycle.yml)
- [Education-regime conformance](conformance/yale-domain-standards.yml) — shibboleth, saml, datacite,
  orcid confirmed institution-operated; oai-pmh confirmed but tenant-operated
- [JSON Schema](json-schema/) · [JSON-LD](json-ld/) · [Vocabulary](vocabulary/) · [Rules](rules/) ·
  [Examples](examples/) · [Collections](collections/)
- [Plans & Pricing](plans/yale-plans-pricing.yml) · [Rate Limits](rate-limits/yale-rate-limits.yml) ·
  [FinOps](finops/yale-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.yale.edu/
- Developer Portal: https://developers.yale.edu/
- Research Repository: https://dataverse.yale.edu/
- Library Catalog: https://collections.library.yale.edu/
- Course Catalog: https://courses.yale.edu/
- Identity Federation: https://auth.yale.edu/idp/shibboleth
- Research Computing: https://research.computing.yale.edu/
- AI Policy: https://ai.yale.edu/
- GitHub (Library): https://github.com/yalelibrary
- Source Code (LUX): https://github.com/project-lux
- LinkedIn: https://www.linkedin.com/school/yale-university/

## Notes

Re-profiled 2026-08-19 under the university pipeline. Every URL in this profile was probed live on
that date and every pointer in `apis.yml` returned 200 (LinkedIn returns its standard 999 bot
challenge, which grades live).

Three things are recorded honestly rather than smoothed over:

1. **Yale Dataverse's OAI-PMH endpoint is broken.** `/oai?verb=Identify` and
   `/oai?verb=ListMetadataFormats` both return HTTP 503 with a raw Payara error page instead of an
   OAI-PMH response. This is the one surface where Yale itself would be the OAI-PMH operator, and it
   is not scored as conformant.
2. **The Dataverse software's own OpenAPI is deliberately not saved here.** `dataverse.yale.edu/openapi`
   serves a 526 KB document titled "Dataverse API" that is identical on every Dataverse installation
   worldwide. Saving it would credit Yale with IQSS's engineering. The contract in `openapi/` describes
   only endpoints actually called against Yale's deployment.
3. **A prior description of the Courses Web Service as returning "public information" is corrected.**
   The payload is public information; the surface is not public access.

No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
