---
api_specs:
- filename: xrhealth-auth-api-openapi.yml
  format: yaml
  label: XRHealth Auth API
  slug: xrhealth-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrhealth/openapi/xrhealth-auth-api-openapi.yml
- filename: xrhealth-me-api-openapi.yml
  format: yaml
  label: XRHealth Me API
  slug: xrhealth-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrhealth/openapi/xrhealth-me-api-openapi.yml
- filename: xrhealth-openapi-json-api-openapi.yml
  format: yaml
  label: XRHealth Openapi.json API
  slug: xrhealth-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrhealth/openapi/xrhealth-openapi-json-api-openapi.yml
- filename: xrhealth-well-known-api-openapi.yml
  format: yaml
  label: XRHealth .well Known API
  slug: xrhealth-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrhealth/openapi/xrhealth-well-known-api-openapi.yml
- filename: xrhealth-xrhealth-platform-api-api-openapi.yml
  format: yaml
  label: XRHealth XRHealth Platform API
  slug: xrhealth-xrhealth-platform-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrhealth/openapi/xrhealth-xrhealth-platform-api-api-openapi.yml
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
  - summary: Lawful use only
    text: use the Services only in accordance with applicable laws and government regulations
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
name: XRHealth
provenance_date: '2026-11-10'
provider_name: XRHealth
provider_slug: xrhealth
slug: xrhealth-eligibility
source_date: '2026-11-10'
source_filename: xrhealth-eligibility.yml
source_heading: Eligibility
source_page: https://platform.xr.health/en/p/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: XRHealth\naid: xrhealth\nurl: https://platform.xr.health/en/p/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: use the Services only in accordance with applicable laws and government regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/xrhealth/eligibility/xrhealth-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from XRHealth's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Digital Health
- Telehealth
- Virtual Reality
- Extended Reality
- Medical Devices
- Rehabilitation
- Mental Health
- Patient Authentication
- Healthcare
---
