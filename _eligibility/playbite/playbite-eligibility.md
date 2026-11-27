---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must be at least 18 years of age and reside in an approved country where Playbite is available to use the Services.
  entity_types:
  - text: Only one (1) User Account is permitted per person.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Personal purposes
    text: The Services are intended to be used for personal purposes.
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
name: Playbite
provenance_date: '2026-11-10'
provider_name: Playbite
provider_slug: playbite
slug: playbite-eligibility
source_date: '2026-11-10'
source_filename: playbite-eligibility.yml
source_heading: Eligibility
source_page: https://www.playbitegames.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Playbite\naid: playbite\nurl: https://www.playbitegames.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must be at least 18 years of age and reside in an approved country where Playbite is available to use\n    the Services.\nentity_types:\n- type: individual\n  text: Only one (1) User Account is permitted per person.\nrestricted_uses:\n- summary: Personal purposes\n  text: The Services are intended to be used for personal purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You\
  \ must be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/playbite/eligibility/playbite-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Playbite's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Mobile Games
- Casual Games
- Mobile App
- Rewards
- Entertainment
- Consumer
---
