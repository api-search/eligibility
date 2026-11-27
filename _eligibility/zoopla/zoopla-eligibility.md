---
api_specs:
- filename: zoopla-products-api-openapi.yml
  format: yaml
  label: Zoopla Products API
  slug: zoopla-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoopla/openapi/zoopla-products-api-openapi.yml
- filename: zoopla-rest-endpoints-api-openapi.yml
  format: yaml
  label: Zoopla REST Endpoints API
  slug: zoopla-rest-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoopla/openapi/zoopla-rest-endpoints-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are authorised to purchase services and products from Zoopla and its affiliates on behalf of the organisation you represent
    type: business
  minimum_age:
    text: null
    value: null
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
name: Zoopla
provenance_date: '2026-11-10'
provider_name: Zoopla
provider_slug: zoopla
slug: zoopla-eligibility
source_date: '2026-11-10'
source_filename: zoopla-eligibility.yml
source_heading: Eligibility
source_page: https://developers.zoopla.co.uk/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zoopla\naid: zoopla\nurl: https://developers.zoopla.co.uk/pages/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you are authorised to purchase services and products from Zoopla and its affiliates on behalf of the organisation\n    you represent\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zoopla/eligibility/zoopla-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Zoopla's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- United Kingdom
- Property Listings
- Property Portal
- PropTech
- Rentals
- Estate Agents
- Leads
- CRM Integration
---
