---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: These terms are only applicable if you are resident of the United States.
  entity_types:
  - text: solely for your own personal use
    type: individual
  minimum_age:
    text: Use of the Service is limited to persons eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Sanctioned countries or parties
    text: you are not located in a country that is subject to a U.S. Government embargo
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
name: Battleface
provenance_date: '2026-11-09'
provider_name: Battleface
provider_slug: battleface
slug: battleface-eligibility
source_date: '2026-11-09'
source_filename: battleface-eligibility.yml
source_heading: Eligibility
source_page: https://www.battleface.com/en-us/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Battleface\naid: battleface\nurl: https://www.battleface.com/en-us/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: These terms are only applicable if you are resident of the United States.\nentity_types:\n- type: individual\n  text: solely for your own personal use\nrestricted_uses:\n- summary: Sanctioned countries or parties\n  text: you are not located in a country that is subject to a U.S. Government embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Use of the Service is limited\
  \ to persons eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/battleface/eligibility/battleface-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Battleface's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Insurance
- Adventure
- DigitalClaims
- Global
---
