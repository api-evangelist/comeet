# Comeet (comeet)

Comeet (now Spark Hire Recruit, after Spark Hire's acquisition of Comeet) is a collaborative talent acquisition platform that helps companies post jobs, source and screen candidates, schedule interviews, and coordinate hiring teams. Comeet exposes a public Careers API (used to embed published positions on a custom careers website), a Recruiting API (used by integration partners to manage candidates and pipeline events), and a Hires API (used to push new-hire data into HRIS/onboarding systems).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/comeet/refs/heads/main/apis.yml)

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
- **Modified:** 2026-04-26

## APIs

### Comeet Careers API
Public, tokenized REST API that returns the list of published positions for a Comeet customer (and details for a single position). Powers custom-branded careers websites, embeds jobs into marketing pages, and syndicates openings to third-party job boards.

**Human URL:** [https://developers.comeet.com/reference/careers-api-overview](https://developers.comeet.com/reference/careers-api-overview)

#### Tags

- Careers, Jobs, Recruiting

#### Properties

- [Documentation](https://developers.comeet.com/reference/careers-api-overview)
- [OpenAPI](openapi/comeet-careers-api-openapi.yml)

### Comeet Recruiting API
Partner-scoped REST API for building on top of Spark Hire Recruit. Used by ATS unification platforms (Merge, Finch, etc.) to integrate Comeet companies, positions, candidates, and pipeline events into HR tooling.

**Human URL:** [https://developers.comeet.com/reference/recruiting-api-overview](https://developers.comeet.com/reference/recruiting-api-overview)

#### Tags

- ATS, Candidates, Pipeline, Recruiting

#### Properties

- [Documentation](https://developers.comeet.com/reference/recruiting-api-overview)

### Comeet Hires API
Captures new-hire data from Comeet and pushes employee-profile information into HRIS, onboarding, and IT-provisioning systems the moment a candidate is marked as hired.

**Human URL:** [https://developers.comeet.com/reference/hires-api-overview](https://developers.comeet.com/reference/hires-api-overview)

#### Tags

- HRIS, Hiring, Onboarding

#### Properties

- [Documentation](https://developers.comeet.com/reference/hires-api-overview)

## Common Properties

- [Website](https://www.comeet.com/)
- [Developer Portal](https://developers.comeet.com/)
- [Help Center](https://recruit-support.sparkhire.com/hc/en-us)
- [Parent Company (Spark Hire)](https://www.sparkhire.com/)
- [Privacy Policy](https://www.comeet.com/privacy-policy/)
- [JSON-LD Context](json-ld/comeet-context.jsonld)
- [Position JSON Schema](json-schema/comeet-position-schema.json)
- [Spectral Ruleset](rules/comeet-rules.yml)
- [Naftiko Capabilities](capabilities/comeet-careers-website-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
