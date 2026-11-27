---
api_specs:
- filename: fighterapi-com-basic-lookup-api-openapi.yml
  format: yaml
  label: fighterapi-com Basic lookup API
  slug: fighterapi-com-basic-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fighterapi-com/openapi/fighterapi-com-basic-lookup-api-openapi.yml
- filename: fighterapi-com-static-reference-api-openapi.yml
  format: yaml
  label: fighterapi-com Static reference API
  slug: fighterapi-com-static-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fighterapi-com/openapi/fighterapi-com-static-reference-api-openapi.yml
- filename: fighterapi-com-stats-aggregation-api-openapi.yml
  format: yaml
  label: fighterapi-com Stats + aggregation API
  slug: fighterapi-com-stats-aggregation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fighterapi-com/openapi/fighterapi-com-stats-aggregation-api-openapi.yml
- filename: fighterapi-com-time-series-api-openapi.yml
  format: yaml
  label: fighterapi-com Time Series API
  slug: fighterapi-com-time-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fighterapi-com/openapi/fighterapi-com-time-series-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service for a company, you confirm you can bind that company, and "you" means the company.
    type: business
  minimum_age:
    text: You must be at least 18 years old, and old enough to make a binding contract where you live.
    value: '18'
  restricted_uses:
  - summary: Gambling-related limits
    text: Some states prohibit betting on an individual college athlete's performance; following the rules where you are is your responsibility.
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
name: fighterapi-com
provenance_date: '2026-11-09'
provider_name: fighterapi-com
provider_slug: fighterapi-com
slug: fighterapi-com-eligibility
source_date: '2026-11-09'
source_filename: fighterapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://fighterapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fighterapi-com\naid: fighterapi-com\nurl: https://fighterapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for a company, you confirm you can bind that company, and \"you\" means the company.\nrestricted_uses:\n- summary: Gambling-related limits\n  text: Some states prohibit betting on an individual college athlete's performance; following the rules where you\n    are is your responsibility.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We verify your email before we issue\
  \ a key.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, and old enough to make a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/fighterapi-com/eligibility/fighterapi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from fighterapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Sports
- MMA
- Data
- Odds
---
