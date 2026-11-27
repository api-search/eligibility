---
api_specs:
- filename: national-australia-bank-gateway-payments-api-openapi.yml
  format: yaml
  label: National Australia Bank (NAB) Gateway Payments API
  slug: national-australia-bank-gateway-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/national-australia-bank/openapi/national-australia-bank-gateway-payments-api-openapi.yml
- filename: national-australia-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: National Australia Bank Banking Account Balances API
  slug: national-australia-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/national-australia-bank/openapi/national-australia-bank-banking-account-balances-api-openapi.yml
- filename: national-australia-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: National Australia Bank Banking Account Direct Debits API
  slug: national-australia-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/national-australia-bank/openapi/national-australia-bank-banking-account-direct-debits-api-openapi.yml
- filename: national-australia-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: National Australia Bank Banking Account Scheduled Payments API
  slug: national-australia-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/national-australia-bank/openapi/national-australia-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: national-australia-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: National Australia Bank Banking Account Transactions API
  slug: national-australia-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/national-australia-bank/openapi/national-australia-bank-banking-account-transactions-api-openapi.yml
- filename: national-australia-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: National Australia Bank Banking Accounts API
  slug: national-australia-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/national-australia-bank/openapi/national-australia-bank-banking-accounts-api-openapi.yml
- filename: national-australia-bank-banking-payees-api-openapi.yml
  format: yaml
  label: National Australia Bank Banking Payees API
  slug: national-australia-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/national-australia-bank/openapi/national-australia-bank-banking-payees-api-openapi.yml
- filename: national-australia-bank-banking-products-api-openapi.yml
  format: yaml
  label: National Australia Bank Banking Products API
  slug: national-australia-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/national-australia-bank/openapi/national-australia-bank-banking-products-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Life-critical services
    text: provide a service where the use or failure of the API Client could lead to death, personal injury, or environmental damage (such as the operation of nuclear facilities, air traffic control, or life support systems);
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: In order to access the APIs you will be required to submit an application providing certain information (such as name, contact details, company details, intended uses of the APIs)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: National Australia Bank
provenance_date: '2026-11-10'
provider_name: National Australia Bank
provider_slug: national-australia-bank
slug: national-australia-bank-eligibility
source_date: '2026-11-10'
source_filename: national-australia-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.nab.com.au/content/dam/nabrwd/documents/terms-and-conditions/services/nab-use-of-apis-developer-terms.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: National Australia Bank\naid: national-australia-bank\nurl: https://www.nab.com.au/content/dam/nabrwd/documents/terms-and-conditions/services/nab-use-of-apis-developer-terms.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Life-critical services\n  text: provide a service where the use or failure of the API Client could lead to death, personal injury, or environmental\n    damage (such as the operation of nuclear facilities, air traffic control, or life support systems);\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: In order to access the APIs you will be required to submit an application providing certain information\n    (such as name, contact details, company details, intended uses of the APIs)\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/national-australia-bank/eligibility/national-australia-bank-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from National Australia Bank's own page on 2026-11-10.
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
