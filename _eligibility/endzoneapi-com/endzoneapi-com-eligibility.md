---
api_specs:
- filename: endzoneapi-com-basic-lookup-api-openapi.yml
  format: yaml
  label: endzoneapi-com Basic lookup API
  slug: endzoneapi-com-basic-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endzoneapi-com/openapi/endzoneapi-com-basic-lookup-api-openapi.yml
- filename: endzoneapi-com-multi-table-api-openapi.yml
  format: yaml
  label: endzoneapi-com Multi Table API
  slug: endzoneapi-com-multi-table-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endzoneapi-com/openapi/endzoneapi-com-multi-table-api-openapi.yml
- filename: endzoneapi-com-static-reference-api-openapi.yml
  format: yaml
  label: endzoneapi-com Static reference API
  slug: endzoneapi-com-static-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endzoneapi-com/openapi/endzoneapi-com-static-reference-api-openapi.yml
- filename: endzoneapi-com-stats-aggregation-api-openapi.yml
  format: yaml
  label: endzoneapi-com Stats + aggregation API
  slug: endzoneapi-com-stats-aggregation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endzoneapi-com/openapi/endzoneapi-com-stats-aggregation-api-openapi.yml
- filename: endzoneapi-com-time-series-api-openapi.yml
  format: yaml
  label: endzoneapi-com Time Series API
  slug: endzoneapi-com-time-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endzoneapi-com/openapi/endzoneapi-com-time-series-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if the law bars you, including U.S. sanctions or export rules.
  entity_types:
  - text: You must be at least 18 years old, and old enough to make a binding contract where you live.
    type: individual
  - text: If you use the Service for a company, you confirm you can bind that company, and "you" means the company.
    type: business
  minimum_age:
    text: You must be at least 18 years old, and old enough to make a binding contract where you live.
    value: '18'
  restricted_uses:
  - summary: Betting on individual college athletes
    text: Some states prohibit betting on an individual college athlete's performance; following the rules where you are is your responsibility.
  - summary: Marketing gambling to minors or where illegal
    text: use the Service to market gambling to anyone under the legal age, or anywhere it is not allowed.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We verify your email before we issue a key.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: endzoneapi-com
provenance_date: '2026-11-09'
provider_name: endzoneapi-com
provider_slug: endzoneapi-com
slug: endzoneapi-com-eligibility
source_date: '2026-11-09'
source_filename: endzoneapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://endzoneapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: endzoneapi-com\naid: endzoneapi-com\nurl: https://endzoneapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if the law bars you, including U.S. sanctions or export rules.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, and old enough to make a binding contract where you live.\n- type: business\n  text: If you use the Service for a company, you confirm you can bind that company, and \"you\" means the company.\nrestricted_uses:\n- summary: Betting on individual college athletes\n  text: Some states prohibit betting\
  \ on an individual college athlete's performance; following the rules where you\n    are is your responsibility.\n- summary: Marketing gambling to minors or where illegal\n  text: use the Service to market gambling to anyone under the legal age, or anywhere it is not allowed.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We verify your email before we issue a key.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, and old enough to make a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/endzoneapi-com/eligibility/endzoneapi-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from endzoneapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Sports
- Football
- NFL
- Data API
- Odds
- MCP
---
