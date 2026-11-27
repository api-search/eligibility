---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Please do not use this website if you are under eighteen (18) years of age.
    type: individual
  minimum_age:
    text: Please do not use this website if you are under eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Dental products require dental practice license or supervision
    text: you are qualified to use them either by holding a dental practice license or under supervision of authorized party if you are dental student.
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
name: X mart
provenance_date: '2026-11-10'
provider_name: X mart
provider_slug: x-mart
slug: x-mart-eligibility
source_date: '2026-11-10'
source_filename: x-mart-eligibility.yml
source_heading: Eligibility
source_page: https://dentacarts.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: X mart\naid: x-mart\nurl: https://dentacarts.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Please do not use this website if you are under eighteen (18) years of age.\nrestricted_uses:\n- summary: Dental products require dental practice license or supervision\n  text: you are qualified to use them either by holding a dental practice license or under supervision of authorized\n    party if you are dental student.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: Please do not use this website if you are under eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/x-mart/eligibility/x-mart-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from X mart's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Dental
- Healthcare
- Marketplace
- E-Commerce
- Medical Supplies
---
