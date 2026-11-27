---
api_specs:
- filename: puckapi-com-basic-lookup-api-openapi.yml
  format: yaml
  label: puckapi-com Basic lookup API
  slug: puckapi-com-basic-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puckapi-com/openapi/puckapi-com-basic-lookup-api-openapi.yml
- filename: puckapi-com-model-projections-api-openapi.yml
  format: yaml
  label: puckapi-com Model projections API
  slug: puckapi-com-model-projections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puckapi-com/openapi/puckapi-com-model-projections-api-openapi.yml
- filename: puckapi-com-multi-table-api-openapi.yml
  format: yaml
  label: puckapi-com Multi Table API
  slug: puckapi-com-multi-table-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puckapi-com/openapi/puckapi-com-multi-table-api-openapi.yml
- filename: puckapi-com-static-reference-api-openapi.yml
  format: yaml
  label: puckapi-com Static reference API
  slug: puckapi-com-static-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puckapi-com/openapi/puckapi-com-static-reference-api-openapi.yml
- filename: puckapi-com-stats-aggregation-api-openapi.yml
  format: yaml
  label: puckapi-com Stats + aggregation API
  slug: puckapi-com-stats-aggregation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puckapi-com/openapi/puckapi-com-stats-aggregation-api-openapi.yml
- filename: puckapi-com-time-series-api-openapi.yml
  format: yaml
  label: puckapi-com Time Series API
  slug: puckapi-com-time-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puckapi-com/openapi/puckapi-com-time-series-api-openapi.yml
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
  - summary: Gambling to under-age or prohibited areas
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
name: puckapi-com
provenance_date: '2026-11-10'
provider_name: puckapi-com
provider_slug: puckapi-com
slug: puckapi-com-eligibility
source_date: '2026-11-10'
source_filename: puckapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://puckapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: puckapi-com\naid: puckapi-com\nurl: https://puckapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for a company, you confirm you can bind that company, and \"you\" means the company.\nrestricted_uses:\n- summary: Gambling to under-age or prohibited areas\n  text: use the Service to market gambling to anyone under the legal age, or anywhere it is not allowed.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We verify your email before we issue a key.\nminimum_age:\n  value:\
  \ '18'\n  text: You must be at least 18 years old, and old enough to make a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/puckapi-com/eligibility/puckapi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from puckapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Sports
- Hockey
- Data
- Statistics
---
