---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer, please note that these terms of use, their subject matter and their formation, are governed by English law.
    type: individual
  - text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms that may apply to our site or any content on it.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: 'Consumer: no commercial use'
    text: we only provide our site for domestic and private use. You agree not to use our site for any commercial or business purposes
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
name: Recycleye
provenance_date: '2026-11-10'
provider_name: Recycleye
provider_slug: recycleye
slug: recycleye-eligibility
source_date: '2026-11-10'
source_filename: recycleye-eligibility.yml
source_heading: Eligibility
source_page: https://recycleye.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Recycleye\naid: recycleye\nurl: https://recycleye.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer, please note that these terms of use, their subject matter and their formation, are\n    governed by English law.\n- type: business\n  text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms\n    that may apply to our site or any content on it.'\nrestricted_uses:\n- summary: 'Consumer: no commercial use'\n  text: we only provide our site for\
  \ domestic and private use. You agree not to use our site for any commercial\n    or business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/recycleye/eligibility/recycleye-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Recycleye's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Recycling
- Waste Management
- Artificial Intelligence
- Computer Vision
- Robotics
- Sustainability
- Circular Economy
---
