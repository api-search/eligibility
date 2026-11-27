---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users between 13–17 must have permission from a parent or guardian
    type: individual
  minimum_age:
    text: The hyperPad Hub is available only to users 13 years or older
    value: '13'
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
name: Hyperpad
provenance_date: '2026-11-09'
provider_name: Hyperpad
provider_slug: hyperpad
slug: hyperpad-eligibility
source_date: '2026-11-09'
source_filename: hyperpad-eligibility.yml
source_heading: Eligibility
source_page: https://www.hyperpad.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hyperpad\naid: hyperpad\nurl: https://www.hyperpad.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users between 13–17 must have permission from a parent or guardian\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The hyperPad Hub is available only to users 13 years or older\n"
source_yaml_url: https://artifacts.apis.io/hyperpad/eligibility/hyperpad-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Hyperpad's own page on 2026-11-09.
synthetic: false
tags:
- Company
- No-Code
- Game Development
- iPad
- Visual Programming
- App Store
- Education
- Developer Tools
- Y Combinator
---
