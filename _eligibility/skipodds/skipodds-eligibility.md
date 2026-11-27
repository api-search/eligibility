---
api_specs:
- filename: skipodds-alerts-api-openapi.yml
  format: yaml
  label: SkipOdds Alerts API
  slug: skipodds-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skipodds/openapi/skipodds-alerts-api-openapi.yml
- filename: skipodds-fixtures-api-openapi.yml
  format: yaml
  label: SkipOdds Fixtures API
  slug: skipodds-fixtures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skipodds/openapi/skipodds-fixtures-api-openapi.yml
- filename: skipodds-golf-api-openapi.yml
  format: yaml
  label: SkipOdds Golf API
  slug: skipodds-golf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skipodds/openapi/skipodds-golf-api-openapi.yml
- filename: skipodds-outrights-api-openapi.yml
  format: yaml
  label: SkipOdds Outrights API
  slug: skipodds-outrights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skipodds/openapi/skipodds-outrights-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Don't use SkipOdds where prohibited by local law.
  minimum_age:
    text: 18+.
    value: '18'
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
name: SkipOdds
provenance_date: '2026-11-10'
provider_name: SkipOdds
provider_slug: skipodds
slug: skipodds-eligibility
source_date: '2026-11-10'
source_filename: skipodds-eligibility.yml
source_heading: Eligibility
source_page: https://skipodds.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SkipOdds\naid: skipodds\nurl: https://skipodds.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Don't use SkipOdds where prohibited by local law.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 18+.\n"
source_yaml_url: https://artifacts.apis.io/skipodds/eligibility/skipodds-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from SkipOdds's own page on 2026-11-10.
synthetic: false
tags:
- Sports
- Odds
- Probabilities
- Betting Data
- de-vig
- Sports Data
- Real-Time
- Webhook
- Sports Betting
- MCP
- Market Data
---
