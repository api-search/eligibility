---
api_specs:
- filename: suggix-indicators-api-openapi.yml
  format: yaml
  label: Suggix Indicators API
  slug: suggix-indicators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suggix/openapi/suggix-indicators-api-openapi.yml
- filename: suggix-industries-api-openapi.yml
  format: yaml
  label: Suggix Industries API
  slug: suggix-industries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suggix/openapi/suggix-industries-api-openapi.yml
- filename: suggix-regions-api-openapi.yml
  format: yaml
  label: Suggix Regions API
  slug: suggix-regions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suggix/openapi/suggix-regions-api-openapi.yml
- filename: suggix-search-api-openapi.yml
  format: yaml
  label: Suggix Search API
  slug: suggix-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suggix/openapi/suggix-search-api-openapi.yml
- filename: suggix-sources-api-openapi.yml
  format: yaml
  label: Suggix Sources API
  slug: suggix-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suggix/openapi/suggix-sources-api-openapi.yml
- filename: suggix-statistics-api-openapi.yml
  format: yaml
  label: Suggix Statistics API
  slug: suggix-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suggix/openapi/suggix-statistics-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: When you create an account with us, you guarantee that you are above the age of 18
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
name: Suggix
provenance_date: '2026-11-10'
provider_name: Suggix
provider_slug: suggix
slug: suggix-eligibility
source_date: '2026-11-10'
source_filename: suggix-eligibility.yml
source_heading: Eligibility
source_page: https://www.suggix.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Suggix\naid: suggix\nurl: https://www.suggix.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you create an account with us, you guarantee that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/suggix/eligibility/suggix-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Suggix's own page on 2026-11-10.
synthetic: false
tags:
- Software-as-a-Service
- Feedback
- Roadmaps
- Changelog
- Product Management
---
