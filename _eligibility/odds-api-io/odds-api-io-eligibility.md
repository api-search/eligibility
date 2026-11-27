---
api_specs:
- filename: odds-api-io-arbitrage-bets-api-openapi.yml
  format: yaml
  label: Odds-API.io Arbitrage Bets API
  slug: odds-api-io-arbitrage-bets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-arbitrage-bets-api-openapi.yml
- filename: odds-api-io-bookmakers-api-openapi.yml
  format: yaml
  label: Odds-API.io Bookmakers API
  slug: odds-api-io-bookmakers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-bookmakers-api-openapi.yml
- filename: odds-api-io-dropping-odds-api-openapi.yml
  format: yaml
  label: Odds-API.io Dropping Odds API
  slug: odds-api-io-dropping-odds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-dropping-odds-api-openapi.yml
- filename: odds-api-io-events-api-openapi.yml
  format: yaml
  label: Odds-API.io Events API
  slug: odds-api-io-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-events-api-openapi.yml
- filename: odds-api-io-historical-api-openapi.yml
  format: yaml
  label: Odds-API.io Historical API
  slug: odds-api-io-historical-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-historical-api-openapi.yml
- filename: odds-api-io-leagues-api-openapi.yml
  format: yaml
  label: Odds-API.io Leagues API
  slug: odds-api-io-leagues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-leagues-api-openapi.yml
- filename: odds-api-io-mappings-api-openapi.yml
  format: yaml
  label: Odds-API.io Mappings API
  slug: odds-api-io-mappings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-mappings-api-openapi.yml
- filename: odds-api-io-markets-api-openapi.yml
  format: yaml
  label: Odds-API.io Markets API
  slug: odds-api-io-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-markets-api-openapi.yml
- filename: odds-api-io-odds-api-openapi.yml
  format: yaml
  label: Odds-API.io Odds API
  slug: odds-api-io-odds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-odds-api-openapi.yml
- filename: odds-api-io-outrights-api-openapi.yml
  format: yaml
  label: Odds-API.io Outrights API
  slug: odds-api-io-outrights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-outrights-api-openapi.yml
- filename: odds-api-io-participants-api-openapi.yml
  format: yaml
  label: Odds-API.io Participants API
  slug: odds-api-io-participants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-participants-api-openapi.yml
- filename: odds-api-io-settlement-api-openapi.yml
  format: yaml
  label: Odds-API.io Settlement API
  slug: odds-api-io-settlement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-settlement-api-openapi.yml
- filename: odds-api-io-sports-api-openapi.yml
  format: yaml
  label: Odds-API.io Sports API
  slug: odds-api-io-sports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-sports-api-openapi.yml
- filename: odds-api-io-value-bets-api-openapi.yml
  format: yaml
  label: Odds-API.io Value Bets API
  slug: odds-api-io-value-bets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odds-api-io/openapi/odds-api-io-value-bets-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms apply to all users of the Service, whether acting as an individual ("Consumer")
    type: individual
  - text: or on behalf of a company or other legal entity ("Business User")
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: You may not use the data for any unlawful or fraudulent purpose
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
name: Odds-API.io
provenance_date: '2026-11-10'
provider_name: Odds-API.io
provider_slug: odds-api-io
slug: odds-api-io-eligibility
source_date: '2026-11-10'
source_filename: odds-api-io-eligibility.yml
source_heading: Eligibility
source_page: https://odds-api.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Odds-API.io\naid: odds-api-io\nurl: https://odds-api.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These Terms apply to all users of the Service, whether acting as an individual (\"Consumer\")\n- type: business\n  text: or on behalf of a company or other legal entity (\"Business User\")\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: You may not use the data for any unlawful or fraudulent purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You must be at least 18 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/odds-api-io/eligibility/odds-api-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Odds-API.io's own page on 2026-11-10.
synthetic: false
tags:
- Sports
- Odds
- Betting
- Real-Time
- Data
---
