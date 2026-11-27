---
api_specs:
- filename: bankwest-banking-account-balances-api-openapi.yml
  format: yaml
  label: Bankwest Banking Account Balances API
  slug: bankwest-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankwest/openapi/bankwest-banking-account-balances-api-openapi.yml
- filename: bankwest-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Bankwest Banking Account Direct Debits API
  slug: bankwest-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankwest/openapi/bankwest-banking-account-direct-debits-api-openapi.yml
- filename: bankwest-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Bankwest Banking Account Scheduled Payments API
  slug: bankwest-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankwest/openapi/bankwest-banking-account-scheduled-payments-api-openapi.yml
- filename: bankwest-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Bankwest Banking Account Transactions API
  slug: bankwest-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankwest/openapi/bankwest-banking-account-transactions-api-openapi.yml
- filename: bankwest-banking-accounts-api-openapi.yml
  format: yaml
  label: Bankwest Banking Accounts API
  slug: bankwest-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankwest/openapi/bankwest-banking-accounts-api-openapi.yml
- filename: bankwest-banking-payees-api-openapi.yml
  format: yaml
  label: Bankwest Banking Payees API
  slug: bankwest-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankwest/openapi/bankwest-banking-payees-api-openapi.yml
- filename: bankwest-banking-products-api-openapi.yml
  format: yaml
  label: Bankwest Banking Products API
  slug: bankwest-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankwest/openapi/bankwest-banking-products-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: Our websites are provided for use by Australian residents only, and the products and services described in them are not directed at anyone outside Australia.
  entity_types:
  - text: Our websites are provided for use by Australian residents only
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use policy
    text: is used as a vehicle for, or may cause or result in Financial Abuse; is offensive, defamatory, harassing or threatening to any person
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Online applications and requests initiated outside Australia are not accepted from anyone who is not an existing Bankwest customer.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bankwest
provenance_date: '2026-11-09'
provider_name: Bankwest
provider_slug: bankwest
slug: bankwest-eligibility
source_date: '2026-11-09'
source_filename: bankwest-eligibility.yml
source_heading: Eligibility
source_page: https://www.bankwest.com.au/legal-stuff/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bankwest\naid: bankwest\nurl: https://www.bankwest.com.au/legal-stuff/website-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: Our websites are provided for use by Australian residents only, and the products and services described\n    in them are not directed at anyone outside Australia.\nentity_types:\n- type: individual\n  text: Our websites are provided for use by Australian residents only\nrestricted_uses:\n- summary: Acceptable use policy\n  text: is used as a vehicle for, or may cause or result in Financial Abuse; is offensive, defamatory, harassing\n    or\
  \ threatening to any person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Online applications and requests initiated outside Australia are not accepted from anyone who is not an\n    existing Bankwest customer.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bankwest/eligibility/bankwest-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Bankwest's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Banking
- Australia
- Product Reference Data
- Digital Bank
---
