---
api_specs:
- filename: hsbc-australia-banking-account-balances-api-openapi.yml
  format: yaml
  label: HSBC Bank Australia Banking Account Balances API
  slug: hsbc-australia-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hsbc-australia/openapi/hsbc-australia-banking-account-balances-api-openapi.yml
- filename: hsbc-australia-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: HSBC Bank Australia Banking Account Direct Debits API
  slug: hsbc-australia-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hsbc-australia/openapi/hsbc-australia-banking-account-direct-debits-api-openapi.yml
- filename: hsbc-australia-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: HSBC Bank Australia Banking Account Scheduled Payments API
  slug: hsbc-australia-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hsbc-australia/openapi/hsbc-australia-banking-account-scheduled-payments-api-openapi.yml
- filename: hsbc-australia-banking-account-transactions-api-openapi.yml
  format: yaml
  label: HSBC Bank Australia Banking Account Transactions API
  slug: hsbc-australia-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hsbc-australia/openapi/hsbc-australia-banking-account-transactions-api-openapi.yml
- filename: hsbc-australia-banking-accounts-api-openapi.yml
  format: yaml
  label: HSBC Bank Australia Banking Accounts API
  slug: hsbc-australia-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hsbc-australia/openapi/hsbc-australia-banking-accounts-api-openapi.yml
- filename: hsbc-australia-banking-payees-api-openapi.yml
  format: yaml
  label: HSBC Bank Australia Banking Payees API
  slug: hsbc-australia-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hsbc-australia/openapi/hsbc-australia-banking-payees-api-openapi.yml
- filename: hsbc-australia-banking-products-api-openapi.yml
  format: yaml
  label: HSBC Bank Australia Banking Products API
  slug: hsbc-australia-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hsbc-australia/openapi/hsbc-australia-banking-products-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: This website is designed for use in Australia.
  entity_types:
  - text: if you are an individual consumer, our Privacy Policy contains more information which you should read alongside this CDR Policy
    type: individual
  - text: depending on whether you interact with us as an individual consumer or a business customer
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: go through our authentication process to verify the request; verify that the third party is accredited on the ACCC's Register to receive data; authenticate you as an HSBC Australia customer
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HSBC Bank Australia
provenance_date: '2026-11-09'
provider_name: HSBC Bank Australia
provider_slug: hsbc-australia
slug: hsbc-australia-eligibility
source_date: '2026-11-09'
source_filename: hsbc-australia-eligibility.yml
source_heading: Eligibility
source_page: https://www.hsbc.com.au/legal/consumer-data-right-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HSBC Bank Australia\naid: hsbc-australia\nurl: https://www.hsbc.com.au/legal/consumer-data-right-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: This website is designed for use in Australia.\nentity_types:\n- type: individual\n  text: if you are an individual consumer, our Privacy Policy contains more information which you should read alongside\n    this CDR Policy\n- type: business\n  text: depending on whether you interact with us as an individual consumer or a business customer\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: go through our authentication process to verify the request; verify that the third party is accredited on\n    the ACCC's Register to receive data; authenticate you as an HSBC Australia customer\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hsbc-australia/eligibility/hsbc-australia-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 4 quoted statements, read from HSBC Bank Australia's own page on 2026-11-09.
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
---
