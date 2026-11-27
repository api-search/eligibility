---
api_specs:
- filename: bendigo-and-adelaide-bank-accounts-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Accounts API
  slug: bendigo-and-adelaide-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-accounts-api-openapi.yml
- filename: bendigo-and-adelaide-bank-attachments-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Attachments API
  slug: bendigo-and-adelaide-bank-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-attachments-api-openapi.yml
- filename: bendigo-and-adelaide-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Banking Account Balances API
  slug: bendigo-and-adelaide-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-banking-account-balances-api-openapi.yml
- filename: bendigo-and-adelaide-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Banking Account Direct Debits API
  slug: bendigo-and-adelaide-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-banking-account-direct-debits-api-openapi.yml
- filename: bendigo-and-adelaide-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Banking Account Scheduled Payments API
  slug: bendigo-and-adelaide-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: bendigo-and-adelaide-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Banking Account Transactions API
  slug: bendigo-and-adelaide-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-banking-account-transactions-api-openapi.yml
- filename: bendigo-and-adelaide-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Banking Accounts API
  slug: bendigo-and-adelaide-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-banking-accounts-api-openapi.yml
- filename: bendigo-and-adelaide-bank-banking-payees-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Banking Payees API
  slug: bendigo-and-adelaide-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-banking-payees-api-openapi.yml
- filename: bendigo-and-adelaide-bank-banking-products-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Banking Products API
  slug: bendigo-and-adelaide-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-banking-products-api-openapi.yml
- filename: bendigo-and-adelaide-bank-categories-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Categories API
  slug: bendigo-and-adelaide-bank-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-categories-api-openapi.yml
- filename: bendigo-and-adelaide-bank-tags-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Tags API
  slug: bendigo-and-adelaide-bank-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-tags-api-openapi.yml
- filename: bendigo-and-adelaide-bank-transactions-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Transactions API
  slug: bendigo-and-adelaide-bank-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-transactions-api-openapi.yml
- filename: bendigo-and-adelaide-bank-utility-endpoints-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Utility endpoints API
  slug: bendigo-and-adelaide-bank-utility-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-utility-endpoints-api-openapi.yml
- filename: bendigo-and-adelaide-bank-webhooks-api-openapi.yml
  format: yaml
  label: Bendigo and Adelaide Bank Webhooks API
  slug: bendigo-and-adelaide-bank-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bendigo-and-adelaide-bank/openapi/bendigo-and-adelaide-bank-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: This Website is not directed at persons in any country other than Australia and should therefore not be relied upon by such persons.
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
name: Bendigo and Adelaide Bank
provenance_date: '2026-11-09'
provider_name: Bendigo and Adelaide Bank
provider_slug: bendigo-and-adelaide-bank
slug: bendigo-and-adelaide-bank-eligibility
source_date: '2026-11-09'
source_filename: bendigo-and-adelaide-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.bendigobank.com.au/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bendigo and Adelaide Bank\naid: bendigo-and-adelaide-bank\nurl: https://www.bendigobank.com.au/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: This Website is not directed at persons in any country other than Australia and should therefore not be\n    relied upon by such persons.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bendigo-and-adelaide-bank/eligibility/bendigo-and-adelaide-bank-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Bendigo and Adelaide Bank's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Data Right
- Consumer Banking
- Australia
- Product Reference Data
---
