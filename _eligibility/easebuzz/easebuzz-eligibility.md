---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You affirm that you are at least Eighteen years of age and are fully able and competent to understand the terms
    type: individual
  - text: Any individual or business
    type: business
  minimum_age:
    text: You affirm that you are at least Eighteen years of age
    value: '18'
  restricted_uses:
  - summary: Politically exposed persons
    text: Easebuzz services cannot be used by or on behalf of Politically Exposed Persons or Entities (PEPs)
  - summary: Time share businesses
    text: Time share businesses, including vacation clubs and fractional ownership schemes, are prohibited from using Easebuzz services.
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
name: Easebuzz
provenance_date: '2026-11-09'
provider_name: Easebuzz
provider_slug: easebuzz
slug: easebuzz-eligibility
source_date: '2026-11-09'
source_filename: easebuzz-eligibility.yml
source_heading: Eligibility
source_page: https://easebuzz.in/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Easebuzz\naid: easebuzz\nurl: https://easebuzz.in/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You affirm that you are at least Eighteen years of age and are fully able and competent to understand the\n    terms\n- type: business\n  text: Any individual or business\nrestricted_uses:\n- summary: Politically exposed persons\n  text: Easebuzz services cannot be used by or on behalf of Politically Exposed Persons or Entities (PEPs)\n- summary: Time share businesses\n  text: Time share businesses, including\
  \ vacation clubs and fractional ownership schemes, are prohibited from using\n    Easebuzz services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that you are at least Eighteen years of age\n"
source_yaml_url: https://artifacts.apis.io/easebuzz/eligibility/easebuzz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Easebuzz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Payment Gateway
- Payouts
- Banking
- India
- UPI
- Subscription
- SDK
---
