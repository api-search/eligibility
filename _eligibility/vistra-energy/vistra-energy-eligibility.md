---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Sites are controlled and offered by us from our facilities in the United States. We make no representation that the Sites are appropriate or available for use outside of the United States
  entity_types:
  - text: you represent and warrant that you are at least eighteen (18) years of age
    type: individual
  - text: If you are using the Sites on behalf of an individual, company, or other legal entity, you represent and warrant that you have the authority to bind that entity to these terms
    type: business
  minimum_age:
    text: you represent and warrant that you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Non-commercial, personal or internal use only
    text: solely for your non-commercial, personal, or internal lawful business use.
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
name: Vistra
provenance_date: '2026-11-10'
provider_name: Vistra
provider_slug: vistra-energy
slug: vistra-energy-eligibility
source_date: '2026-11-10'
source_filename: vistra-energy-eligibility.yml
source_heading: Eligibility
source_page: https://vistracorp.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vistra\naid: vistra-energy\nurl: https://vistracorp.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Sites are controlled and offered by us from our facilities in the United States. We make no representation\n    that the Sites are appropriate or available for use outside of the United States\nentity_types:\n- type: individual\n  text: you represent and warrant that you are at least eighteen (18) years of age\n- type: business\n  text: If you are using the Sites on behalf of an individual, company, or other legal entity, you represent and\n    warrant that\
  \ you have the authority to bind that entity to these terms\nrestricted_uses:\n- summary: Non-commercial, personal or internal use only\n  text: solely for your non-commercial, personal, or internal lawful business use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/vistra-energy/eligibility/vistra-energy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Vistra's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United States
- Utilities
- Electricity
- Natural Gas
- Power Generation
- Retail Energy
- Smart Metering
- Green Button
- Energy Markets
- Nuclear
- Solar
- Battery Storage
- Texas
- ERCOT
---
