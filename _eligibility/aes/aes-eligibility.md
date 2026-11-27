---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: AES makes no representation that the Content or Site are appropriate or available for use in any particular locations, or to individuals or entities in any particular jurisdiction.
  entity_types:
  - text: You must be the age of majority (which is typically eighteen [18] years old) in your place of residence to use this Site.
    type: individual
  minimum_age:
    text: You must be the age of majority (which is typically eighteen [18] years old) in your place of residence to use this Site.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited online conduct
    text: You agree to use the Site and the Content (to the extent permissible under these Terms) only for lawful purposes.
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
name: AES
provenance_date: '2026-11-09'
provider_name: AES
provider_slug: aes
slug: aes-eligibility
source_date: '2026-11-09'
source_filename: aes-eligibility.yml
source_heading: Eligibility
source_page: https://www.aes.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AES\naid: aes\nurl: https://www.aes.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: AES makes no representation that the Content or Site are appropriate or available for use in any particular\n    locations, or to individuals or entities in any particular jurisdiction.\nentity_types:\n- type: individual\n  text: You must be the age of majority (which is typically eighteen [18] years old) in your place of residence\n    to use this Site.\nrestricted_uses:\n- summary: Unlawful or prohibited online conduct\n  text: You agree to use the Site and the Content (to the\
  \ extent permissible under these Terms) only for lawful\n    purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be the age of majority (which is typically eighteen [18] years old) in your place of residence\n    to use this Site.\n"
source_yaml_url: https://artifacts.apis.io/aes/eligibility/aes-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AES's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Power Generation
- Renewable Energy
- Battery Storage
- Utility
- Clean Energy
- Fortune 500
---
