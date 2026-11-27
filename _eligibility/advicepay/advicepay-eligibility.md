---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Customer Responsibility section: to the extent used in connection with the deposit or withdrawal of any funds, all Products and Services must be used solely in connection with United States based bank accounts.'
  minimum_age:
    text: You shall not use the AdvicePay Portal if you are under the age of 18
    value: '18'
  restricted_uses:
  - summary: Fraud and impersonation
    text: You shall not and shall not permit a third party to use the AdvicePay Portal for fraudulent purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As a condition of AdvicePay enabling payment processing services through Stripe, you agree to provide AdvicePay accurate and complete information about you and your business
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AdvicePay
provenance_date: '2026-11-09'
provider_name: AdvicePay
provider_slug: advicepay
slug: advicepay-eligibility
source_date: '2026-11-09'
source_filename: advicepay-eligibility.yml
source_heading: Eligibility
source_page: https://advicepay.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdvicePay\naid: advicepay\nurl: https://advicepay.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Customer Responsibility section: to the extent used in connection with the deposit or withdrawal of any\n    funds, all Products and Services must be used solely in connection with United States based bank accounts.'\nentity_types: []\nrestricted_uses:\n- summary: Fraud and impersonation\n  text: You shall not and shall not permit a third party to use the AdvicePay Portal for fraudulent purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: As a condition of AdvicePay enabling payment processing services through Stripe, you agree to provide AdvicePay\n    accurate and complete information about you and your business\nminimum_age:\n  value: '18'\n  text: You shall not use the AdvicePay Portal if you are under the age of 18\n"
source_yaml_url: https://artifacts.apis.io/advicepay/eligibility/advicepay-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from AdvicePay's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Payments
- Billing
- Invoicing
- Financial Planning
- Wealth Management
- Subscription
- E-Signature
- Compliance
- Fintech
---
