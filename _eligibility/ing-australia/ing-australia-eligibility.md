---
api_specs:
- filename: ing-australia-banking-account-balances-api-openapi.yml
  format: yaml
  label: ING Australia Banking Account Balances API
  slug: ing-australia-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ing-australia/openapi/ing-australia-banking-account-balances-api-openapi.yml
- filename: ing-australia-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: ING Australia Banking Account Direct Debits API
  slug: ing-australia-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ing-australia/openapi/ing-australia-banking-account-direct-debits-api-openapi.yml
- filename: ing-australia-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: ING Australia Banking Account Scheduled Payments API
  slug: ing-australia-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ing-australia/openapi/ing-australia-banking-account-scheduled-payments-api-openapi.yml
- filename: ing-australia-banking-account-transactions-api-openapi.yml
  format: yaml
  label: ING Australia Banking Account Transactions API
  slug: ing-australia-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ing-australia/openapi/ing-australia-banking-account-transactions-api-openapi.yml
- filename: ing-australia-banking-accounts-api-openapi.yml
  format: yaml
  label: ING Australia Banking Accounts API
  slug: ing-australia-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ing-australia/openapi/ing-australia-banking-accounts-api-openapi.yml
- filename: ing-australia-banking-payees-api-openapi.yml
  format: yaml
  label: ING Australia Banking Payees API
  slug: ing-australia-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ing-australia/openapi/ing-australia-banking-payees-api-openapi.yml
- filename: ing-australia-banking-products-api-openapi.yml
  format: yaml
  label: ING Australia Banking Products API
  slug: ing-australia-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ing-australia/openapi/ing-australia-banking-products-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: The products and services described on the ING website are available only to Australian residents. Applications from people other than Australian residents will not be accepted.
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
name: ING Australia
provenance_date: '2026-11-09'
provider_name: ING Australia
provider_slug: ing-australia
slug: ing-australia-eligibility
source_date: '2026-11-09'
source_filename: ing-australia-eligibility.yml
source_heading: Eligibility
source_page: https://www.ing.com.au/legal.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ING Australia\naid: ing-australia\nurl: https://www.ing.com.au/legal.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: The products and services described on the ING website are available only to Australian residents. Applications\n    from people other than Australian residents will not be accepted.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ing-australia/eligibility/ing-australia-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from ING Australia's own page on 2026-11-09.
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
