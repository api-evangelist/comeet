# Comeet (comeet)

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

Comeet (now Spark Hire Recruit, after Spark Hire's acquisition of Comeet) is a collaborative talent acquisition platform that helps companies post jobs, source and screen candidates, schedule interviews, and coordinate hiring teams. Comeet exposes a public Careers API (used to embed published positions on a custom careers website), a Recruiting API (used by integration partners to manage candidates and pipeline events), and a Hires API (used to push new-hire data into HRIS/onboarding systems).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/comeet/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/comeet/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- ATS
- Candidates
- Careers
- Interviews
- Jobs
- Recruiting
- Talent Acquisition

## Timestamps

- **Created:** 2025-01-07
- **Modified:** 2026-05-19

## APIs

### Comeet Careers API

Public, tokenized REST API that returns the list of published positions for a Comeet customer (and details for a single position). Used to power custom-branded careers websites, embed jobs into marketing pages, and syndicate openings to third-party job boards. Each company's data is scoped by a company UID and a public company token issued by Comeet.

- **Human URL:** [https://developers.comeet.com/reference/careers-api-overview](https://developers.comeet.com/reference/careers-api-overview)
- **Base URL:** `https://www.comeet.co/careers-api/2.0`

#### Tags

- Careers
- Jobs
- Recruiting

#### Properties

- [Documentation](https://developers.comeet.com/reference/careers-api-overview)
- [OpenAPI](openapi/comeet-careers-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/comeet-careers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/comeet-careers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Comeet Recruiting API

The Recruiting API is a partner-scoped REST API for building on top of Spark Hire Recruit (Comeet). It supports listing companies, positions, candidates, and pipeline events, and is the underlying interface used by ATS unification platforms (Merge, Finch, etc.) to integrate Comeet data into HR tooling. Access is granted to approved integration partners.

- **Human URL:** [https://developers.comeet.com/reference/recruiting-api-overview](https://developers.comeet.com/reference/recruiting-api-overview)

#### Tags

- ATS
- Candidates
- Pipeline
- Recruiting

#### Properties

- [Documentation](https://developers.comeet.com/reference/recruiting-api-overview)
- [Postman Collection](collections/comeet-careers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/comeet-careers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Comeet Hires API

The Hires API captures new-hire data from Comeet and pushes employee profile information into downstream HRIS, onboarding, and provisioning systems. It is typically used to trigger an onboarding workflow the moment a candidate is marked as hired.

- **Human URL:** [https://developers.comeet.com/reference/hires-api-overview](https://developers.comeet.com/reference/hires-api-overview)

#### Tags

- HRIS
- Hiring
- Onboarding

#### Properties

- [Documentation](https://developers.comeet.com/reference/hires-api-overview)
- [Postman Collection](collections/comeet-careers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/comeet-careers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/ComeetCo)
- [LinkedIn](https://www.linkedin.com/company/comeet-hire-better-together)
- [Website](https://www.comeet.com/)
- [Portal](https://developers.comeet.com/)
- [Help Center](https://recruit-support.sparkhire.com/hc/en-us)
- [Parent Company](https://www.sparkhire.com/)
- [Privacy Policy](https://www.comeet.com/privacy-policy/)
- [JSON-LD](json-ld/comeet-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/comeet-position-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/comeet-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [L L Ms Txt](https://developers.comeet.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
