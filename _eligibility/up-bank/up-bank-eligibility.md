---
api_specs:
- filename: up-bank-accounts-api-openapi.yml
  format: yaml
  label: Up Accounts API
  slug: up-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-accounts-api-openapi.yml
- filename: up-bank-attachments-api-openapi.yml
  format: yaml
  label: Up Attachments API
  slug: up-bank-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-attachments-api-openapi.yml
- filename: up-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: Up Banking Account Balances API
  slug: up-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-banking-account-balances-api-openapi.yml
- filename: up-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Up Banking Account Direct Debits API
  slug: up-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-banking-account-direct-debits-api-openapi.yml
- filename: up-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Up Banking Account Scheduled Payments API
  slug: up-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: up-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Up Banking Account Transactions API
  slug: up-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-banking-account-transactions-api-openapi.yml
- filename: up-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: Up Banking Accounts API
  slug: up-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-banking-accounts-api-openapi.yml
- filename: up-bank-banking-payees-api-openapi.yml
  format: yaml
  label: Up Banking Payees API
  slug: up-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-banking-payees-api-openapi.yml
- filename: up-bank-banking-products-api-openapi.yml
  format: yaml
  label: Up Banking Products API
  slug: up-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-banking-products-api-openapi.yml
- filename: up-bank-categories-api-openapi.yml
  format: yaml
  label: Up Categories API
  slug: up-bank-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-categories-api-openapi.yml
- filename: up-bank-tags-api-openapi.yml
  format: yaml
  label: Up Tags API
  slug: up-bank-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-tags-api-openapi.yml
- filename: up-bank-transactions-api-openapi.yml
  format: yaml
  label: Up Transactions API
  slug: up-bank-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-transactions-api-openapi.yml
- filename: up-bank-utility-endpoints-api-openapi.yml
  format: yaml
  label: Up Utility endpoints API
  slug: up-bank-utility-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-utility-endpoints-api-openapi.yml
- filename: up-bank-webhooks-api-openapi.yml
  format: yaml
  label: Up Webhooks API
  slug: up-bank-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/up-bank/openapi/up-bank-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: At this time the Up API is provided for your personal use only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial applications
    text: Attempting to extract data (such as merchant data) for use in commercial applications
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
name: Up
provenance_date: '2026-11-10'
provider_name: Up
provider_slug: up-bank
slug: up-bank-eligibility
source_date: '2026-11-10'
source_filename: up-bank-eligibility.yml
source_heading: Eligibility
source_page: https://up.com.au/api-acceptable-use-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Up\naid: up-bank\nurl: https://up.com.au/api-acceptable-use-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: At this time the Up API is provided for your personal use only.\nrestricted_uses:\n- summary: Commercial applications\n  text: Attempting to extract data (such as merchant data) for use in commercial applications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/up-bank/eligibility/up-bank-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Up's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Banking
- Australia
- Neobank
- Product Reference Data
---
