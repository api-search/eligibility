---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Domestic supply T&Cs
    type: individual
  - text: Business supply T&Cs
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Some tariffs have specific eligibility criteria that must be met and others have peak and off-peak times that apply.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Good Energy
provenance_date: '2026-11-09'
provider_name: Good Energy
provider_slug: good-energy
slug: good-energy-eligibility
source_date: '2026-11-09'
source_filename: good-energy-eligibility.yml
source_heading: Eligibility
source_page: https://www.goodenergy.co.uk/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Good Energy\naid: good-energy\nurl: https://www.goodenergy.co.uk/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Domestic supply T&Cs\n- type: business\n  text: Business supply T&Cs\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Some tariffs have specific eligibility criteria that must be met and others have peak and off-peak times\n    that apply.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/good-energy/eligibility/good-energy-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from Good Energy's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- United Kingdom
- Utilities
- Electricity
- Gas
- Renewables
- Smart Metering
- Solar
- EV Charging
- Energy Retail
---
