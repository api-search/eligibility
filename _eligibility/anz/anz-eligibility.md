---
api_specs:
- filename: anz-banking-account-balances-api-openapi.yml
  format: yaml
  label: Australia and New Zealand Banking Group (ANZ) Banking Account Balances API
  slug: anz-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anz/openapi/anz-banking-account-balances-api-openapi.yml
- filename: anz-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Australia and New Zealand Banking Group (ANZ) Banking Account Direct Debits API
  slug: anz-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anz/openapi/anz-banking-account-direct-debits-api-openapi.yml
- filename: anz-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Australia and New Zealand Banking Group (ANZ) Banking Account Scheduled Payments API
  slug: anz-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anz/openapi/anz-banking-account-scheduled-payments-api-openapi.yml
- filename: anz-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Australia and New Zealand Banking Group (ANZ) Banking Account Transactions API
  slug: anz-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anz/openapi/anz-banking-account-transactions-api-openapi.yml
- filename: anz-banking-accounts-api-openapi.yml
  format: yaml
  label: Australia and New Zealand Banking Group (ANZ) Banking Accounts API
  slug: anz-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anz/openapi/anz-banking-accounts-api-openapi.yml
- filename: anz-banking-payees-api-openapi.yml
  format: yaml
  label: Australia and New Zealand Banking Group (ANZ) Banking Payees API
  slug: anz-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anz/openapi/anz-banking-payees-api-openapi.yml
- filename: anz-banking-products-api-openapi.yml
  format: yaml
  label: Australia and New Zealand Banking Group (ANZ) Banking Products API
  slug: anz-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anz/openapi/anz-banking-products-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: products and services discussed in the section of the ANZ website which refers to the Australian operations of any ANZ Group member (the "Australian Section") are designed and intended to be used only by Australian residents.
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
name: Australia and New Zealand Banking Group (ANZ)
provenance_date: '2026-11-09'
provider_name: Australia and New Zealand Banking Group (ANZ)
provider_slug: anz
slug: anz-eligibility
source_date: '2026-11-09'
source_filename: anz-eligibility.yml
source_heading: Eligibility
source_page: https://www.anz.com.au/support/legal/website-terms-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Australia and New Zealand Banking Group (ANZ)\naid: anz\nurl: https://www.anz.com.au/support/legal/website-terms-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: products and services discussed in the section of the ANZ website which refers to the Australian operations\n    of any ANZ Group member (the \"Australian Section\") are designed and intended to be used only by Australian residents.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anz/eligibility/anz-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Australia and New Zealand Banking Group (ANZ)'s own page on 2026-11-09.
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
