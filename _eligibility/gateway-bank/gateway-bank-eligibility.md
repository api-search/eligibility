---
api_specs:
- filename: gateway-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Account Balances API
  slug: gateway-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-account-balances-api-openapi.yml
- filename: gateway-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Account Direct Debits API
  slug: gateway-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-account-direct-debits-api-openapi.yml
- filename: gateway-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Account Scheduled Payments API
  slug: gateway-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: gateway-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Account Transactions API
  slug: gateway-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-account-transactions-api-openapi.yml
- filename: gateway-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Accounts API
  slug: gateway-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-accounts-api-openapi.yml
- filename: gateway-bank-banking-payees-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Payees API
  slug: gateway-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-payees-api-openapi.yml
- filename: gateway-bank-banking-products-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Products API
  slug: gateway-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-products-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The products and services described on this site are available only to applicants who satisfy our Membership criteria.
    type: other
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
name: Gateway Bank
provenance_date: '2026-11-09'
provider_name: Gateway Bank
provider_slug: gateway-bank
slug: gateway-bank-eligibility
source_date: '2026-11-09'
source_filename: gateway-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.gatewaybank.com.au/help-and-support/important-information/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gateway Bank\naid: gateway-bank\nurl: https://www.gatewaybank.com.au/help-and-support/important-information/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: The products and services described on this site are available only to applicants who satisfy our Membership\n    criteria.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gateway-bank/eligibility/gateway-bank-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Gateway Bank's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Banking
- Mutual Bank
- Customer Owned
- Australia
- Product Reference Data
---
