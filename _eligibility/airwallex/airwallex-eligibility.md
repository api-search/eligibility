---
api_specs:
- filename: airwallex-authentication-api-openapi.yml
  format: yaml
  label: Airwallex Authentication API
  slug: airwallex-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airwallex/openapi/airwallex-authentication-api-openapi.yml
- filename: airwallex-balances-api-openapi.yml
  format: yaml
  label: Airwallex Balances API
  slug: airwallex-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airwallex/openapi/airwallex-balances-api-openapi.yml
- filename: airwallex-beneficiaries-api-openapi.yml
  format: yaml
  label: Airwallex Beneficiaries API
  slug: airwallex-beneficiaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airwallex/openapi/airwallex-beneficiaries-api-openapi.yml
- filename: airwallex-customers-api-openapi.yml
  format: yaml
  label: Airwallex Customers API
  slug: airwallex-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airwallex/openapi/airwallex-customers-api-openapi.yml
- filename: airwallex-payment-intents-api-openapi.yml
  format: yaml
  label: Airwallex Payment Intents API
  slug: airwallex-payment-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airwallex/openapi/airwallex-payment-intents-api-openapi.yml
- filename: airwallex-payouts-api-openapi.yml
  format: yaml
  label: Airwallex Payouts API
  slug: airwallex-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airwallex/openapi/airwallex-payouts-api-openapi.yml
- filename: airwallex-refunds-api-openapi.yml
  format: yaml
  label: Airwallex Refunds API
  slug: airwallex-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airwallex/openapi/airwallex-refunds-api-openapi.yml
- filename: airwallex-transfers-api-openapi.yml
  format: yaml
  label: Airwallex Transfers API
  slug: airwallex-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airwallex/openapi/airwallex-transfers-api-openapi.yml
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
    text: As part of the onboarding process, we will ask you to provide us with certain information about your company so we can make this decision.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Airwallex
provenance_date: '2026-11-09'
provider_name: Airwallex
provider_slug: airwallex
slug: airwallex-eligibility
source_date: '2026-11-09'
source_filename: airwallex-eligibility.yml
source_heading: Eligibility
source_page: https://www.airwallex.com/global/terms/sign-up-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airwallex\naid: airwallex\nurl: https://www.airwallex.com/global/terms/sign-up-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As part of the onboarding process, we will ask you to provide us with certain information about your company\n    so we can make this decision.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/airwallex/eligibility/airwallex-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Airwallex's own page on 2026-11-09.
synthetic: false
tags:
- Cross-Border Payments
- Fintech
- Foreign Exchange
- Payments
- Global
- Embedded Finance
- Multi-Currency
---
