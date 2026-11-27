---
api_specs:
- filename: checkout-openapi-generated.yml
  format: yaml
  label: Checkout API
  slug: checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkout/openapi/_ae-authored/checkout-openapi-generated.yml
- filename: checkout-checkout-api-api-openapi.yml
  format: yaml
  label: Checkout Checkout API
  slug: checkout-checkout-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkout/openapi/checkout-checkout-api-api-openapi.yml
- filename: checkout-connect-api-openapi.yml
  format: yaml
  label: Checkout Connect API
  slug: checkout-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkout/openapi/checkout-connect-api-openapi.yml
- filename: checkout-payments-api-openapi.yml
  format: yaml
  label: Checkout Payments API
  slug: checkout-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkout/openapi/checkout-payments-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    - CA
    - NZ
    text: This information is for Checkout.com customers based in the United Kingdom that receive services from Checkout Ltd.
  entity_types:
  - text: Checkout.com customers based in the United Kingdom that receive services from Checkout Ltd.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Declined lines of business
    text: 'You may not use the Checkout.com service for activities that:'
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
name: Checkout
provenance_date: '2026-11-09'
provider_name: Checkout
provider_slug: checkout
slug: checkout-eligibility
source_date: '2026-11-09'
source_filename: checkout-eligibility.yml
source_heading: Eligibility
source_page: https://www.checkout.com/legal/terms-and-policies
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Checkout\naid: checkout\nurl: https://www.checkout.com/legal/terms-and-policies\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  - CA\n  - NZ\n  excluded: []\n  text: This information is for Checkout.com customers based in the United Kingdom that receive services from Checkout\n    Ltd.\nentity_types:\n- type: business\n  text: Checkout.com customers based in the United Kingdom that receive services from Checkout Ltd.\nrestricted_uses:\n- summary: Declined lines of business\n  text: 'You may not use the Checkout.com service for activities that:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/checkout/eligibility/checkout-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Checkout's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Fintech
- E-Commerce
- Global
---
