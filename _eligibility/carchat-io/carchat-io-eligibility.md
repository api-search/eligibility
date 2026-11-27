---
api_specs:
- filename: carchat-io-dealers-api-openapi.yml
  format: yaml
  label: CarChat Dealers API
  slug: carchat-io-dealers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carchat-io/openapi/carchat-io-dealers-api-openapi.yml
- filename: carchat-io-inventory-api-openapi.yml
  format: yaml
  label: CarChat Inventory API
  slug: carchat-io-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carchat-io/openapi/carchat-io-inventory-api-openapi.yml
- filename: carchat-io-lead-api-openapi.yml
  format: yaml
  label: CarChat Lead API
  slug: carchat-io-lead-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carchat-io/openapi/carchat-io-lead-api-openapi.yml
- filename: carchat-io-segments-api-openapi.yml
  format: yaml
  label: CarChat Segments API
  slug: carchat-io-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carchat-io/openapi/carchat-io-segments-api-openapi.yml
- filename: carchat-io-vehicles-api-openapi.yml
  format: yaml
  label: CarChat Vehicles API
  slug: carchat-io-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carchat-io/openapi/carchat-io-vehicles-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'CarChat is free for shoppers: no account, no fees, no purchases on the site.'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive use
    text: use listings for any unlawful purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'CarChat is free for shoppers: no account, no fees, no purchases on the site.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CarChat
provenance_date: '2026-11-09'
provider_name: CarChat
provider_slug: carchat-io
slug: carchat-io-eligibility
source_date: '2026-11-09'
source_filename: carchat-io-eligibility.yml
source_heading: Eligibility
source_page: https://carchat.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CarChat\naid: carchat-io\nurl: https://carchat.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'CarChat is free for shoppers: no account, no fees, no purchases on the site.'\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: use listings for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'CarChat is free for shoppers: no account, no fees, no purchases on the site.'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/carchat-io/eligibility/carchat-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from CarChat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Automotive
- Artificial Intelligence
- OpenAPI
---
