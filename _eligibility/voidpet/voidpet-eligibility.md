---
api_specs:
- filename: voidpet-discovery-api-openapi.yml
  format: yaml
  label: Voidpet Discovery API
  slug: voidpet-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voidpet/openapi/voidpet-discovery-api-openapi.yml
- filename: voidpet-health-api-openapi.yml
  format: yaml
  label: Voidpet Health API
  slug: voidpet-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voidpet/openapi/voidpet-health-api-openapi.yml
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
  - summary: Framing the website
    text: Without prior approval and written permission, you may not create frames around our Webpages that alter in any way the visual presentation or appearance of our Website.
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
name: Voidpet
provenance_date: '2026-11-10'
provider_name: Voidpet
provider_slug: voidpet
slug: voidpet-eligibility
source_date: '2026-11-10'
source_filename: voidpet-eligibility.yml
source_heading: Eligibility
source_page: https://voidpet.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Voidpet\naid: voidpet\nurl: https://voidpet.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Framing the website\n  text: Without prior approval and written permission, you may not create frames around our Webpages that alter\n    in any way the visual presentation or appearance of our Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/voidpet/eligibility/voidpet-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Voidpet's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Games
- Gaming
- Mental Health
- Wellness
- Discovery
- Agents
- MCP
- Read Only
---
