---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: APS makes no representation that the information, goods and services on or available through this Site are appropriate or available for use in other locations, or to individuals or entities outside of APS' service territory.
  entity_types:
  - text: The Site is intended only for, and may only be accessed by, persons 18 years of age and older.
    type: individual
  minimum_age:
    text: The Site is intended only for, and may only be accessed by, persons 18 years of age and older.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You agree to use this Site only for lawful purposes.
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
name: Arizona Public Service
provenance_date: '2026-11-09'
provider_name: Arizona Public Service
provider_slug: aps-com
slug: aps-com-eligibility
source_date: '2026-11-09'
source_filename: aps-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.aps.com/en/Utility/Regulatory-and-Legal/Terms-of-Use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arizona Public Service\naid: aps-com\nurl: https://www.aps.com/en/Utility/Regulatory-and-Legal/Terms-of-Use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: APS makes no representation that the information, goods and services on or available through this Site are\n    appropriate or available for use in other locations, or to individuals or entities outside of APS' service territory.\nentity_types:\n- type: individual\n  text: The Site is intended only for, and may only be accessed by, persons 18 years of age and older.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You\
  \ agree to use this Site only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended only for, and may only be accessed by, persons 18 years of age and older.\n"
source_yaml_url: https://artifacts.apis.io/aps-com/eligibility/aps-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Arizona Public Service's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Utilities
- Electricity
---
