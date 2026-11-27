---
api_specs:
- filename: zopa-account-access-api-openapi.yml
  format: yaml
  label: zopa Account Access API
  slug: zopa-account-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-account-access-api-openapi.yml
- filename: zopa-accounts-api-openapi.yml
  format: yaml
  label: zopa Accounts API
  slug: zopa-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-accounts-api-openapi.yml
- filename: zopa-balances-api-openapi.yml
  format: yaml
  label: zopa Balances API
  slug: zopa-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-balances-api-openapi.yml
- filename: zopa-beneficiaries-api-openapi.yml
  format: yaml
  label: zopa Beneficiaries API
  slug: zopa-beneficiaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-beneficiaries-api-openapi.yml
- filename: zopa-direct-debits-api-openapi.yml
  format: yaml
  label: zopa Direct Debits API
  slug: zopa-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-direct-debits-api-openapi.yml
- filename: zopa-domestic-payments-api-openapi.yml
  format: yaml
  label: zopa Domestic Payments API
  slug: zopa-domestic-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-domestic-payments-api-openapi.yml
- filename: zopa-domestic-standing-orders-api-openapi.yml
  format: yaml
  label: zopa Domestic Standing Orders API
  slug: zopa-domestic-standing-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-domestic-standing-orders-api-openapi.yml
- filename: zopa-offers-api-openapi.yml
  format: yaml
  label: zopa Offers API
  slug: zopa-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-offers-api-openapi.yml
- filename: zopa-parties-api-openapi.yml
  format: yaml
  label: zopa Parties API
  slug: zopa-parties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-parties-api-openapi.yml
- filename: zopa-standing-orders-api-openapi.yml
  format: yaml
  label: zopa Standing Orders API
  slug: zopa-standing-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-standing-orders-api-openapi.yml
- filename: zopa-statements-api-openapi.yml
  format: yaml
  label: zopa Statements API
  slug: zopa-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-statements-api-openapi.yml
- filename: zopa-transactions-api-openapi.yml
  format: yaml
  label: zopa Transactions API
  slug: zopa-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-transactions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: You'll need to be a UK resident, at least 18 years old, with an email address.
  entity_types:
  - text: You'll need to be a UK resident, at least 18 years old, with an email address.
    type: individual
  minimum_age:
    text: at least 18 years old
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If the correct security details are used, we'll assume we're dealing with you and that we're authorised to take action.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: zopa
provenance_date: '2026-11-10'
provider_name: zopa
provider_slug: zopa
slug: zopa-eligibility
source_date: '2026-11-10'
source_filename: zopa-eligibility.yml
source_heading: Eligibility
source_page: https://www.zopa.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: zopa\naid: zopa\nurl: https://www.zopa.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: You'll need to be a UK resident, at least 18 years old, with an email address.\nentity_types:\n- type: individual\n  text: You'll need to be a UK resident, at least 18 years old, with an email address.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If the correct security details are used, we'll assume we're dealing with you and that we're authorised\n    to take action.\nminimum_age:\n  value: '18'\n  text: at least 18 years\
  \ old\n"
source_yaml_url: https://artifacts.apis.io/zopa/eligibility/zopa-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from zopa's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Banking
- Fintech
- Open Banking
- PSD2
- Payments
- Account Information
- Payment Initiation
- FAPI
- United Kingdom
- Digital Bank
- Lending
---
