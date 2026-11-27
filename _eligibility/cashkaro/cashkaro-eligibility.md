---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are a natural person, (i) as a condition to Your use of the Platform, You must be 18 (eighteen) years of age or older
    type: individual
  minimum_age:
    text: You must be 18 (eighteen) years of age or older
    value: '18'
  restricted_uses:
  - summary: No resale or commercial purchases
    text: You shall not use CashKaro Platform to purchase anything to resell for commercial or business purposes, to derive any financial gain.
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
name: Cashkaro
provenance_date: '2026-11-09'
provider_name: Cashkaro
provider_slug: cashkaro
slug: cashkaro-eligibility
source_date: '2026-11-09'
source_filename: cashkaro-eligibility.yml
source_heading: Eligibility
source_page: https://cashkaro.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cashkaro\naid: cashkaro\nurl: https://cashkaro.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If You are a natural person, (i) as a condition to Your use of the Platform, You must be 18 (eighteen) years\n    of age or older\nrestricted_uses:\n- summary: No resale or commercial purchases\n  text: You shall not use CashKaro Platform to purchase anything to resell for commercial or business purposes,\n    to derive any financial gain.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be 18 (eighteen) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/cashkaro/eligibility/cashkaro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cashkaro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cashback
- Coupons
- E-Commerce
- India
---
