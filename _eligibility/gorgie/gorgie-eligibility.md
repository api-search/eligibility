---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: products purchased by you and shipped to your designated location in the U.S. may be subject to applicable state or local sales or use tax
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: In any way that violates any applicable federal, state, local or international law or regulation;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may require you to provide information that may be used to confirm your identity and help ensure the security of your account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GORGIE
provenance_date: '2026-11-09'
provider_name: GORGIE
provider_slug: gorgie
slug: gorgie-eligibility
source_date: '2026-11-09'
source_filename: gorgie-eligibility.yml
source_heading: Eligibility
source_page: https://getgorgie.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GORGIE\naid: gorgie\nurl: https://getgorgie.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: products purchased by you and shipped to your designated location in the U.S. may be subject to applicable\n    state or local sales or use tax\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: In any way that violates any applicable federal, state, local or international law or regulation;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we may require you to provide information that may be used to confirm\
  \ your identity and help ensure the\n    security of your account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gorgie/eligibility/gorgie-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from GORGIE's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Consumer Packaged Goods
- Energy Drink
- Beverages
- Wellness
- E-Commerce
- Direct to Consumer
---
