---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Company System may be restricted or prohibited in certain geographies.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Gambling and unlawful content
    text: relating or encouraging gambling, money laundering or engaging in activities which would cause offence to others on grounds of race
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
name: Perfios
provenance_date: '2026-11-10'
provider_name: Perfios
provider_slug: perfios
slug: perfios-eligibility
source_date: '2026-11-10'
source_filename: perfios-eligibility.yml
source_heading: Eligibility
source_page: https://perfios.ai/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Perfios\naid: perfios\nurl: https://perfios.ai/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Company System may be restricted or prohibited in certain geographies.\nentity_types: []\nrestricted_uses:\n- summary: Gambling and unlawful content\n  text: relating or encouraging gambling, money laundering or engaging in activities which would cause offence to\n    others on grounds of race\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/perfios/eligibility/perfios-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Perfios's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Financial Services
- KYC
- Onboarding
- Credit Decisioning
- Bank Statement Analysis
- Fraud Prevention
- Account Aggregator
- India
---
