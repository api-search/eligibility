---
api_specs:
- filename: auswide-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: Auswide Bank Banking Account Balances API
  slug: auswide-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auswide-bank/openapi/auswide-bank-banking-account-balances-api-openapi.yml
- filename: auswide-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Auswide Bank Banking Account Direct Debits API
  slug: auswide-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auswide-bank/openapi/auswide-bank-banking-account-direct-debits-api-openapi.yml
- filename: auswide-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Auswide Bank Banking Account Scheduled Payments API
  slug: auswide-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auswide-bank/openapi/auswide-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: auswide-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Auswide Bank Banking Account Transactions API
  slug: auswide-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auswide-bank/openapi/auswide-bank-banking-account-transactions-api-openapi.yml
- filename: auswide-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: Auswide Bank Banking Accounts API
  slug: auswide-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auswide-bank/openapi/auswide-bank-banking-accounts-api-openapi.yml
- filename: auswide-bank-banking-payees-api-openapi.yml
  format: yaml
  label: Auswide Bank Banking Payees API
  slug: auswide-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auswide-bank/openapi/auswide-bank-banking-payees-api-openapi.yml
- filename: auswide-bank-banking-products-api-openapi.yml
  format: yaml
  label: Auswide Bank Banking Products API
  slug: auswide-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auswide-bank/openapi/auswide-bank-banking-products-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: Unless otherwise stated or agreed with you, the information on this Site has been prepared in accordance with Australian law for residents of Australia and for the supply of products or services in Australia.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Products & Services are only available to approved applicants and, in particular, all applications for credit are subject to normal credit approval criteria.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Auswide Bank
provenance_date: '2026-11-09'
provider_name: Auswide Bank
provider_slug: auswide-bank
slug: auswide-bank-eligibility
source_date: '2026-11-09'
source_filename: auswide-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.auswidebank.com.au/about/website-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Auswide Bank\naid: auswide-bank\nurl: https://www.auswidebank.com.au/about/website-terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: Unless otherwise stated or agreed with you, the information on this Site has been prepared in accordance\n    with Australian law for residents of Australia and for the supply of products or services in Australia.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Products & Services are only available to approved applicants and, in particular, all applications for\n\
  \    credit are subject to normal credit approval criteria.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/auswide-bank/eligibility/auswide-bank-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Auswide Bank's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Banking
- Australia
- Product Reference Data
- ADI
---
