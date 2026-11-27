---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: THE SYSTEM WAS DEVELOPED FOR USE IN THE UNITED STATES, AND NEITHER WE NOR ANY OF OUR LICENSORS ... MAKE ANY REPRESENTATION CONCERNING THE SYSTEM WHEN USED IN ANY OTHER COUNTRY.
  minimum_age:
    text: The System can be used only by persons over 18 years of age.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must register with EnergyHub to use the broader functionality of the System
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: EnergyHub
provenance_date: '2026-11-09'
provider_name: EnergyHub
provider_slug: energyhub
slug: energyhub-eligibility
source_date: '2026-11-09'
source_filename: energyhub-eligibility.yml
source_heading: Eligibility
source_page: https://www.energyhub.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EnergyHub\naid: energyhub\nurl: https://www.energyhub.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: THE SYSTEM WAS DEVELOPED FOR USE IN THE UNITED STATES, AND NEITHER WE NOR ANY OF OUR LICENSORS ... MAKE\n    ANY REPRESENTATION CONCERNING THE SYSTEM WHEN USED IN ANY OTHER COUNTRY.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must register with EnergyHub to use the broader functionality of the System\nminimum_age:\n  value: '18'\n  text: The System can be used only by persons over 18 years\
  \ of age.\n"
source_yaml_url: https://artifacts.apis.io/energyhub/eligibility/energyhub-eligibility.yml
stated_fields:
- countries
- verification
- minimum_age
summary_line: 3 quoted statements, read from EnergyHub's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- United States
- Utilities
- Electricity
- Grid
- DERMS
- Distributed Energy Resources
- Demand Response
- Virtual Power Plant
- OpenADR
- EV Charging
- Solar
- Energy Storage
- Smart Thermostats
---
