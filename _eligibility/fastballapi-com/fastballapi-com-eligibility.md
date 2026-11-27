---
api_specs:
- filename: fastballapi-com-basic-lookup-api-openapi.yml
  format: yaml
  label: fastballapi-com Basic lookup API
  slug: fastballapi-com-basic-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastballapi-com/openapi/fastballapi-com-basic-lookup-api-openapi.yml
- filename: fastballapi-com-multi-table-api-openapi.yml
  format: yaml
  label: fastballapi-com Multi Table API
  slug: fastballapi-com-multi-table-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastballapi-com/openapi/fastballapi-com-multi-table-api-openapi.yml
- filename: fastballapi-com-static-reference-api-openapi.yml
  format: yaml
  label: fastballapi-com Static reference API
  slug: fastballapi-com-static-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastballapi-com/openapi/fastballapi-com-static-reference-api-openapi.yml
- filename: fastballapi-com-stats-aggregation-api-openapi.yml
  format: yaml
  label: fastballapi-com Stats + aggregation API
  slug: fastballapi-com-stats-aggregation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastballapi-com/openapi/fastballapi-com-stats-aggregation-api-openapi.yml
- filename: fastballapi-com-time-series-api-openapi.yml
  format: yaml
  label: fastballapi-com Time Series API
  slug: fastballapi-com-time-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastballapi-com/openapi/fastballapi-com-time-series-api-openapi.yml
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
  - summary: Marketing gambling to minors or where banned
    text: use the Service to market gambling to anyone under the legal age, or anywhere it is not allowed
  - summary: Harassing athletes
    text: You may not use the Service to harass, threaten or target any athlete, official or other person.
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
name: fastballapi-com
provenance_date: '2026-11-09'
provider_name: fastballapi-com
provider_slug: fastballapi-com
slug: fastballapi-com-eligibility
source_date: '2026-11-09'
source_filename: fastballapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://fastballapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fastballapi-com\naid: fastballapi-com\nurl: https://fastballapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if the law bars you, including U.S. sanctions or export rules.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, and old enough to make a binding contract where you live.\n- type: business\n  text: If you use the Service for a company, you confirm you can bind that company, and \"you\" means the company.\nrestricted_uses:\n- summary: Marketing gambling to minors or where banned\n  text: use the Service to\
  \ market gambling to anyone under the legal age, or anywhere it is not allowed\n- summary: Harassing athletes\n  text: You may not use the Service to harass, threaten or target any athlete, official or other person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We verify your email before we issue a key.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, and old enough to make a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/fastballapi-com/eligibility/fastballapi-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from fastballapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Baseball
- Sports
- Data
- MLB
---
