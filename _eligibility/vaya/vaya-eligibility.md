---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using this Platform, you warrant that you are over the age of 18 years and are legally capable of entering into binding contracts.
    type: individual
  - text: You agree that you will use your account on the Platform to make purchases only for personal use and not for business purposes.
    type: business
  minimum_age:
    text: you warrant that you are over the age of 18 years
    value: '18'
  restricted_uses:
  - summary: Business purchases
    text: You agree not to use the platform for any unlawful or prohibited activity, including attempting to purchase Vaya services for business purposes.
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
name: Vaya
provenance_date: '2026-11-10'
provider_name: Vaya
provider_slug: vaya
slug: vaya-eligibility
source_date: '2026-11-10'
source_filename: vaya-eligibility.yml
source_heading: Eligibility
source_page: https://vaya.so/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vaya\naid: vaya\nurl: https://vaya.so/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using this Platform, you warrant that you are over the age of 18 years and are legally capable of entering\n    into binding contracts.\n- type: business\n  text: You agree that you will use your account on the Platform to make purchases only for personal use and not\n    for business purposes.\nrestricted_uses:\n- summary: Business purchases\n  text: You agree not to use the platform for any unlawful or prohibited activity, including attempting\
  \ to purchase\n    Vaya services for business purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you warrant that you are over the age of 18 years\n"
source_yaml_url: https://artifacts.apis.io/vaya/eligibility/vaya-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Vaya's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Astrology
- Vedic Astrology
- Consultations
- Consumer App
- India
---
