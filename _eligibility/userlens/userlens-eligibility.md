---
api_specs:
- filename: userlens-events-api-openapi.yml
  format: yaml
  label: Userlens Events API
  slug: userlens-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/userlens/openapi/userlens-events-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These terms apply to business customers.
    type: business
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
name: Userlens
provenance_date: '2026-11-10'
provider_name: Userlens
provider_slug: userlens
slug: userlens-eligibility
source_date: '2026-11-10'
source_filename: userlens-eligibility.yml
source_heading: Eligibility
source_page: https://userlens.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Userlens\naid: userlens\nurl: https://userlens.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These terms apply to business customers.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/userlens/eligibility/userlens-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Userlens's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Customer Success
- Product Analytics
- AI Agents
- Churn Prediction
- Event Tracking
- B2B SaaS
- Account Intelligence
---
