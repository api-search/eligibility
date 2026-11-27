---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: intended for the lawful use of Motorola's customers, employees and members of the general public who are over the age of 18 and residents of the United States.
  entity_types:
  - text: members of the general public who are over the age of 18 and residents of the United States
    type: individual
  minimum_age:
    text: over the age of 18
    value: '18'
  restricted_uses:
  - summary: Content use causing consumer confusion
    text: You agree not to download, display or use any Content located on the Site in any manner that is likely to cause confusion among consumers
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
name: Motorola
provenance_date: '2026-11-10'
provider_name: Motorola
provider_slug: motorola
slug: motorola-eligibility
source_date: '2026-11-10'
source_filename: motorola-eligibility.yml
source_heading: Eligibility
source_page: https://www.motorola.com/us/en/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Motorola\naid: motorola\nurl: https://www.motorola.com/us/en/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: intended for the lawful use of Motorola's customers, employees and members of the general public who are\n    over the age of 18 and residents of the United States.\nentity_types:\n- type: individual\n  text: members of the general public who are over the age of 18 and residents of the United States\nrestricted_uses:\n- summary: Content use causing consumer confusion\n  text: You agree not to download, display or use any Content located on the Site\
  \ in any manner that is likely to\n    cause confusion among consumers\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/motorola/eligibility/motorola-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Motorola's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer Electronics
- Smartphones
- Mobile Devices
- Android
- Hardware
- Lenovo
---
