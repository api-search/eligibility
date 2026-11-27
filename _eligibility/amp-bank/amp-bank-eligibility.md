---
api_specs:
- filename: amp-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: AMP Bank Banking Account Balances API
  slug: amp-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amp-bank/openapi/amp-bank-banking-account-balances-api-openapi.yml
- filename: amp-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: AMP Bank Banking Account Direct Debits API
  slug: amp-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amp-bank/openapi/amp-bank-banking-account-direct-debits-api-openapi.yml
- filename: amp-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: AMP Bank Banking Account Scheduled Payments API
  slug: amp-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amp-bank/openapi/amp-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: amp-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: AMP Bank Banking Account Transactions API
  slug: amp-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amp-bank/openapi/amp-bank-banking-account-transactions-api-openapi.yml
- filename: amp-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: AMP Bank Banking Accounts API
  slug: amp-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amp-bank/openapi/amp-bank-banking-accounts-api-openapi.yml
- filename: amp-bank-banking-payees-api-openapi.yml
  format: yaml
  label: AMP Bank Banking Payees API
  slug: amp-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amp-bank/openapi/amp-bank-banking-payees-api-openapi.yml
- filename: amp-bank-banking-products-api-openapi.yml
  format: yaml
  label: AMP Bank GO Banking Products API
  slug: amp-bank-go-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amp-bank/openapi/amp-bank-banking-products-api-openapi.yml
- filename: amp-bank-banking-products-api-openapi.yml
  format: yaml
  label: AMP Bank Banking Products API
  slug: amp-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amp-bank/openapi/amp-bank-banking-products-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: This website is for only for the use of persons accessing the website from within Australia.
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
name: AMP Bank
provenance_date: '2026-11-09'
provider_name: AMP Bank
provider_slug: amp-bank
slug: amp-bank-eligibility
source_date: '2026-11-09'
source_filename: amp-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.amp.com.au/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AMP Bank\naid: amp-bank\nurl: https://www.amp.com.au/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: This website is for only for the use of persons accessing the website from within Australia.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amp-bank/eligibility/amp-bank-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from AMP Bank's own page on 2026-11-09.
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
