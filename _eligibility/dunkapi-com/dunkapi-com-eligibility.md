---
api_specs:
- filename: dunkapi-com-basic-lookup-api-openapi.yml
  format: yaml
  label: dunkapi-com Basic lookup API
  slug: dunkapi-com-basic-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dunkapi-com/openapi/dunkapi-com-basic-lookup-api-openapi.yml
- filename: dunkapi-com-multi-table-api-openapi.yml
  format: yaml
  label: dunkapi-com Multi Table API
  slug: dunkapi-com-multi-table-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dunkapi-com/openapi/dunkapi-com-multi-table-api-openapi.yml
- filename: dunkapi-com-static-reference-api-openapi.yml
  format: yaml
  label: dunkapi-com Static reference API
  slug: dunkapi-com-static-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dunkapi-com/openapi/dunkapi-com-static-reference-api-openapi.yml
- filename: dunkapi-com-stats-aggregation-api-openapi.yml
  format: yaml
  label: dunkapi-com Stats + aggregation API
  slug: dunkapi-com-stats-aggregation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dunkapi-com/openapi/dunkapi-com-stats-aggregation-api-openapi.yml
- filename: dunkapi-com-time-series-api-openapi.yml
  format: yaml
  label: dunkapi-com Time Series API
  slug: dunkapi-com-time-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dunkapi-com/openapi/dunkapi-com-time-series-api-openapi.yml
claim_count: 5
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
  - summary: Gambling-related restrictions
    text: use the Service to market gambling to anyone under the legal age, or anywhere it is not allowed.
  - summary: College athlete betting
    text: Some states prohibit betting on an individual college athlete's performance; following the rules where you are is your responsibility.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: We verify your email before we issue a key.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: dunkapi-com
provenance_date: '2026-11-09'
provider_name: dunkapi-com
provider_slug: dunkapi-com
slug: dunkapi-com-eligibility
source_date: '2026-11-09'
source_filename: dunkapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://dunkapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: dunkapi-com\naid: dunkapi-com\nurl: https://dunkapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for a company, you confirm you can bind that company, and \"you\" means the company.\nrestricted_uses:\n- summary: Gambling-related restrictions\n  text: use the Service to market gambling to anyone under the legal age, or anywhere it is not allowed.\n- summary: College athlete betting\n  text: Some states prohibit betting on an individual college athlete's performance; following the rules where you\n \
  \   are is your responsibility.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: We verify your email before we issue a key.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, and old enough to make a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/dunkapi-com/eligibility/dunkapi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from dunkapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sports
- Basketball
- NBA
- Data
---
