---
api_specs:
- filename: sponge-agents-api-openapi.yml
  format: yaml
  label: Sponge Agents API
  slug: sponge-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sponge/openapi/sponge-agents-api-openapi.yml
- filename: sponge-cards-api-openapi.yml
  format: yaml
  label: Sponge Cards API
  slug: sponge-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sponge/openapi/sponge-cards-api-openapi.yml
- filename: sponge-fiat-api-openapi.yml
  format: yaml
  label: Sponge Fiat API
  slug: sponge-fiat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sponge/openapi/sponge-fiat-api-openapi.yml
- filename: sponge-mpp-api-openapi.yml
  format: yaml
  label: Sponge MPP API
  slug: sponge-mpp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sponge/openapi/sponge-mpp-api-openapi.yml
- filename: sponge-payments-api-openapi.yml
  format: yaml
  label: Sponge Payments API
  slug: sponge-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sponge/openapi/sponge-payments-api-openapi.yml
- filename: sponge-secrets-api-openapi.yml
  format: yaml
  label: Sponge Secrets API
  slug: sponge-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sponge/openapi/sponge-secrets-api-openapi.yml
- filename: sponge-sponge-card-api-openapi.yml
  format: yaml
  label: Sponge Card API
  slug: sponge-sponge-card-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sponge/openapi/sponge-sponge-card-api-openapi.yml
- filename: sponge-trading-api-openapi.yml
  format: yaml
  label: Sponge Trading API
  slug: sponge-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sponge/openapi/sponge-trading-api-openapi.yml
- filename: sponge-transfers-api-openapi.yml
  format: yaml
  label: Sponge Transfers API
  slug: sponge-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sponge/openapi/sponge-transfers-api-openapi.yml
- filename: sponge-wallet-api-openapi.yml
  format: yaml
  label: Sponge Wallet API
  slug: sponge-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sponge/openapi/sponge-wallet-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
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
name: Sponge
provenance_date: '2026-11-10'
provider_name: Sponge
provider_slug: sponge
slug: sponge-eligibility
source_date: '2026-11-10'
source_filename: sponge-eligibility.yml
source_heading: Eligibility
source_page: https://paysponge.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sponge\naid: sponge\nurl: https://paysponge.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/sponge/eligibility/sponge-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Sponge's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Agentic Payments
- AI Agents
- Wallets
- Cryptocurrency
- Payments
- Stablecoins
- x402
- MPP
- Financial Infrastructure
- MCP
- Fintech
- Cards
- On-Ramp
---
