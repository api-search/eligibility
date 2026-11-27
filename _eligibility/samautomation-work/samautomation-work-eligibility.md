---
api_specs:
- filename: samautomation-work-openapi-generated.yml
  format: yaml
  label: samautomation-work API
  slug: samautomation-work-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/samautomation-work/openapi/_ae-authored/samautomation-work-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'By placing an order for our services, you warrant that: You are legally capable of entering into binding contracts; You are at least 18 years old'
    type: individual
  minimum_age:
    text: You are at least 18 years old
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
name: samautomation-work
provenance_date: '2026-11-10'
provider_name: samautomation-work
provider_slug: samautomation-work
slug: samautomation-work-eligibility
source_date: '2026-11-10'
source_filename: samautomation-work-eligibility.yml
source_heading: Eligibility
source_page: https://samautomation.work/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: samautomation-work\naid: samautomation-work\nurl: https://samautomation.work/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'By placing an order for our services, you warrant that: You are legally capable of entering into binding\n    contracts; You are at least 18 years old'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/samautomation-work/eligibility/samautomation-work-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from samautomation-work's own page on 2026-11-10.
synthetic: false
tags:
- Video
- Artificial Intelligence
- JSON
- Automation
- Media
---
