---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if the law bars you, including U.S. sanctions or export rules.
  entity_types:
  - text: You must be at least 18 years old, and old enough to make a binding contract where you live.
    type: individual
  - text: If you use the Service for a company, you confirm you can bind that company, and "you" means the company.
    type: business
  minimum_age:
    text: You must be at least 18 years old, and old enough to make a binding contract where you live.
    value: '18'
  restricted_uses:
  - summary: Marketing gambling to minors or where illegal
    text: use the Service to market gambling to anyone under the legal age, or anywhere it is not allowed
  - summary: Harassing athletes
    text: You may not use the Service to harass, threaten or target any athlete, official or other person.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We verify your email before we issue a key.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: strikerapi-com
provenance_date: '2026-11-10'
provider_name: strikerapi-com
provider_slug: strikerapi-com
slug: strikerapi-com-eligibility
source_date: '2026-11-10'
source_filename: strikerapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://strikerapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: strikerapi-com\naid: strikerapi-com\nurl: https://strikerapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if the law bars you, including U.S. sanctions or export rules.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, and old enough to make a binding contract where you live.\n- type: business\n  text: If you use the Service for a company, you confirm you can bind that company, and \"you\" means the company.\nrestricted_uses:\n- summary: Marketing gambling to minors or where illegal\n  text: use the Service to\
  \ market gambling to anyone under the legal age, or anywhere it is not allowed\n- summary: Harassing athletes\n  text: You may not use the Service to harass, threaten or target any athlete, official or other person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We verify your email before we issue a key.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, and old enough to make a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/strikerapi-com/eligibility/strikerapi-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from strikerapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Soccer
- Sports Data
- Odds
- Statistics
---
