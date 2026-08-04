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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Yale University is a private Ivy League research university in New Haven, Connecticut, United States, ranked #17 in the QS World University Rankings 2025. This repository catalogs Yale's public developer and API footprint as an [APIs.json](https://apisjson.org) profile, spanning the Yale API Portal (enterprise/SOA and portal APIs), the LUX cross-collection discovery platform, and IIIF digital library collections.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/yale/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=yale-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Cultural Heritage, Linked Data, United States

## APIs

- **Courses Web Service v3** — Public course-offering data (sections) by term and subject, JSON/XML; API key gated to Yale netid holders. [Docs](https://developers.yale.edu/courseswebservicev3)
- **Yale API Portal (Enterprise & Portal APIs)** — Discovery hub for enterprise (SOA), portal (Buildings, Courses, Course Subjects, GatewayServiceMetrics) and vendor APIs; access limited to Yale netid holders. [Docs](https://developers.yale.edu/api-documentation)
- **LUX Yale Collections Discovery API** — Public cross-collection discovery over 41M+ records using Linked Art and IIIF, serving JSON-LD and search endpoints. [Docs](https://lux.collections.yale.edu/content/technology) · [Source](https://github.com/project-lux)
- **Yale Digital Collections IIIF** — IIIF Presentation/Image manifests for digitized library objects. [Docs](https://iiif.io/guides/guides/collections.library.yale.edu/)

## Plans / Rate Limits / FinOps

- [Plans & Pricing](plans/yale-plans-pricing.yml)
- [Rate Limits](rate-limits/yale-rate-limits.yml)
- [FinOps](finops/yale-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.yale.edu/
- Developer Portal: https://developers.yale.edu/
- GitHub (Library): https://github.com/yalelibrary
- Source Code (LUX): https://github.com/project-lux
- LinkedIn: https://www.linkedin.com/school/yale-university/

## Notes

All URLs in this profile were probed live on 2026-06-03. The Yale API Portal and Courses Web Service are real and documented but gated behind a Yale netid and API-key registration, so they cannot be exercised anonymously (the Courses gateway returns HTTP 400 without a valid key/params). The LUX search endpoints responded HTTP 200; some LUX data-document endpoints returned transient 502/504 gateway errors at probe time. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
