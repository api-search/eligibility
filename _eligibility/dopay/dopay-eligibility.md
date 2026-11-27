---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We provide Dopay Business Accounts and related services to companies
    type: business
  - text: Dopay personal accounts, prepaid cards, and related services to Beneficiaries
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: AML compliance warranty
    text: The Client represents and warrants that it has and will continue to conduct its operations in full compliance with all applicable anti-money laundering and counter-terrorist financing laws.
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
name: dopay
provenance_date: '2026-11-09'
provider_name: dopay
provider_slug: dopay
slug: dopay-eligibility
source_date: '2026-11-09'
source_filename: dopay-eligibility.yml
source_heading: Eligibility
source_page: https://dopay.com/en/business-terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: dopay\naid: dopay\nurl: https://dopay.com/en/business-terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: We provide Dopay Business Accounts and related services to companies\n- type: individual\n  text: Dopay personal accounts, prepaid cards, and related services to Beneficiaries\nrestricted_uses:\n- summary: AML compliance warranty\n  text: The Client represents and warrants that it has and will continue to conduct its operations in full compliance\n    with all applicable anti-money laundering and counter-terrorist financing\
  \ laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dopay/eligibility/dopay-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from dopay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payroll
- Payments
- Fintech
- Earned Wage Access
- Salary Disbursement
- Egypt
- Financial Services
---
