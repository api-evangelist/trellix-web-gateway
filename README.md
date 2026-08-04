# Trellix Web Gateway (trellix-web-gateway)

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

Trellix Web Gateway (formerly McAfee Web Gateway) provides advanced threat protection and secure web access for enterprises. It offers URL filtering, malware detection, data loss prevention, SSL inspection, and cloud security capabilities through a comprehensive web security platform with REST APIs for appliance management, policy configuration, and security reporting.

**APIs.json:** [https://www.trellix.com/products/web-gateway/](https://www.trellix.com/products/web-gateway/)

## Tags

- Cybersecurity
- Data Loss Prevention
- Enterprise Security
- Malware Protection
- Network Security
- SSL Inspection
- Threat Protection
- URL Filtering
- Web Gateway

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Trellix Web Gateway REST API

RESTful API for managing and configuring Trellix Web Gateway appliances, including policy management, system administration, file handling, custom list management, and session-based authentication tasks.

- **Human URL:** [https://docs.trellix.com/bundle/web-gateway-product-guide](https://docs.trellix.com/bundle/web-gateway-product-guide)
- **Base URL:** `https://<mwg-server>:<port>/Konfigurator/REST`

#### Tags

- Appliance Management
- Configuration Management
- Enterprise Security
- Gateway
- Threat Protection
- Web Security

#### Properties

- [Documentation](https://docs.trellix.com/bundle/web-gateway-rest-api-guide)
- [OpenAPI](https://docs.trellix.com/api/web-gateway/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.trellix.com/bundle/web-gateway-rest-api-guide/page/authentication.html)
- [Postman Collection](https://www.postman.com/trellix/workspace/trellix-public/collection/web-gateway-api) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [OpenAPI](openapi/trellix-web-gateway-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trellix-web-gateway-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trellix-web-gateway-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trellix Web Gateway Reporting API

API for accessing web traffic logs, security events, threat analytics, and generating custom reports from Web Gateway data.

- **Human URL:** [https://docs.trellix.com/bundle/web-gateway-reporting-guide](https://docs.trellix.com/bundle/web-gateway-reporting-guide)
- **Base URL:** `https://<mwg-server>:<port>/reporter/api`

#### Tags

- Analytics
- Logs
- Reporting
- Security Events

#### Properties

- [Documentation](https://docs.trellix.com/bundle/web-gateway-reporting-api)
- [API Reference](https://docs.trellix.com/api/web-gateway/reporting/)
- [OpenAPI](openapi/trellix-web-gateway-reporting-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trellix-web-gateway-reporting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trellix-web-gateway-reporting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trellix Web Gateway Policy API

API for creating, updating, and managing security policies, rules, and configurations for web filtering, anti-malware, SSL inspection, DLP, and threat prevention.

- **Human URL:** [https://docs.trellix.com/bundle/web-gateway-policy-guide](https://docs.trellix.com/bundle/web-gateway-policy-guide)
- **Base URL:** `https://<mwg-server>:<port>/Konfigurator/REST/policy`

#### Tags

- Configuration
- DLP
- Policy Management
- Rules
- Security Policies

#### Properties

- [Documentation](https://docs.trellix.com/bundle/web-gateway-policy-api)
- [Examples](https://github.com/trellix-enterprise/mwg-api-examples)
- [OpenAPI](openapi/trellix-web-gateway-policy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trellix-web-gateway-policy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trellix-web-gateway-policy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/trellixsecurity)
- [Getting Started](https://docs.trellix.com/bundle/web-gateway-getting-started)
- [Developer  Portal](https://developer.trellix.com/)
- [Changelog](https://docs.trellix.com/bundle/web-gateway-release-notes)
- [Status Page](https://status.trellix.com/)
- [Terms of Service](https://www.trellix.com/legal/terms-of-use/)
- [Privacy Policy](https://www.trellix.com/privacy/)
- [Portal](https://www.trellix.com/login/)
- [SDK](https://github.com/trellix-enterprise/mwg-sdk)
- [JSON-LD](json-ld/trellix-web-gateway-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/trellix-web-gateway-security-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trellix-web-gateway-rule-set-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/trellix-web-gateway-security-event-structure.json)
- [Spectral Rules](rules/trellix-web-gateway-spectral-rules.yml)
- [Vocabulary](vocabulary/trellix-web-gateway-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
