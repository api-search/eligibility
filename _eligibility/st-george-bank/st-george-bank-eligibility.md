---
api_specs:
- filename: st-george-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: St.George Bank Banking Account Balances API
  slug: st-george-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/st-george-bank/openapi/st-george-bank-banking-account-balances-api-openapi.yml
- filename: st-george-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: St.George Bank Banking Account Direct Debits API
  slug: st-george-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/st-george-bank/openapi/st-george-bank-banking-account-direct-debits-api-openapi.yml
- filename: st-george-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: St.George Bank Banking Account Scheduled Payments API
  slug: st-george-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/st-george-bank/openapi/st-george-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: st-george-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: St.George Bank Banking Account Transactions API
  slug: st-george-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/st-george-bank/openapi/st-george-bank-banking-account-transactions-api-openapi.yml
- filename: st-george-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: St.George Bank Banking Accounts API
  slug: st-george-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/st-george-bank/openapi/st-george-bank-banking-accounts-api-openapi.yml
- filename: st-george-bank-banking-payees-api-openapi.yml
  format: yaml
  label: St.George Bank Banking Payees API
  slug: st-george-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/st-george-bank/openapi/st-george-bank-banking-payees-api-openapi.yml
- filename: st-george-bank-banking-products-api-openapi.yml
  format: yaml
  label: St.George Bank Banking Products API
  slug: st-george-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/st-george-bank/openapi/st-george-bank-banking-products-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Unless otherwise specified, the products and services described on this website are available only in Australia
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Lending criteria apply to approval of credit products.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: St.George Bank
provenance_date: '2026-11-10'
provider_name: St.George Bank
provider_slug: st-george-bank
slug: st-george-bank-eligibility
source_date: '2026-11-10'
source_filename: st-george-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.stgeorge.com.au/help/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: St.George Bank\naid: st-george-bank\nurl: https://www.stgeorge.com.au/help/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Unless otherwise specified, the products and services described on this website are available only in Australia\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Lending criteria apply to approval of credit products.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/st-george-bank/eligibility/st-george-bank-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from St.George Bank's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Banking
- Australia
- Product Reference Data
- Westpac Group
---
