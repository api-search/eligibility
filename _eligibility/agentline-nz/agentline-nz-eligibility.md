---
api_specs:
- filename: agentline-nz-api-openapi.json
  format: json
  label: Agentline API API
  slug: agentline-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-nz/openapi/_original/agentline-nz-api-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 or older and give us a working email address.
    type: individual
  - text: If you use the service for a business, you confirm you're authorised to bind it
    type: business
  minimum_age:
    text: You must be 18 or older and give us a working email address.
    value: '18'
  restricted_uses:
  - summary: No emergency communications
    text: Don't use the service for emergency communications (it can't reach 111)
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
name: Agentline NZ
provenance_date: '2026-11-09'
provider_name: Agentline NZ
provider_slug: agentline-nz
slug: agentline-nz-eligibility
source_date: '2026-11-09'
source_filename: agentline-nz-eligibility.yml
source_heading: Eligibility
source_page: https://agentline.nz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agentline NZ\naid: agentline-nz\nurl: https://agentline.nz/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 or older and give us a working email address.\n- type: business\n  text: If you use the service for a business, you confirm you're authorised to bind it\nrestricted_uses:\n- summary: No emergency communications\n  text: Don't use the service for emergency communications (it can't reach 111)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ You must be 18 or older and give us a working email address.\n"
source_yaml_url: https://artifacts.apis.io/agentline-nz/eligibility/agentline-nz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Agentline NZ's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Email
- Assistant
- NZ
- Software-as-a-Service
- Company
---
