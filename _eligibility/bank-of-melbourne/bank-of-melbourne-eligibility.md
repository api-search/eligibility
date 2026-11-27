---
api_specs:
- filename: bank-of-melbourne-cds-banking-products-openapi.yml
  format: yaml
  label: Bank of Melbourne CDR Product Reference Data API
  slug: bank-of-melbourne-cdr-product-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bank-of-melbourne/openapi/bank-of-melbourne-cds-banking-products-openapi.yml
- filename: bank-of-melbourne-cds-banking-products-openapi.yml
  format: yaml
  label: Bank of Melbourne CDR Accounts & Balances API
  slug: bank-of-melbourne-cdr-accounts-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bank-of-melbourne/openapi/bank-of-melbourne-cds-banking-products-openapi.yml
- filename: bank-of-melbourne-cds-banking-products-openapi.yml
  format: yaml
  label: Bank of Melbourne CDR Transactions API
  slug: bank-of-melbourne-cdr-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bank-of-melbourne/openapi/bank-of-melbourne-cds-banking-products-openapi.yml
- filename: bank-of-melbourne-cds-banking-products-openapi.yml
  format: yaml
  label: Bank of Melbourne CDR Direct Debits & Scheduled Payments API
  slug: bank-of-melbourne-cdr-direct-debits-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bank-of-melbourne/openapi/bank-of-melbourne-cds-banking-products-openapi.yml
- filename: bank-of-melbourne-cds-banking-products-openapi.yml
  format: yaml
  label: Bank of Melbourne CDR Payees API
  slug: bank-of-melbourne-cdr-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bank-of-melbourne/openapi/bank-of-melbourne-cds-banking-products-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: Unless otherwise specified, the products and services described on this website are available only in Australia
  entity_types:
  - text: Personal customers
    type: individual
  - text: Business customers
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Lending criteria apply to approval of credit products.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bank of Melbourne
provenance_date: '2026-11-09'
provider_name: Bank of Melbourne
provider_slug: bank-of-melbourne
slug: bank-of-melbourne-eligibility
source_date: '2026-11-09'
source_filename: bank-of-melbourne-eligibility.yml
source_heading: Eligibility
source_page: https://www.bankofmelbourne.com.au/help/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bank of Melbourne\naid: bank-of-melbourne\nurl: https://www.bankofmelbourne.com.au/help/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: Unless otherwise specified, the products and services described on this website are available only in Australia\nentity_types:\n- type: individual\n  text: Personal customers\n- type: business\n  text: Business customers\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Lending criteria apply to approval of credit products.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bank-of-melbourne/eligibility/bank-of-melbourne-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 4 quoted statements, read from Bank of Melbourne's own page on 2026-11-09.
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
- Westpac Group
---
