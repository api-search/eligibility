---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - SY
    - IR
    - KP
    - BY
    - RU
    served: []
    text: If you are located in Cuba, Syria, Iran, North Korea, Belarus, or Russia, you may not use the Services.
  entity_types:
  - text: You must be 16 years of age to use the Services.
    type: individual
  minimum_age:
    text: You must be 16 years of age to use the Services.
    value: '16'
  restricted_uses:
  - summary: Multiple accounts and false identity
    text: You agree not to create an Account using a false identity or information, or on behalf of someone other than yourself.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- SY
- IR
- KP
- BY
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Influence Mobile
provenance_date: '2026-11-09'
provider_name: Influence Mobile
provider_slug: influence-mobile
slug: influence-mobile-eligibility
source_date: '2026-11-09'
source_filename: influence-mobile-eligibility.yml
source_heading: Eligibility
source_page: https://www.influencemobile.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Influence Mobile\naid: influence-mobile\nurl: https://www.influencemobile.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - SY\n  - IR\n  - KP\n  - BY\n  - RU\n  text: If you are located in Cuba, Syria, Iran, North Korea, Belarus, or Russia, you may not use the Services.\nentity_types:\n- type: individual\n  text: You must be 16 years of age to use the Services.\nrestricted_uses:\n- summary: Multiple accounts and false identity\n  text: You agree not to create an Account using a false identity or information, or on behalf of someone other\n    than yourself.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be 16 years of age to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/influence-mobile/eligibility/influence-mobile-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Influence Mobile's own page on 2026-11-09.
synthetic: false
tags:
- Mobile Gaming
- Advertising
- Data Platform
- Player Acquisition
- Rewarded Play
- User Acquisition
- Loyalty Rewards
---
