---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are an individual (i.e., not a corporation) you are at least 18 years of age.
    type: individual
  minimum_age:
    text: if you are an individual (i.e., not a corporation) you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: for personal non-commercial use only
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
name: Timehop
provenance_date: '2026-11-10'
provider_name: Timehop
provider_slug: timehop
slug: timehop-eligibility
source_date: '2026-11-10'
source_filename: timehop-eligibility.yml
source_heading: Eligibility
source_page: https://www.timehop.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Timehop\naid: timehop\nurl: https://www.timehop.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are an individual (i.e., not a corporation) you are at least 18 years of age.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: for personal non-commercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you are an individual (i.e., not a corporation) you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/timehop/eligibility/timehop-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Timehop's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Mobile
- Memories
- Photos
- Nostalgia
- Social
- iOS
- Android
---
