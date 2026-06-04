# Yale University (yale)

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
