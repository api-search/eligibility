---
api_specs:
- filename: ziina-account-api-openapi.yml
  format: yaml
  label: Ziina Account API
  slug: ziina-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-account-api-openapi.yml
- filename: ziina-log-api-openapi.yml
  format: yaml
  label: Ziina Log API
  slug: ziina-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-log-api-openapi.yml
- filename: ziina-paymentintent-api-openapi.yml
  format: yaml
  label: Ziina PaymentIntent API
  slug: ziina-paymentintent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-paymentintent-api-openapi.yml
- filename: ziina-refund-api-openapi.yml
  format: yaml
  label: Ziina Refund API
  slug: ziina-refund-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-refund-api-openapi.yml
- filename: ziina-transfer-api-openapi.yml
  format: yaml
  label: Ziina Transfer API
  slug: ziina-transfer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-transfer-api-openapi.yml
- filename: ziina-webhook-api-openapi.yml
  format: yaml
  label: Ziina Webhook API
  slug: ziina-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-webhook-api-openapi.yml
- filename: ziina-health-check-api-openapi.yml
  format: yaml
  label: Ziina Health Check API
  slug: ziina-health-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-health-check-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AE
    text: To create a personal Account, you must be a resident of the United Arab Emirates
  entity_types:
  - text: Ziina offers personal Accounts and, for Business Users, business Accounts.
    type: individual
  - text: Business Entity" means an entity which conducts business, irrespective of its legal form, including sole proprietorships, limited liability companies, free zone companies and free zone establishments
    type: business
  minimum_age:
    text: comply with any applicable age-related requirements imposed by Ziina or Applicable Law
    value: null
  restricted_uses:
  - summary: Prohibited business categories
    text: 'You undertake not to: (a) effect any transaction within or in relation to a Prohibited Business Category'
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
name: Ziina
provenance_date: '2026-11-10'
provider_name: Ziina
provider_slug: ziina
slug: ziina-eligibility
source_date: '2026-11-10'
source_filename: ziina-eligibility.yml
source_heading: Eligibility
source_page: https://ziina.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ziina\naid: ziina\nurl: https://ziina.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - AE\n  excluded: []\n  text: To create a personal Account, you must be a resident of the United Arab Emirates\nentity_types:\n- type: individual\n  text: Ziina offers personal Accounts and, for Business Users, business Accounts.\n- type: business\n  text: Business Entity\" means an entity which conducts business, irrespective of its legal form, including sole\n    proprietorships, limited liability companies, free zone companies and free zone establishments\nrestricted_uses:\n- summary: Prohibited\
  \ business categories\n  text: 'You undertake not to: (a) effect any transaction within or in relation to a Prohibited Business Category'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: comply with any applicable age-related requirements imposed by Ziina or Applicable Law\n"
source_yaml_url: https://artifacts.apis.io/ziina/eligibility/ziina-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Ziina's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Fintech
- United Arab Emirates
- MENA
- Money Transfer
- Wallets
---
