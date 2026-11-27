---
api_specs:
- filename: boxcompute-ai-openapi.yml
  format: yaml
  label: BoxCompute Customer Sandbox API
  slug: boxcompute-customer-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boxcompute-ai/openapi/boxcompute-ai-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use BoxCompute for an organization, you agree for that organization too.
    type: business
  minimum_age:
    text: You must be at least 18 and able to enter a binding contract.
    value: '18'
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
name: BoxCompute
provenance_date: '2026-11-09'
provider_name: BoxCompute
provider_slug: boxcompute-ai
slug: boxcompute-ai-eligibility
source_date: '2026-11-09'
source_filename: boxcompute-ai-eligibility.yml
source_heading: Eligibility
source_page: https://boxcompute.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BoxCompute\naid: boxcompute-ai\nurl: https://boxcompute.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use BoxCompute for an organization, you agree for that organization too.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to enter a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/boxcompute-ai/eligibility/boxcompute-ai-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from BoxCompute's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Pay-as-you-go
- Sandbox
---
