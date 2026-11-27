---
api_specs:
- filename: echorelay-openapi-generated.yml
  format: yaml
  label: EchoRelay API
  slug: echorelay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/echorelay/openapi/_ae-authored/echorelay-openapi-generated.yml
- filename: echorelay-keys-api-openapi.yml
  format: yaml
  label: EchoRelay Keys API
  slug: echorelay-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/echorelay/openapi/echorelay-keys-api-openapi.yml
- filename: echorelay-projects-api-openapi.yml
  format: yaml
  label: EchoRelay Projects API
  slug: echorelay-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/echorelay/openapi/echorelay-projects-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer in the European Union or United Kingdom, you have a statutory right to withdraw from a distance contract within 14 days of purchase.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: EchoRelay
provenance_date: '2026-11-09'
provider_name: EchoRelay
provider_slug: echorelay
slug: echorelay-eligibility
source_date: '2026-11-09'
source_filename: echorelay-eligibility.yml
source_heading: Eligibility
source_page: https://echorelay.dev/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EchoRelay\naid: echorelay\nurl: https://echorelay.dev/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer in the European Union or United Kingdom, you have a statutory right to withdraw from\n    a distance contract within 14 days of purchase.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/echorelay/eligibility/echorelay-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from EchoRelay's own page on 2026-11-09.
synthetic: false
tags:
- Integration
- Platform
- Automation
- No-Code
- Company
---
