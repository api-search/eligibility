---
api_specs:
- filename: brite-payments-openapi-generated.yml
  format: yaml
  label: Brite Payments API
  slug: brite-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brite-payments/openapi/_ae-authored/brite-payments-openapi-generated.yml
- filename: brite-payments-assets-api-openapi.yml
  format: yaml
  label: Brite Payments Assets API
  slug: brite-payments-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brite-payments/openapi/brite-payments-assets-api-openapi.yml
- filename: brite-payments-bank-account-api-openapi.yml
  format: yaml
  label: Brite Payments Bank Account API
  slug: brite-payments-bank-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brite-payments/openapi/brite-payments-bank-account-api-openapi.yml
- filename: brite-payments-brite-payments-api-api-openapi.yml
  format: yaml
  label: Brite Payments Brite Payments API
  slug: brite-payments-brite-payments-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brite-payments/openapi/brite-payments-brite-payments-api-api-openapi.yml
- filename: brite-payments-callback-api-openapi.yml
  format: yaml
  label: Brite Payments Callback API
  slug: brite-payments-callback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brite-payments/openapi/brite-payments-callback-api-openapi.yml
- filename: brite-payments-session-api-openapi.yml
  format: yaml
  label: Brite Payments Session API
  slug: brite-payments-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brite-payments/openapi/brite-payments-session-api-openapi.yml
- filename: brite-payments-transaction-api-openapi.yml
  format: yaml
  label: Brite Payments Transaction API
  slug: brite-payments-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brite-payments/openapi/brite-payments-transaction-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: only use an account opened in your name and located within the EEA
  entity_types:
  - text: The Terms and Conditions apply to private individuals
    type: individual
  minimum_age:
    text: you must be of at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Violation of law or third-party agreements
    text: you shall not use the Service for any purpose that is in violation of its agreements with third parties or applicable law.
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
name: Brite Payments
provenance_date: '2026-11-09'
provider_name: Brite Payments
provider_slug: brite-payments
slug: brite-payments-eligibility
source_date: '2026-11-09'
source_filename: brite-payments-eligibility.yml
source_heading: Eligibility
source_page: https://britepayments.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brite Payments\naid: brite-payments\nurl: https://britepayments.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: only use an account opened in your name and located within the EEA\nentity_types:\n- type: individual\n  text: The Terms and Conditions apply to private individuals\nrestricted_uses:\n- summary: Violation of law or third-party agreements\n  text: you shall not use the Service for any purpose that is in violation of its agreements with third parties\n    or applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: you must be of at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/brite-payments/eligibility/brite-payments-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Brite Payments's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Europe
- Online Payments
---
