---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: You represent and warrant that (i) you are not located in, under the control of, or a national or resident of any country or territory subject to comprehensive U.S. trade sanctions (including, without limitation, Cuba, Iran, North Korea, Syria, and the Crimea, so-called Donetsk People's Republic, and Luhansk People's Republic regions of Ukraine)
  entity_types:
  - text: The Website is intended for users who are at least 18 years of age.
    type: individual
  minimum_age:
    text: The Website is intended for users who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Export/sanctions restrictions
    text: you will not access or use the Website in violation of any U.S. or other applicable export-control or sanctions law or regulation.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cormint
provenance_date: '2026-11-09'
provider_name: Cormint
provider_slug: cormint
slug: cormint-eligibility
source_date: '2026-11-09'
source_filename: cormint-eligibility.yml
source_heading: Eligibility
source_page: https://www.cormint.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cormint\naid: cormint\nurl: https://www.cormint.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: You represent and warrant that (i) you are not located in, under the control of, or a national or resident\n    of any country or territory subject to comprehensive U.S. trade sanctions (including, without limitation, Cuba,\n    Iran, North Korea, Syria, and the Crimea, so-called Donetsk People's Republic, and Luhansk People's Republic\n    regions of Ukraine)\nentity_types:\n- type: individual\n  text: The Website is intended for users who are at\
  \ least 18 years of age.\nrestricted_uses:\n- summary: Export/sanctions restrictions\n  text: you will not access or use the Website in violation of any U.S. or other applicable export-control or sanctions\n    law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is intended for users who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/cormint/eligibility/cormint-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cormint's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Center
- Power Infrastructure
- Energy
- Bitcoin Mining
- AI Infrastructure
- High Performance Computing
- Colocation
- Texas
---
