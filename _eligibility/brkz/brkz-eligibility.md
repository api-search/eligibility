---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - SA
    text: The Program is exclusively available to activated users of BRKZ within the Kingdom of Saudi Arabia.
  entity_types:
  - text: You are 18 years of age or older
    type: individual
  - text: you and your organisation or corporation (the “End-User”)
    type: business
  minimum_age:
    text: You are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Unlawful use or infringing data
    text: Violates any applicable laws, or infringes, violates or otherwise misappropriates the intellectual property or other rights of any third party
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: submitted all required documents as per BRKZ’s activation policy
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BRKZ
provenance_date: '2026-11-09'
provider_name: BRKZ
provider_slug: brkz
slug: brkz-eligibility
source_date: '2026-11-09'
source_filename: brkz-eligibility.yml
source_heading: Eligibility
source_page: https://brkz.com/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BRKZ\naid: brkz\nurl: https://brkz.com/en/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SA\n  excluded: []\n  text: The Program is exclusively available to activated users of BRKZ within the Kingdom of Saudi Arabia.\nentity_types:\n- type: individual\n  text: You are 18 years of age or older\n- type: business\n  text: you and your organisation or corporation (the “End-User”)\nrestricted_uses:\n- summary: Unlawful use or infringing data\n  text: Violates any applicable laws, or infringes, violates or otherwise misappropriates the intellectual property\n    or other rights of any third\
  \ party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: submitted all required documents as per BRKZ’s activation policy\nminimum_age:\n  value: '18'\n  text: You are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/brkz/eligibility/brkz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from BRKZ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Building Materials
- Construction Technology
- E-Commerce
- Marketplace
- Procurement
- Logistics
- B2B
- Saudi Arabia
---
