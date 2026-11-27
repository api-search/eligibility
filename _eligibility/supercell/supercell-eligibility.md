---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using or registering for an Account or otherwise using the Service, you affirm that you are the legal age of majority in your country of residence. If you are not, your legal guardian must review and agree to these Terms of Service.
    type: individual
  minimum_age:
    text: you affirm that you are the legal age of majority in your country of residence.
    value: age of majority
  restricted_uses:
  - summary: Non-commercial use only
    text: You agree not to use the Service for any other purpose.
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
name: Supercell
provenance_date: '2026-11-10'
provider_name: Supercell
provider_slug: supercell
slug: supercell-eligibility
source_date: '2026-11-10'
source_filename: supercell-eligibility.yml
source_heading: Eligibility
source_page: https://supercell.com/en/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Supercell\naid: supercell\nurl: https://supercell.com/en/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using or registering for an Account or otherwise using the Service, you affirm that you are the legal\n    age of majority in your country of residence. If you are not, your legal guardian must review and agree to these\n    Terms of Service.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You agree not to use the Service for any other purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you affirm that you are the legal age of majority in your country of residence.\n"
source_yaml_url: https://artifacts.apis.io/supercell/eligibility/supercell-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Supercell's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Gaming
- Mobile Games
- Video Games
- Game Data
- Developer API
- Leaderboards
- Esports
---
