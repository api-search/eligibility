---
api_specs:
- filename: claroty-authenticate-api-openapi.yml
  format: yaml
  label: Claroty Authenticate API
  slug: claroty-authenticate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-authenticate-api-openapi.yml
- filename: claroty-health-api-openapi.yml
  format: yaml
  label: Claroty Health API
  slug: claroty-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-health-api-openapi.yml
- filename: claroty-is-key-registered-api-openapi.yml
  format: yaml
  label: Claroty Is Key Registered API
  slug: claroty-is-key-registered-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-is-key-registered-api-openapi.yml
- filename: claroty-jwks-api-openapi.yml
  format: yaml
  label: Claroty Jwks API
  slug: claroty-jwks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-jwks-api-openapi.yml
- filename: claroty-jwthenticator-api-openapi.yml
  format: yaml
  label: Claroty JW Thenticator API
  slug: claroty-jwthenticator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-jwthenticator-api-openapi.yml
- filename: claroty-refresh-api-openapi.yml
  format: yaml
  label: Claroty Refresh API
  slug: claroty-refresh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-refresh-api-openapi.yml
- filename: claroty-register-key-api-openapi.yml
  format: yaml
  label: Claroty Register Key API
  slug: claroty-register-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-register-key-api-openapi.yml
- filename: claroty-validate-api-openapi.yml
  format: yaml
  label: Claroty Validate API
  slug: claroty-validate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-validate-api-openapi.yml
- filename: claroty-validate-request-api-openapi.yml
  format: yaml
  label: Claroty Validate Request API
  slug: claroty-validate-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-validate-request-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is available only to individuals who (a) are at least eighteen (18) years old; and (b) possess the legal capacity to enter into these Terms
    type: individual
  minimum_age:
    text: at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: (a) use the Site and/or the Content for any illegal, immoral, unlawful and/or unauthorized purposes
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
name: Claroty
provenance_date: '2026-11-09'
provider_name: Claroty
provider_slug: claroty
slug: claroty-eligibility
source_date: '2026-11-09'
source_filename: claroty-eligibility.yml
source_heading: Eligibility
source_page: https://www.claroty.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Claroty\naid: claroty\nurl: https://www.claroty.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is available only to individuals who (a) are at least eighteen (18) years old; and (b) possess\n    the legal capacity to enter into these Terms\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: (a) use the Site and/or the Content for any illegal, immoral, unlawful and/or unauthorized purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/claroty/eligibility/claroty-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Claroty's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- OT Security
- Cyber-Physical Systems
- IoT Security
- Industrial Control Systems
- Threat Detection
- Exposure Management
- Healthcare Security
---
