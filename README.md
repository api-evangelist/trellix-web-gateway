# Trellix Web Gateway

Trellix Web Gateway (formerly McAfee Web Gateway) provides advanced threat protection and secure web access for enterprises. It offers URL filtering, malware detection, data loss prevention, SSL inspection, and cloud security capabilities. REST APIs are available for appliance management, policy configuration, and security reporting.

**Website:** [https://www.trellix.com/products/web-gateway/](https://www.trellix.com/products/web-gateway/)  
**Docs:** [https://docs.trellix.com/bundle/web-gateway-rest-api-guide](https://docs.trellix.com/bundle/web-gateway-rest-api-guide)  
**Developer Portal:** [https://developer.trellix.com/](https://developer.trellix.com/)

## APIs

### Trellix Web Gateway REST API

RESTful API for managing and configuring Web Gateway appliances, including system administration, configuration management, file handling, and custom list management.

- **Base URL:** `https://<mwg-server>:<port>/Konfigurator/REST`
- **Authentication:** Session cookie (JSESSIONID) via `/login`
- **OpenAPI:** [openapi/trellix-web-gateway-rest-openapi.yml](openapi/trellix-web-gateway-rest-openapi.yml)

### Trellix Web Gateway Reporting API

API for accessing web traffic logs, security events, threat analytics, and generating custom reports.

- **Base URL:** `https://<mwg-server>:<port>/reporter/api`
- **Authentication:** Session cookie (JSESSIONID)
- **OpenAPI:** [openapi/trellix-web-gateway-reporting-openapi.yml](openapi/trellix-web-gateway-reporting-openapi.yml)

### Trellix Web Gateway Policy API

API for managing security policies, rule sets, URL filtering, anti-malware, SSL inspection, DLP, and authentication configuration.

- **Base URL:** `https://<mwg-server>:<port>/Konfigurator/REST/policy`
- **Authentication:** Session cookie (JSESSIONID)
- **OpenAPI:** [openapi/trellix-web-gateway-policy-openapi.yml](openapi/trellix-web-gateway-policy-openapi.yml)

## Artifacts

| Type | File |
|---|---|
| OpenAPI (REST) | [openapi/trellix-web-gateway-rest-openapi.yml](openapi/trellix-web-gateway-rest-openapi.yml) |
| OpenAPI (Reporting) | [openapi/trellix-web-gateway-reporting-openapi.yml](openapi/trellix-web-gateway-reporting-openapi.yml) |
| OpenAPI (Policy) | [openapi/trellix-web-gateway-policy-openapi.yml](openapi/trellix-web-gateway-policy-openapi.yml) |
| JSON Schema (Security Event) | [json-schema/trellix-web-gateway-security-event-schema.json](json-schema/trellix-web-gateway-security-event-schema.json) |
| JSON Schema (Rule Set) | [json-schema/trellix-web-gateway-rule-set-schema.json](json-schema/trellix-web-gateway-rule-set-schema.json) |
| JSON Structure (Security Event) | [json-structure/trellix-web-gateway-security-event-structure.json](json-structure/trellix-web-gateway-security-event-structure.json) |
| JSON-LD Context | [json-ld/trellix-web-gateway-context.jsonld](json-ld/trellix-web-gateway-context.jsonld) |
| Spectral Rules | [rules/trellix-web-gateway-spectral-rules.yml](rules/trellix-web-gateway-spectral-rules.yml) |
| Vocabulary | [vocabulary/trellix-web-gateway-vocabulary.yml](vocabulary/trellix-web-gateway-vocabulary.yml) |

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/web-gateway-rest-api.yaml](capabilities/shared/web-gateway-rest-api.yaml) | Core appliance management (system, configuration, lists, logs) |
| [capabilities/shared/web-gateway-policy-api.yaml](capabilities/shared/web-gateway-policy-api.yaml) | Policy management (rules, URL filter, anti-malware, SSL, DLP) |
| [capabilities/shared/web-gateway-reporting-api.yaml](capabilities/shared/web-gateway-reporting-api.yaml) | Reporting (traffic logs, security events, statistics) |

### Workflow Capabilities

| File | Description |
|---|---|
| [capabilities/web-security-operations.yaml](capabilities/web-security-operations.yaml) | SOC security operations (event investigation, threat monitoring, log analysis) |
| [capabilities/web-policy-management.yaml](capabilities/web-policy-management.yaml) | Policy configuration (rule sets, URL filtering, anti-malware, SSL, DLP) |

## Examples

- [examples/trellix-web-gateway-get-security-events-example.json](examples/trellix-web-gateway-get-security-events-example.json)

## Common Properties

- [Getting Started](https://docs.trellix.com/bundle/web-gateway-getting-started)
- [Developer Portal](https://developer.trellix.com/)
- [Change Log](https://docs.trellix.com/bundle/web-gateway-release-notes)
- [Status](https://status.trellix.com/)
- [Terms of Service](https://www.trellix.com/legal/terms-of-use/)
- [Privacy Policy](https://www.trellix.com/privacy/)
- [Portal](https://www.trellix.com/login/)
- [SDK](https://github.com/trellix-enterprise/mwg-sdk)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com

## Tags

Cybersecurity, Data Loss Prevention, Enterprise Security, Malware Protection, Network Security, SSL Inspection, Threat Protection, URL Filtering, Web Gateway
