---
api_specs:
- filename: opay-cashier-api-openapi.yml
  format: yaml
  label: OPay Cashier API
  slug: opay-cashier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opay/openapi/opay-cashier-api-openapi.yml
- filename: opay-payments-api-openapi.yml
  format: yaml
  label: OPay Payments API
  slug: opay-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opay/openapi/opay-payments-api-openapi.yml
- filename: opay-refunds-api-openapi.yml
  format: yaml
  label: OPay Refunds API
  slug: opay-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opay/openapi/opay-refunds-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - NG
    text: The OPay Debit Card is accepted at all ATM, POS, or online payment platforms in Nigeria.
  minimum_age:
    text: null
    value: null
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
name: OPay
provenance_date: '2026-11-10'
provider_name: OPay
provider_slug: opay
slug: opay-eligibility
source_date: '2026-11-10'
source_filename: opay-eligibility.yml
source_heading: Eligibility
source_page: https://www.opayweb.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OPay\naid: opay\nurl: https://www.opayweb.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - NG\n  excluded: []\n  text: The OPay Debit Card is accepted at all ATM, POS, or online payment platforms in Nigeria.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/opay/eligibility/opay-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from OPay's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Mobile Money
- Fintech
- Super App
- Nigeria
- Africa
- Wallets
- Savings
- Buy Now Pay Later
- Bank Transfers
- Card Payments
- USSD
- Agent Banking
- Point-of-Sale
- Bill Payments
- Airtime
- Cashier
- Checkout
- Merchant Acquiring
---
