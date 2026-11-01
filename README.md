# Yale University

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

Yale University is a private Ivy League research university in New Haven, Connecticut, United States, ranked #16 in the QS World University Rankings. Its programmable footprint is real but sharply bifurcated, and it is one of the few institutions in this cohort that operates its own contracts rather than only buying them. On the open side Yale runs LUX (lux.collections.yale.edu), a cross-collection discovery platform serving Linked Art JSON-LD over more than 41 million cultural-heritage records, built and published openly by Yale's own project-lux engineering organization; Yale Dataverse (dataverse.yale.edu), a self-hosted research-data repository on Yale's own AWS infrastructure minting DOIs under Yale's own DataCite prefix 10.60600; IIIF Presentation 3.0 manifests from Yale University Library Digital Collections; and a signed SAML 2.0 Shibboleth identity-provider metadata document registered in InCommon. All four were probed live and answer anonymously. On the closed side, developers.yale.edu is a genuine institution-operated developer portal documenting eleven Enterprise (SOA) services and four Portal APIs — Buildings, Courses, Course Subjects, GatewayServiceMetrics — but Yale's own pages describe these as internal and private: the SOA tier uses basic authentication via a provisioned service account, and a Portal API key can only be requested by someone holding a valid Yale NetID. The gateway at gw.its.yale.edu is live and answers an anonymous call with "Invalid API Key", so the surface exists and is simply not open. An earlier profile of this repository described the Courses Web Service as returning "public information"; that is corrected here. Two further surfaces carry Yale's name but not Yale's engineering and are recorded as tenant relationships rather than as Yale contracts: EliScholar (elischolar.library.yale.edu), whose OAI-PMH endpoint is live but whose Identify response gives an Elsevier bepress Digital Commons admin contact, and the course catalog at courses.yale.edu / catalog.yale.edu, which is a Leepfrog CourseLeaf tenancy. Yale publishes no open-data portal, no llms.txt and no security.txt.

**Areas:** University · Higher Education · Education · United States · Ivy League · Research · Research Data · Research Repository · Identity Federation · Library · Cultural Heritage · Linked Data

## Yale University on APIs.io

Everything profiled for Yale University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/yale/](https://apis.io/providers/yale/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [LUX Collections Discovery — Search API](https://apis.io/apis/yale/yale-search-api/) — Search and discovery across LUX scopes, returning Linked Art OrderedCollectionPage documents in JSON-LD. LUX is Yale's own platform: the frontend, middle…
- [LUX Collections Discovery — Documents API](https://apis.io/apis/yale/yale-documents-api/) — Retrieves a single entity from LUX as a Linked Art JSON-LD document by type and identifier. Institution-operated on lux.collections.yale.edu.
- [LUX Collections Discovery — Facets API](https://apis.io/apis/yale/yale-facets-api/) — Faceted aggregation over LUX search results, returning an OrderedCollectionPage of facet values and occurrence counts. Institution-operated on…
- [LUX Collections Discovery — Related API](https://apis.io/apis/yale/yale-related-api/) — Related-entity discovery across LUX, returning an OrderedCollectionPage of documents connected to a given URI. Institution-operated on lux.collections.yale.edu.
- [LUX Collections Discovery — Configuration API](https://apis.io/apis/yale/yale-configuration-api/) — Advanced-search configuration metadata for LUX, describing searchable terms by scope, search options and stop words. Verified 200 returning 43,502 bytes of…
- [Yale API Portal — Portal APIs](https://apis.io/apis/yale/portal/) — Yale's institution-operated developer portal documents four Portal APIs — Buildings (name and location of Yale campus buildings), Courses, Course Subjects…
- [Yale Courses Web Service v3](https://apis.io/apis/yale/courses/) — Returns course-offering information for a given termCode and subjectCode — titles, descriptions, instructors, meeting times, prerequisites and…
- [Yale Enterprise (SOA) Services](https://apis.io/apis/yale/enterprise-soa/) — Eleven services delivered by Yale's Integration Competency Center covering Yale identities (People Hub — PeopleService, GetPeopleService,…
- [EliScholar OAI-PMH (bepress Digital Commons tenancy)](https://apis.io/apis/yale/elischolar/) — EliScholar is Yale's digital platform for scholarly publishing, and its OAI-PMH endpoint is live — Identify returned protocol version 2.0 with…
- [Yale Course Search and University Publications (CourseLeaf tenancy)](https://apis.io/apis/yale/course-catalog/) — Yale Course Search (courses.yale.edu) and the Yale University Publications bulletin (catalog.yale.edu) are the institution's public course-catalog surfaces.…
- [Yale University Federation API](https://apis.io/apis/yale/yale-federation-api/) — SAML 2.0 entity metadata
- [Yale University IIIF API](https://apis.io/apis/yale/yale-iiif-api/) — IIIF Presentation 3.0 manifests for digitized objects
- [Yale University Info API](https://apis.io/apis/yale/yale-info-api/) — Deployment identity, version and metrics

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Yale Agentic Access](https://apis.io/agentic-access/yale/yale-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [LUX Linked Art Entity](https://apis.io/schemas/yale/yale-linkedartentity/)
- [LUX OrderedCollection](https://apis.io/schemas/yale/yale-orderedcollection/)
- [LUX OrderedCollectionPage](https://apis.io/schemas/yale/yale-orderedcollectionpage/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Yale Linkedartentity Structure](https://apis.io/json-structure/yale/yale-linkedartentity-structure/)
- [Yale Orderedcollectionpage Structure](https://apis.io/json-structure/yale/yale-orderedcollectionpage-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Yale Context](https://apis.io/jsonld/yale/yale-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [LUX Yale Collections Discovery Vocabulary](https://apis.io/vocabularies/yale/yale-vocabulary/)

#### Examples (7)

Example requests and responses.

- [Yale Dataverse Info Version Example](https://apis.io/examples/yale/yale-dataverse-info-version-example/)
- [Yale Dataverse Metrics Datasets Example](https://apis.io/examples/yale/yale-dataverse-metrics-datasets-example/)
- [Yale Dataverse Search Example](https://apis.io/examples/yale/yale-dataverse-search-example/)
- [Yale Getdocument Example](https://apis.io/examples/yale/yale-getDocument-example/)
- [Yale Iiif Manifest Example](https://apis.io/examples/yale/yale-iiif-manifest-example/)
- [Yale Search Example](https://apis.io/examples/yale/yale-search-example/)
- [Yale Searchestimate Example](https://apis.io/examples/yale/yale-searchEstimate-example/)

#### Collections (5)

Postman and Open Collection request collections.

- [LUX Yale Collections Discovery Configuration API](https://apis.io/collections/yale/open-yale-configuration-api/)
- [LUX Yale Collections Discovery Configuration Documents API](https://apis.io/collections/yale/open-yale-documents-api/)
- [LUX Yale Collections Discovery Configuration Facets API](https://apis.io/collections/yale/open-yale-facets-api/)
- [LUX Yale Collections Discovery Configuration Related API](https://apis.io/collections/yale/open-yale-related-api/)
- [LUX Yale Collections Discovery Configuration Search API](https://apis.io/collections/yale/open-yale-search-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Yale University — jsonschema rules](https://apis.io/rules/yale/yale-jsonschema-spectral-rules/)
- [Yale University API Rules](https://apis.io/rules/yale/yale-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Yale Authentication](https://apis.io/security/yale/yale-authentication/)
- [Yale Domain Security](https://apis.io/security/yale/yale-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Yale Scopes](https://apis.io/scopes/yale/yale-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Yale Plans Pricing](https://apis.io/plans/yale/yale-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Yale Rate Limits](https://apis.io/rate-limits/yale/yale-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Yale Finops](https://apis.io/finops/yale/yale-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.yale.edu/)
- [Documentation](https://developers.yale.edu/api-documentation)
- [API reference](https://developers.yale.edu/api-documentation/portal-apis)
- [Support](https://developers.yale.edu/frequently-asked-questions)
- [Blog](https://news.yale.edu/news-rss)
- [Terms of service](https://your.yale.edu/policies-procedures)
- [Privacy policy](https://www.yale.edu/privacy-policy)
- [GitHub](https://github.com/yalelibrary)

## API Evangelist rating

**Kin Score 37.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 53.1 |
| Contract governance | 9.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 33.3 |
| Access clarity | 39.5 |

**Agent readiness 20.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | partial |
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

**Regulatory alignment 28.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/yale/](https://apis.io/providers/yale/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Yale University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/yale/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
