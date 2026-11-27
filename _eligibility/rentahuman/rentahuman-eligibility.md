---
api_specs:
- filename: rentahuman-bookings-api-openapi.yml
  format: yaml
  label: Rentahuman Bookings API
  slug: rentahuman-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rentahuman/openapi/rentahuman-bookings-api-openapi.yml
- filename: rentahuman-humans-api-openapi.yml
  format: yaml
  label: Rentahuman Humans API
  slug: rentahuman-humans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rentahuman/openapi/rentahuman-humans-api-openapi.yml
- filename: rentahuman-wallet-api-openapi.yml
  format: yaml
  label: Rentahuman Wallet API
  slug: rentahuman-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rentahuman/openapi/rentahuman-wallet-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Posters are individuals who are 18 years of age or older or legal entities, businesses, or enterprises acting through an authorized representative
    type: business
  - text: Workers are individuals who are 18 years of age or older who register on the Platform
    type: individual
  minimum_age:
    text: You must be at least 18 years of age (or the age of majority in your jurisdiction) to use the Platform.
    value: '18'
  restricted_uses:
  - summary: No alcohol or illegal goods or services
    text: (j) will not use the Platform for the purchase or delivery of alcohol, or any other controlled or illegal substances or goods or services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may require identity, payment, location, or other verification for certain users or transactions in our discretion
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rentahuman
provenance_date: '2026-11-10'
provider_name: Rentahuman
provider_slug: rentahuman
slug: rentahuman-eligibility
source_date: '2026-11-10'
source_filename: rentahuman-eligibility.yml
source_heading: Eligibility
source_page: https://rentahuman.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rentahuman\naid: rentahuman\nurl: https://rentahuman.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Posters are individuals who are 18 years of age or older or legal entities, businesses, or enterprises acting\n    through an authorized representative\n- type: individual\n  text: Workers are individuals who are 18 years of age or older who register on the Platform\nrestricted_uses:\n- summary: No alcohol or illegal goods or services\n  text: (j) will not use the Platform for the purchase or delivery of alcohol,\
  \ or any other controlled or illegal\n    substances or goods or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we may require identity, payment, location, or other verification for certain users or transactions in our\n    discretion\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the age of majority in your jurisdiction) to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/rentahuman/eligibility/rentahuman-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Rentahuman's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- AI Agents
- Human-in-the-Loop
- Gig Economy
- MCP
- Labor
- Payments
---
