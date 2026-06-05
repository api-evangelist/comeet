# Comeet (comeet)

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
