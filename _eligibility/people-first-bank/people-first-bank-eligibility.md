---
api_specs:
- filename: people-first-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: People First Bank Banking Account Balances API
  slug: people-first-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/people-first-bank/openapi/people-first-bank-banking-account-balances-api-openapi.yml
- filename: people-first-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: People First Bank Banking Account Direct Debits API
  slug: people-first-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/people-first-bank/openapi/people-first-bank-banking-account-direct-debits-api-openapi.yml
- filename: people-first-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: People First Bank Banking Account Scheduled Payments API
  slug: people-first-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/people-first-bank/openapi/people-first-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: people-first-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: People First Bank Banking Account Transactions API
  slug: people-first-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/people-first-bank/openapi/people-first-bank-banking-account-transactions-api-openapi.yml
- filename: people-first-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: People First Bank Banking Accounts API
  slug: people-first-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/people-first-bank/openapi/people-first-bank-banking-accounts-api-openapi.yml
- filename: people-first-bank-banking-payees-api-openapi.yml
  format: yaml
  label: People First Bank Banking Payees API
  slug: people-first-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/people-first-bank/openapi/people-first-bank-banking-payees-api-openapi.yml
- filename: people-first-bank-banking-products-api-openapi.yml
  format: yaml
  label: People First Bank Banking Products API
  slug: people-first-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/people-first-bank/openapi/people-first-bank-banking-products-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: The products and services described on the People First Bank website are available only to Australian residents and in relation to property in Australia. Applications from people that are not Australian residents will not be accepted.
  entity_types:
  - text: Applications from people that are not Australian residents will not be accepted.
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All applications for credit are subject to People First Bank's usual credit assessment criteria.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: People First Bank
provenance_date: '2026-11-10'
provider_name: People First Bank
provider_slug: people-first-bank
slug: people-first-bank-eligibility
source_date: '2026-11-10'
source_filename: people-first-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.peoplefirstbank.com.au/disclaimer
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: People First Bank\naid: people-first-bank\nurl: https://www.peoplefirstbank.com.au/disclaimer\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: The products and services described on the People First Bank website are available only to Australian residents\n    and in relation to property in Australia. Applications from people that are not Australian residents will not\n    be accepted.\nentity_types:\n- type: individual\n  text: Applications from people that are not Australian residents will not be accepted.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: All applications for credit are subject to People First Bank's usual credit assessment criteria.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/people-first-bank/eligibility/people-first-bank-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from People First Bank's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Banking
- Australia
- Mutual Bank
- Product Reference Data
---
