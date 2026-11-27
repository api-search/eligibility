---
api_specs:
- filename: bank-first-banking-account-balances-api-openapi.yml
  format: yaml
  label: Bank First Banking Account Balances API
  slug: bank-first-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bank-first/openapi/bank-first-banking-account-balances-api-openapi.yml
- filename: bank-first-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Bank First Banking Account Direct Debits API
  slug: bank-first-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bank-first/openapi/bank-first-banking-account-direct-debits-api-openapi.yml
- filename: bank-first-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Bank First Banking Account Scheduled Payments API
  slug: bank-first-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bank-first/openapi/bank-first-banking-account-scheduled-payments-api-openapi.yml
- filename: bank-first-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Bank First Banking Account Transactions API
  slug: bank-first-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bank-first/openapi/bank-first-banking-account-transactions-api-openapi.yml
- filename: bank-first-banking-accounts-api-openapi.yml
  format: yaml
  label: Bank First Banking Accounts API
  slug: bank-first-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bank-first/openapi/bank-first-banking-accounts-api-openapi.yml
- filename: bank-first-banking-payees-api-openapi.yml
  format: yaml
  label: Bank First Banking Payees API
  slug: bank-first-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bank-first/openapi/bank-first-banking-payees-api-openapi.yml
- filename: bank-first-banking-products-api-openapi.yml
  format: yaml
  label: Bank First Banking Products API
  slug: bank-first-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bank-first/openapi/bank-first-banking-products-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The products and services on this website are not marketed to or intended for residents of the European Union.
  minimum_age:
    text: Strong Start Saver is our online savings account designed for members 15 -35 (inclusive).
    value: '15'
  restricted_uses:
  - summary: Super Saver Account limited to partner organisation employees
    text: The Super Saver Account is intended for employees of approved partner organisation and their immediate family members.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A valid promotion code must be entered at the time of application. Applications submitted without a valid promotion code will not be accepted.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bank First
provenance_date: '2026-11-09'
provider_name: Bank First
provider_slug: bank-first
slug: bank-first-eligibility
source_date: '2026-11-09'
source_filename: bank-first-eligibility.yml
source_heading: Eligibility
source_page: https://www.bankfirst.com.au/disclosure-documents
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bank First\naid: bank-first\nurl: https://www.bankfirst.com.au/disclosure-documents\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The products and services on this website are not marketed to or intended for residents of the European\n    Union.\nentity_types: []\nrestricted_uses:\n- summary: Super Saver Account limited to partner organisation employees\n  text: The Super Saver Account is intended for employees of approved partner organisation and their immediate family\n    members.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ A valid promotion code must be entered at the time of application. Applications submitted without a valid\n    promotion code will not be accepted.\nminimum_age:\n  value: '15'\n  text: Strong Start Saver is our online savings account designed for members 15 -35 (inclusive).\n"
source_yaml_url: https://artifacts.apis.io/bank-first/eligibility/bank-first-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bank First's own page on 2026-11-09.
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
