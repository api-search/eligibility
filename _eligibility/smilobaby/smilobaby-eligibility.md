---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Eligibility is limited to real individuals only.
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You may not use our products for any illegal or unauthorized purpose
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
name: Smilobaby
provenance_date: '2026-11-10'
provider_name: Smilobaby
provider_slug: smilobaby
slug: smilobaby-eligibility
source_date: '2026-11-10'
source_filename: smilobaby-eligibility.yml
source_heading: Eligibility
source_page: https://www.smilobaby.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Smilobaby\naid: smilobaby\nurl: https://www.smilobaby.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Eligibility is limited to real individuals only.\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You may not use our products for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/smilobaby/eligibility/smilobaby-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Smilobaby's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Baby Products
- Consumer
- E-Commerce
- Retail
- Parenting
- Direct to Consumer
---
