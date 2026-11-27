---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: be 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Multiple accounts for same business
    text: multiple accounts operating under the same business name or franchise are not allowed.
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
name: AirPOS
provenance_date: '2026-11-09'
provider_name: AirPOS
provider_slug: airpos
slug: airpos-eligibility
source_date: '2026-11-09'
source_filename: airpos-eligibility.yml
source_heading: Eligibility
source_page: https://www.airpointofsale.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AirPOS\naid: airpos\nurl: https://www.airpointofsale.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Multiple accounts for same business\n  text: multiple accounts operating under the same business name or franchise are not allowed.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: be 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/airpos/eligibility/airpos-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from AirPOS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Point-of-Sale
- Retail
- Payments
- Inventory
- E-Commerce
- United Kingdom
- Northern Ireland
---
