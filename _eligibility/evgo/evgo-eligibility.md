---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You maintain automobile liability insurance in accordance with the laws of the state in which you reside
  entity_types:
  - text: 'You may use the Services only if: You are at least 18 years old (or the legal age of majority where you live)'
    type: individual
  minimum_age:
    text: You are at least 18 years old (or the legal age of majority where you live)
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: Unless EVgo agrees otherwise in writing, the Services are for personal use only.
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
name: EVgo
provenance_date: '2026-11-09'
provider_name: EVgo
provider_slug: evgo
slug: evgo-eligibility
source_date: '2026-11-09'
source_filename: evgo-eligibility.yml
source_heading: Eligibility
source_page: https://www.evgo.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EVgo\naid: evgo\nurl: https://www.evgo.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You maintain automobile liability insurance in accordance with the laws of the state in which you reside\nentity_types:\n- type: individual\n  text: 'You may use the Services only if: You are at least 18 years old (or the legal age of majority where you\n    live)'\nrestricted_uses:\n- summary: Personal use only\n  text: Unless EVgo agrees otherwise in writing, the Services are for personal use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old (or the legal age of majority where you live)\n"
source_yaml_url: https://artifacts.apis.io/evgo/eligibility/evgo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from EVgo's own page on 2026-11-09.
synthetic: false
tags:
- Electric Vehicles
- EV Charging
- Charging Stations
- Energy
- Transportation
- Mobility
---
