---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'You represent and warrant that: (i) you are not located in a country that is subject to a U.S. Government embargo'
  entity_types:
  - text: for your personal, non-commercial purposes
    type: individual
  minimum_age:
    text: In any case, to use our Service you must be 16 years of age or older.
    value: '16'
  restricted_uses:
  - summary: Advertising or solicitation content
    text: Do not submit or share content for advertising or solicitation purposes (including promotional or commercial content).
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
name: Waze
provenance_date: '2026-11-10'
provider_name: Waze
provider_slug: waze
slug: waze-eligibility
source_date: '2026-11-10'
source_filename: waze-eligibility.yml
source_heading: Eligibility
source_page: https://support.google.com/waze/answer/12373727
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Waze\naid: waze\nurl: https://support.google.com/waze/answer/12373727\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'You represent and warrant that: (i) you are not located in a country that is subject to a U.S. Government\n    embargo'\nentity_types:\n- type: individual\n  text: for your personal, non-commercial purposes\nrestricted_uses:\n- summary: Advertising or solicitation content\n  text: Do not submit or share content for advertising or solicitation purposes (including promotional or commercial\n    content).\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: In any case, to use our Service you must be 16 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/waze/eligibility/waze-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Waze's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mobility
- Navigation
- Maps
- Traffic
- Location
- Transportation
- Smart Cities
---
