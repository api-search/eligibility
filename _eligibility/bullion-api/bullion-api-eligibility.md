---
api_specs:
- filename: bullion-api-bullion-api-api-api-openapi.yml
  format: yaml
  label: Bullion API Bullion API API
  slug: bullion-api-bullion-api-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-bullion-api-api-api-openapi.yml
- filename: bullion-api-central-bank-gold-api-openapi.yml
  format: yaml
  label: Bullion API Central Bank Gold API
  slug: bullion-api-central-bank-gold-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-central-bank-gold-api-openapi.yml
- filename: bullion-api-central-bank-reserves-api-openapi.yml
  format: yaml
  label: Bullion API Central Bank Reserves API
  slug: bullion-api-central-bank-reserves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-central-bank-reserves-api-openapi.yml
- filename: bullion-api-countries-api-openapi.yml
  format: yaml
  label: Bullion API Countries API
  slug: bullion-api-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-countries-api-openapi.yml
- filename: bullion-api-gold-api-openapi.yml
  format: yaml
  label: Bullion API Gold API
  slug: bullion-api-gold-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-gold-api-openapi.yml
- filename: bullion-api-portfolio-api-openapi.yml
  format: yaml
  label: Bullion API Portfolio API
  slug: bullion-api-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-portfolio-api-openapi.yml
- filename: bullion-api-silver-api-openapi.yml
  format: yaml
  label: Bullion API Silver API
  slug: bullion-api-silver-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-silver-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter a contract in your jurisdiction.
    type: individual
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Market manipulation or unverified automated trading
    text: Use the data for market manipulation, insider trading, or to inform automated trading decisions without independent verification.
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
name: Bullion API
provenance_date: '2026-11-09'
provider_name: Bullion API
provider_slug: bullion-api
slug: bullion-api-eligibility
source_date: '2026-11-09'
source_filename: bullion-api-eligibility.yml
source_heading: Eligibility
source_page: https://bullionapi.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bullion API\naid: bullion-api\nurl: https://bullionapi.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter a contract in your jurisdiction.\nrestricted_uses:\n- summary: Market manipulation or unverified automated trading\n  text: Use the data for market manipulation, insider trading, or to inform automated trading decisions without\n    independent verification.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/bullion-api/eligibility/bullion-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bullion API's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gold
- Prices
- Finance
- Data
---
