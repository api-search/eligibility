---
api_specs:
- filename: beyond-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Account Balances API
  slug: beyond-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-account-balances-api-openapi.yml
- filename: beyond-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Account Direct Debits API
  slug: beyond-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-account-direct-debits-api-openapi.yml
- filename: beyond-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Account Scheduled Payments API
  slug: beyond-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: beyond-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Account Transactions API
  slug: beyond-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-account-transactions-api-openapi.yml
- filename: beyond-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Accounts API
  slug: beyond-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-accounts-api-openapi.yml
- filename: beyond-bank-banking-payees-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Payees API
  slug: beyond-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-payees-api-openapi.yml
- filename: beyond-bank-banking-products-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Products API
  slug: beyond-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-products-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: Unless otherwise stated, all products and services described in this site are issued by Beyond Bank Australia and are only available to Australian residents.
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
name: Beyond Bank Australia
provenance_date: '2026-11-09'
provider_name: Beyond Bank Australia
provider_slug: beyond-bank
slug: beyond-bank-eligibility
source_date: '2026-11-09'
source_filename: beyond-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.beyondbank.com.au/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beyond Bank Australia\naid: beyond-bank\nurl: https://www.beyondbank.com.au/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: Unless otherwise stated, all products and services described in this site are issued by Beyond Bank Australia\n    and are only available to Australian residents.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/beyond-bank/eligibility/beyond-bank-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Beyond Bank Australia's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Banking
- Australia
- Customer Owned
- Product Reference Data
---
