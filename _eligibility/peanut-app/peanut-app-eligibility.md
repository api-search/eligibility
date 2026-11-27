---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: be at least 18 years old; and, be legally permitted to use the App in your country.
    type: individual
  minimum_age:
    text: be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Commercial use of other users' information
    text: You may not use other users' information for commercial purposes, to spam, to harass, or to make unlawful threats.
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
name: Peanut App
provenance_date: '2026-11-10'
provider_name: Peanut App
provider_slug: peanut-app
slug: peanut-app-eligibility
source_date: '2026-11-10'
source_filename: peanut-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.peanut-app.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Peanut App\naid: peanut-app\nurl: https://www.peanut-app.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: be at least 18 years old; and, be legally permitted to use the App in your country.\nrestricted_uses:\n- summary: Commercial use of other users' information\n  text: You may not use other users' information for commercial purposes, to spam, to harass, or to make unlawful\n    threats.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: be at least 18 years\
  \ old\n"
source_yaml_url: https://artifacts.apis.io/peanut-app/eligibility/peanut-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Peanut App's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Social Network
- Community
- Women
- Health
- Mobile App
---
