---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are legally able to enter into a binding agreement
    type: individual
  - text: If you are accessing or using the Services on behalf of a company, law firm, corporation, partnership, government entity, or other organization (“Customer”)
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
name: Avoice
provenance_date: '2026-11-09'
provider_name: Avoice
provider_slug: avoice
slug: avoice-eligibility
source_date: '2026-11-09'
source_filename: avoice-eligibility.yml
source_heading: Eligibility
source_page: https://www.avoice.co/terms-of-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avoice\naid: avoice\nurl: https://www.avoice.co/terms-of-services\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are legally able to enter into a binding agreement\n- type: business\n  text: If you are accessing or using the Services on behalf of a company, law firm, corporation, partnership, government\n    entity, or other organization (“Customer”)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/avoice/eligibility/avoice-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Avoice's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Architecture
- Engineering
- AECO
- AI Agents
- Design Automation
- Specification
- Construction Administration
- Productivity
- Y Combinator
---
