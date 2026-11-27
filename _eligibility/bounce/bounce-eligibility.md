---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least eighteen (18) years old to register.
    type: individual
  - text: you represent a legal person and you have all the necessary power to represent and bind this legal person
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old to register.
    value: '18'
  restricted_uses:
  - summary: Prohibited items
    text: You may not use the Bounce Platform to store, deliver, receive, transport, or otherwise interact with the following items
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
name: Bounce
provenance_date: '2026-11-09'
provider_name: Bounce
provider_slug: bounce
slug: bounce-eligibility
source_date: '2026-11-09'
source_filename: bounce-eligibility.yml
source_heading: Eligibility
source_page: https://bounce.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bounce\naid: bounce\nurl: https://bounce.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old to register.\n- type: business\n  text: you represent a legal person and you have all the necessary power to represent and bind this legal person\nrestricted_uses:\n- summary: Prohibited items\n  text: You may not use the Bounce Platform to store, deliver, receive, transport, or otherwise interact with the\n    following items\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to register.\n"
source_yaml_url: https://artifacts.apis.io/bounce/eligibility/bounce-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bounce's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Luggage Storage
- Travel
- Marketplace
- Logistics
- Consumer
- Storage Network
- Hospitality
---
