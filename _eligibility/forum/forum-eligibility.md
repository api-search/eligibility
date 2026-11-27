---
api_specs:
- filename: forum-account-api-openapi.yml
  format: yaml
  label: Forum Account API
  slug: forum-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forum/openapi/forum-account-api-openapi.yml
- filename: forum-exchange-api-openapi.yml
  format: yaml
  label: Forum Exchange API
  slug: forum-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forum/openapi/forum-exchange-api-openapi.yml
- filename: forum-fills-api-openapi.yml
  format: yaml
  label: Forum Fills API
  slug: forum-fills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forum/openapi/forum-fills-api-openapi.yml
- filename: forum-funding-api-openapi.yml
  format: yaml
  label: Forum Funding API
  slug: forum-funding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forum/openapi/forum-funding-api-openapi.yml
- filename: forum-indices-api-openapi.yml
  format: yaml
  label: Forum Indices API
  slug: forum-indices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forum/openapi/forum-indices-api-openapi.yml
- filename: forum-market-data-api-openapi.yml
  format: yaml
  label: Forum Market Data API
  slug: forum-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forum/openapi/forum-market-data-api-openapi.yml
- filename: forum-markets-api-openapi.yml
  format: yaml
  label: Forum Markets API
  slug: forum-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forum/openapi/forum-markets-api-openapi.yml
- filename: forum-orders-api-openapi.yml
  format: yaml
  label: Forum Orders API
  slug: forum-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forum/openapi/forum-orders-api-openapi.yml
- filename: forum-positions-api-openapi.yml
  format: yaml
  label: Forum Positions API
  slug: forum-positions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forum/openapi/forum-positions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Paper trading only, no real trades
    text: The Service provides a simulated trading environment using fictitious money for educational and informational purposes only. No real money is involved.
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
name: Forum
provenance_date: '2026-11-09'
provider_name: Forum
provider_slug: forum
slug: forum-eligibility
source_date: '2026-11-09'
source_filename: forum-eligibility.yml
source_heading: Eligibility
source_page: https://forum-legal.s3.us-east-2.amazonaws.com/terms-of-service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Forum\naid: forum\nurl: https://forum-legal.s3.us-east-2.amazonaws.com/terms-of-service.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\nrestricted_uses:\n- summary: Paper trading only, no real trades\n  text: The Service provides a simulated trading environment using fictitious money for educational and informational\n    purposes only. No real money is involved.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/forum/eligibility/forum-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Forum's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Trading
- Exchange
- Perpetual Futures
- Market Data
- Attention Economy
- Fintech
- WebSocket
- Real-Time
---
