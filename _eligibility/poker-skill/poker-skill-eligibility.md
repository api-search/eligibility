---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: we make no representation that the Service is appropriate or available in all locations.
  entity_types:
  - text: You must be at least 18 years old to use Poker Skill.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use Poker Skill.
    value: '18'
  restricted_uses:
  - summary: No real-money gambling
    text: Attempting to use Poker Skill to facilitate real-money bets or wagers outside the app.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Some features may require creating an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Poker Skill
provenance_date: '2026-11-10'
provider_name: Poker Skill
provider_slug: poker-skill
slug: poker-skill-eligibility
source_date: '2026-11-10'
source_filename: poker-skill-eligibility.yml
source_heading: Eligibility
source_page: https://www.pokerskill.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Poker Skill\naid: poker-skill\nurl: https://www.pokerskill.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: we make no representation that the Service is appropriate or available in all locations.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use Poker Skill.\nrestricted_uses:\n- summary: No real-money gambling\n  text: Attempting to use Poker Skill to facilitate real-money bets or wagers outside the app.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Some features may require creating an account.\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years old to use Poker Skill.\n"
source_yaml_url: https://artifacts.apis.io/poker-skill/eligibility/poker-skill-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Poker Skill's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Poker
- Gaming
- Education
- Mobile App
- Training
- Artificial Intelligence
---
