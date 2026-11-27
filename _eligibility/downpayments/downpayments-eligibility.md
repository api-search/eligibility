---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Downpayments Site is made available only for personal, non-commercial use and display by U.S. residents legally capable of entering commercial agreements.
  entity_types:
  - text: The Downpayments Site is available only to individuals who are permitted to use it under applicable law.
    type: individual
  minimum_age:
    text: You may only accept this Agreement and use the Downpayments Site if you are legally authorized to accept and be bound by these terms and of a legal age to enter this Agreement.
    value: null
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: The Downpayments Site is made available only for personal, non-commercial use and display by U.S. residents legally capable of entering commercial agreements.
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
name: Downpayments
provenance_date: '2026-11-09'
provider_name: Downpayments
provider_slug: downpayments
slug: downpayments-eligibility
source_date: '2026-11-09'
source_filename: downpayments-eligibility.yml
source_heading: Eligibility
source_page: https://downpayments.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Downpayments\naid: downpayments\nurl: https://downpayments.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Downpayments Site is made available only for personal, non-commercial use and display by U.S. residents\n    legally capable of entering commercial agreements.\nentity_types:\n- type: individual\n  text: The Downpayments Site is available only to individuals who are permitted to use it under applicable law.\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: The Downpayments Site is made available only for personal, non-commercial\
  \ use and display by U.S. residents\n    legally capable of entering commercial agreements.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may only accept this Agreement and use the Downpayments Site if you are legally authorized to accept\n    and be bound by these terms and of a legal age to enter this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/downpayments/eligibility/downpayments-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Downpayments's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Real Estate
- Home Equity
- Mortgage
- Investment
---
