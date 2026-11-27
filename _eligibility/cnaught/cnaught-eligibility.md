---
api_specs:
- filename: cnaught-cnaught-api-api-openapi.yml
  format: yaml
  label: CNaught CNaught API
  slug: cnaught-cnaught-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnaught/openapi/cnaught-cnaught-api-api-openapi.yml
- filename: cnaught-orders-api-openapi.yml
  format: yaml
  label: CNaught Orders API
  slug: cnaught-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnaught/openapi/cnaught-orders-api-openapi.yml
- filename: cnaught-subaccounts-api-openapi.yml
  format: yaml
  label: CNaught Subaccounts API
  slug: cnaught-subaccounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnaught/openapi/cnaught-subaccounts-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, THEN YOU REPRESENT AND WARRANT THAT YOU ARE AUTHORIZED TO BIND SUCH ENTITY
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
name: CNaught
provenance_date: '2026-11-09'
provider_name: CNaught
provider_slug: cnaught
slug: cnaught-eligibility
source_date: '2026-11-09'
source_filename: cnaught-eligibility.yml
source_heading: Eligibility
source_page: https://www.cnaught.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CNaught\naid: cnaught\nurl: https://www.cnaught.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, THEN YOU REPRESENT AND WARRANT THAT YOU\n    ARE AUTHORIZED TO BIND SUCH ENTITY\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cnaught/eligibility/cnaught-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from CNaught's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Climate
- Carbon Credits
- Sustainability
---
