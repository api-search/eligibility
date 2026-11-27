---
api_specs:
- filename: realmarketapi-market-data-api-openapi.yml
  format: yaml
  label: RealMarketAPI Market Data API
  slug: realmarketapi-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/realmarketapi/openapi/realmarketapi-market-data-api-openapi.yml
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
  restricted_uses:
  - summary: Market manipulation and unlawful surveillance
    text: Use data for prohibited activities, including market manipulation, unlawful surveillance, or reselling raw data feeds without authorisation.
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
name: RealMarketAPI
provenance_date: '2026-11-10'
provider_name: RealMarketAPI
provider_slug: realmarketapi
slug: realmarketapi-eligibility
source_date: '2026-11-10'
source_filename: realmarketapi-eligibility.yml
source_heading: Eligibility
source_page: https://realmarketapi.com/en-US/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RealMarketAPI\naid: realmarketapi\nurl: https://realmarketapi.com/en-US/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Market manipulation and unlawful surveillance\n  text: Use data for prohibited activities, including market manipulation, unlawful surveillance, or reselling raw\n    data feeds without authorisation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/realmarketapi/eligibility/realmarketapi-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from RealMarketAPI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Market Data
- Real-Time
---
