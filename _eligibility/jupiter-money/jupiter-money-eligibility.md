---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: You are a resident of India; Only Indian Resident customers are eligible to open Deposit accounts under single mode of operation.
  minimum_age:
    text: You are of at least 21 years of age
    value: '21'
  restricted_uses:
  - summary: Loan proceeds limited to declared purpose
    text: use the proceeds of the Credit Facilities for any purpose other than as declared to Jupiter or its Lending Partners
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Partner Bank reserves the right to accept / reject your application. Partner Bank's decision in this regard would be final.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Jupiter Money
provenance_date: '2026-11-09'
provider_name: Jupiter Money
provider_slug: jupiter-money
slug: jupiter-money-eligibility
source_date: '2026-11-09'
source_filename: jupiter-money-eligibility.yml
source_heading: Eligibility
source_page: https://jupiter.money/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jupiter Money\naid: jupiter-money\nurl: https://jupiter.money/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: You are a resident of India; Only Indian Resident customers are eligible to open Deposit accounts under\n    single mode of operation.\nentity_types: []\nrestricted_uses:\n- summary: Loan proceeds limited to declared purpose\n  text: use the proceeds of the Credit Facilities for any purpose other than as declared to Jupiter or its Lending\n    Partners\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text:\
  \ Partner Bank reserves the right to accept / reject your application. Partner Bank's decision in this regard\n    would be final.\nminimum_age:\n  value: '21'\n  text: You are of at least 21 years of age\n"
source_yaml_url: https://artifacts.apis.io/jupiter-money/eligibility/jupiter-money-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Jupiter Money's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- Neobank
- Digital Banking
- Fintech
- Consumer Finance
- Personal Finance
- Savings
- Lending
- Credit Cards
- UPI
- Payments
- Mutual Funds
- Digital Gold
- Rewards
- India
---
