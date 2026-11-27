---
api_specs:
- filename: macquarie-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: Macquarie Bank Banking Account Balances API
  slug: macquarie-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macquarie-bank/openapi/macquarie-bank-banking-account-balances-api-openapi.yml
- filename: macquarie-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Macquarie Bank Banking Account Direct Debits API
  slug: macquarie-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macquarie-bank/openapi/macquarie-bank-banking-account-direct-debits-api-openapi.yml
- filename: macquarie-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Macquarie Bank Banking Account Scheduled Payments API
  slug: macquarie-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macquarie-bank/openapi/macquarie-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: macquarie-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Macquarie Bank Banking Account Transactions API
  slug: macquarie-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macquarie-bank/openapi/macquarie-bank-banking-account-transactions-api-openapi.yml
- filename: macquarie-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: Macquarie Bank Banking Accounts API
  slug: macquarie-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macquarie-bank/openapi/macquarie-bank-banking-accounts-api-openapi.yml
- filename: macquarie-bank-banking-payees-api-openapi.yml
  format: yaml
  label: Macquarie Bank Banking Payees API
  slug: macquarie-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macquarie-bank/openapi/macquarie-bank-banking-payees-api-openapi.yml
- filename: macquarie-bank-banking-products-api-openapi.yml
  format: yaml
  label: Macquarie Bank Banking Products API
  slug: macquarie-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macquarie-bank/openapi/macquarie-bank-banking-products-api-openapi.yml
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
    approval_required: null
    kyb: null
    kyc: null
    text: All applications for credit or lending products are subject to Macquarie Group’s standard credit approval criteria and/or product provider criteria.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Macquarie Bank
provenance_date: '2026-11-10'
provider_name: Macquarie Bank
provider_slug: macquarie-bank
slug: macquarie-bank-eligibility
source_date: '2026-11-10'
source_filename: macquarie-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.macquarie.com.au/important-information.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Macquarie Bank\naid: macquarie-bank\nurl: https://www.macquarie.com.au/important-information.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: All applications for credit or lending products are subject to Macquarie Group’s standard credit approval\n    criteria and/or product provider criteria.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/macquarie-bank/eligibility/macquarie-bank-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Macquarie Bank's own page on 2026-11-10.
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
- Payments
---
