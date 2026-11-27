---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Services for use only by persons located in the United States.
  minimum_age:
    text: you certify that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Use by minors
    text: Our Website is not intended for children under 16 years of age. No one under age 16 may provide any information to or on the Website.
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
name: Billee
provenance_date: '2026-11-09'
provider_name: Billee
provider_slug: billee
slug: billee-eligibility
source_date: '2026-11-09'
source_filename: billee-eligibility.yml
source_heading: Eligibility
source_page: https://app.billee.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Billee\naid: billee\nurl: https://app.billee.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Services for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Use by minors\n  text: Our Website is not intended for children under 16 years of age. No one under age 16 may provide any information\n    to or on the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you certify that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/billee/eligibility/billee-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Billee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Utility
- Billing
- Artificial Intelligence
- Multifamily
---
