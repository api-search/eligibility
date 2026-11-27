---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to register for and purchase a subscription to the FightCamp Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to register for and purchase a subscription to the FightCamp Service.
    value: '18'
  restricted_uses:
  - summary: Commercial purposes
    text: 'You agree not to, and will not assist, encourage, or enable others to use the FightCamp Service: For any commercial purpose, except as expressly permitted under these Terms'
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
name: Fightcamp
provenance_date: '2026-11-09'
provider_name: Fightcamp
provider_slug: fightcamp
slug: fightcamp-eligibility
source_date: '2026-11-09'
source_filename: fightcamp-eligibility.yml
source_heading: Eligibility
source_page: https://joinfightcamp.com/legal-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fightcamp\naid: fightcamp\nurl: https://joinfightcamp.com/legal-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to register for and purchase a subscription to the FightCamp Service.\nrestricted_uses:\n- summary: Commercial purposes\n  text: 'You agree not to, and will not assist, encourage, or enable others to use the FightCamp Service: For any\n    commercial purpose, except as expressly permitted under these Terms'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to register for and purchase a subscription to the FightCamp Service.\n"
source_yaml_url: https://artifacts.apis.io/fightcamp/eligibility/fightcamp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fightcamp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Fitness
- Connected Fitness
- Boxing
- Wearables
- Health
- Direct to Consumer
---
