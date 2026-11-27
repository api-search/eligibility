---
api_specs:
- filename: assistantgym-com-openapi-generated.yml
  format: yaml
  label: Assistant Gym API
  slug: assistantgym-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assistantgym-com/openapi/_ae-authored/assistantgym-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 or older and allowed to connect the assistant for yourself or your organization.
    type: individual
  - text: allowed to connect the assistant for yourself or your organization
    type: business
  minimum_age:
    text: You must be 18 or older
    value: '18'
  restricted_uses:
  - summary: High-stakes decisions
    text: Do not rely on them alone for decisions about money, safety, health or legal matters.
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
name: Assistant Gym
provenance_date: '2026-11-09'
provider_name: Assistant Gym
provider_slug: assistantgym-com
slug: assistantgym-com-eligibility
source_date: '2026-11-09'
source_filename: assistantgym-com-eligibility.yml
source_heading: Eligibility
source_page: https://assistantgym.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Assistant Gym\naid: assistantgym-com\nurl: https://assistantgym.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 or older and allowed to connect the assistant for yourself or your organization.\n- type: business\n  text: allowed to connect the assistant for yourself or your organization\nrestricted_uses:\n- summary: High-stakes decisions\n  text: Do not rely on them alone for decisions about money, safety, health or legal matters.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be 18 or older\n"
source_yaml_url: https://artifacts.apis.io/assistantgym-com/eligibility/assistantgym-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Assistant Gym's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Assistant
- Productivity
- Automation
- Platform
---
