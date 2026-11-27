---
api_specs:
- filename: sprift-home-api-openapi.yml
  format: yaml
  label: Sprift Home API
  slug: sprift-home-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sprift/openapi/sprift-home-api-openapi.yml
- filename: sprift-insider-api-openapi.yml
  format: yaml
  label: Sprift Insider API
  slug: sprift-insider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sprift/openapi/sprift-insider-api-openapi.yml
- filename: sprift-property-api-openapi.yml
  format: yaml
  label: Sprift Property API
  slug: sprift-property-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sprift/openapi/sprift-property-api-openapi.yml
- filename: sprift-property-v2-api-openapi.yml
  format: yaml
  label: Sprift Property V2 API
  slug: sprift-property-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sprift/openapi/sprift-property-v2-api-openapi.yml
- filename: sprift-search-api-openapi.yml
  format: yaml
  label: Sprift Search API
  slug: sprift-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sprift/openapi/sprift-search-api-openapi.yml
- filename: sprift-share-api-openapi.yml
  format: yaml
  label: Sprift Share API
  slug: sprift-share-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sprift/openapi/sprift-share-api-openapi.yml
- filename: sprift-user-api-openapi.yml
  format: yaml
  label: Sprift User API
  slug: sprift-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sprift/openapi/sprift-user-api-openapi.yml
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
  - summary: Investment advice or guaranteed outcomes
    text: (b) use the AI Outputs to provide investment advice or guarantee outcomes;
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
name: Sprift
provenance_date: '2026-11-10'
provider_name: Sprift
provider_slug: sprift
slug: sprift-eligibility
source_date: '2026-11-10'
source_filename: sprift-eligibility.yml
source_heading: Eligibility
source_page: https://sprift.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sprift\naid: sprift\nurl: https://sprift.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Investment advice or guaranteed outcomes\n  text: (b) use the AI Outputs to provide investment advice or guarantee outcomes;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sprift/eligibility/sprift-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Sprift's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- United Kingdom
- PropTech
- Property Data
- Property Listings
- Valuation
- AVM
- Land Registry
- Conveyancing
- Rentals
- Mortgage
---
