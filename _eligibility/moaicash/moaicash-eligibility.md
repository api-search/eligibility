---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you must be a resident of the one of the countries in which the applicable Services are supported
  entity_types:
  - text: To be eligible to use Moai and certain add-on services offered by third parties and made available to you via Moai, you must be a resident of the one of the countries in which the applicable Services are supported and be at least 18 years of age or (if greater) the age of majority in your country of residence.
    type: individual
  minimum_age:
    text: be at least 18 years of age or (if greater) the age of majority in your country of residence
    value: '18'
  restricted_uses:
  - summary: Sanctions and unlawful activity
    text: Violating sanctions or embargo regulations
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
name: Moai.cash
provenance_date: '2026-11-10'
provider_name: Moai.cash
provider_slug: moaicash
slug: moaicash-eligibility
source_date: '2026-11-10'
source_filename: moaicash-eligibility.yml
source_heading: Eligibility
source_page: https://moai.cash/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moai.cash\naid: moaicash\nurl: https://moai.cash/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you must be a resident of the one of the countries in which the applicable Services are supported\nentity_types:\n- type: individual\n  text: To be eligible to use Moai and certain add-on services offered by third parties and made available to you\n    via Moai, you must be a resident of the one of the countries in which the applicable Services are supported\n    and be at least 18 years of age or (if greater) the age of majority in your country of residence.\nrestricted_uses:\n\
  - summary: Sanctions and unlawful activity\n  text: Violating sanctions or embargo regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: be at least 18 years of age or (if greater) the age of majority in your country of residence\n"
source_yaml_url: https://artifacts.apis.io/moaicash/eligibility/moaicash-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Moai.cash's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Payments
- Digital Wallet
- Web3
- Blockchain
- Fintech
- Prediction Markets
- Telegram
---
