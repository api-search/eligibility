---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Services are provided in the state or territory in which they are being provided; no country list is stated.
  entity_types:
  - text: You will be able to set up an Account within the App which can be used by an individual for personal or business use.
    type: individual
  minimum_age:
    text: you must be at least of an age where a driver’s licence may be issued to you in the state or territory in which the Services are being provided
    value: driver licence age
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
name: Evie Networks
provenance_date: '2026-11-09'
provider_name: Evie Networks
provider_slug: evie-networks
slug: evie-networks-eligibility
source_date: '2026-11-09'
source_filename: evie-networks-eligibility.yml
source_heading: Eligibility
source_page: https://evie.com.au/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evie Networks\naid: evie-networks\nurl: https://evie.com.au/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Services are provided in the state or territory in which they are being provided; no country list is stated.\nentity_types:\n- type: individual\n  text: You will be able to set up an Account within the App which can be used by an individual for personal or\n    business use.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: driver licence age\n  text: you must be at least of an age\
  \ where a driver’s licence may be issued to you in the state or territory in\n    which the Services are being provided\n"
source_yaml_url: https://artifacts.apis.io/evie-networks/eligibility/evie-networks-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Evie Networks's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Australia
- EV Charging
- Electricity
- Utilities
- E-Mobility
- Charging Infrastructure
- Fleet Management
- Transport Electrification
---
