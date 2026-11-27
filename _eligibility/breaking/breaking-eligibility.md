---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 years old to use the Services.
    type: individual
  - text: you are accepting these terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: You must be 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: solely for your own personal, noncommercial use.
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
name: Breaking
provenance_date: '2026-11-09'
provider_name: Breaking
provider_slug: breaking
slug: breaking-eligibility
source_date: '2026-11-09'
source_filename: breaking-eligibility.yml
source_heading: Eligibility
source_page: https://www.breaking.com/termsOfUse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Breaking\naid: breaking\nurl: https://www.breaking.com/termsOfUse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 years old to use the Services.\n- type: business\n  text: you are accepting these terms (on behalf of yourself or the entity that you represent)\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: solely for your own personal, noncommercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years old\
  \ to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/breaking/eligibility/breaking-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Breaking's own page on 2026-11-09.
synthetic: false
tags:
- Plastic Waste
- Chemical Recycling
---
