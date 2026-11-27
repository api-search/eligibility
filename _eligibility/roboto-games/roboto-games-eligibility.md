---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old (or the minimum age in your country) to use the Services. If you are under 18, a parent or guardian must review these terms and accept them on your behalf.
    type: individual
  minimum_age:
    text: You must be at least 13 years old (or the minimum age in your country) to use the Services.
    value: '13'
  restricted_uses:
  - summary: Unapproved commercial purposes
    text: (e) use the Services for any commercial purpose we have not approved
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
name: Roboto Games
provenance_date: '2026-11-10'
provider_name: Roboto Games
provider_slug: roboto-games
slug: roboto-games-eligibility
source_date: '2026-11-10'
source_filename: roboto-games-eligibility.yml
source_heading: Eligibility
source_page: https://www.robotogames.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Roboto Games\naid: roboto-games\nurl: https://www.robotogames.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old (or the minimum age in your country) to use the Services. If you are under\n    18, a parent or guardian must review these terms and accept them on your behalf.\nrestricted_uses:\n- summary: Unapproved commercial purposes\n  text: (e) use the Services for any commercial purpose we have not approved\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '13'\n  text: You must be at least 13 years old (or the minimum age in your country) to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/roboto-games/eligibility/roboto-games-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Roboto Games's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video Games
- Game Development
- Game Studio
- Survival Crafting
- Entertainment
- Consumer
---
