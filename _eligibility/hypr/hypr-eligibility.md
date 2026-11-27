---
api_specs:
- filename: hypr-analytics-api-openapi.yml
  format: yaml
  label: HYPR Analytics API
  slug: hypr-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypr/openapi/hypr-analytics-api-openapi.yml
- filename: hypr-control-center-api-openapi.yml
  format: yaml
  label: HYPR Control Center API
  slug: hypr-control-center-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypr/openapi/hypr-control-center-api-openapi.yml
- filename: hypr-fido-api-api-openapi.yml
  format: yaml
  label: HYPR FIDO API
  slug: hypr-fido-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypr/openapi/hypr-fido-api-api-openapi.yml
- filename: hypr-fido2-rp-api-api-openapi.yml
  format: yaml
  label: HYPR FIDO2 RP API
  slug: hypr-fido2-rp-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypr/openapi/hypr-fido2-rp-api-api-openapi.yml
- filename: hypr-radius-api-openapi.yml
  format: yaml
  label: HYPR RADIUS API
  slug: hypr-radius-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypr/openapi/hypr-radius-api-openapi.yml
- filename: hypr-rp-applications-api-openapi.yml
  format: yaml
  label: HYPR RP Applications API
  slug: hypr-rp-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypr/openapi/hypr-rp-applications-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Trial and non-GA services
    text: Non-GA Services are provided for evaluation purposes and not for production use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HYPR
provenance_date: '2026-11-09'
provider_name: HYPR
provider_slug: hypr
slug: hypr-eligibility
source_date: '2026-11-09'
source_filename: hypr-eligibility.yml
source_heading: Eligibility
source_page: https://www.hypr.com/trust-center/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HYPR\naid: hypr\nurl: https://www.hypr.com/trust-center/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Trial and non-GA services\n  text: Non-GA Services are provided for evaluation purposes and not for production use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hypr/eligibility/hypr-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from HYPR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity
- Passwordless
- Authentication
- FIDO
- Security
---
