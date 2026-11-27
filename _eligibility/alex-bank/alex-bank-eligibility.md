---
api_specs:
- filename: alex-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: Alex Bank Banking Account Balances API
  slug: alex-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alex-bank/openapi/alex-bank-banking-account-balances-api-openapi.yml
- filename: alex-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Alex Bank Banking Account Direct Debits API
  slug: alex-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alex-bank/openapi/alex-bank-banking-account-direct-debits-api-openapi.yml
- filename: alex-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Alex Bank Banking Account Scheduled Payments API
  slug: alex-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alex-bank/openapi/alex-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: alex-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Alex Bank Banking Account Transactions API
  slug: alex-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alex-bank/openapi/alex-bank-banking-account-transactions-api-openapi.yml
- filename: alex-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: Alex Bank Banking Accounts API
  slug: alex-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alex-bank/openapi/alex-bank-banking-accounts-api-openapi.yml
- filename: alex-bank-banking-payees-api-openapi.yml
  format: yaml
  label: Alex Bank Banking Payees API
  slug: alex-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alex-bank/openapi/alex-bank-banking-payees-api-openapi.yml
- filename: alex-bank-banking-products-api-openapi.yml
  format: yaml
  label: Alex Bank Banking Products API
  slug: alex-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alex-bank/openapi/alex-bank-banking-products-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Loan applications are subject to credit approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Alex Bank
provenance_date: '2026-11-09'
provider_name: Alex Bank
provider_slug: alex-bank
slug: alex-bank-eligibility
source_date: '2026-11-09'
source_filename: alex-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.alex.bank/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alex Bank\naid: alex-bank\nurl: https://www.alex.bank/legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Loan applications are subject to credit approval.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alex-bank/eligibility/alex-bank-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Alex Bank's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Data Right
- Consumer Banking
- Australia
- Digital Bank
- Product Reference Data
---
