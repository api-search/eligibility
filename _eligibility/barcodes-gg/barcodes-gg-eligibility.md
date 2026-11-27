---
api_specs:
- filename: barcodes-gg-account-api-openapi.yml
  format: yaml
  label: Barcodes.GG Account API
  slug: barcodes-gg-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barcodes-gg/openapi/barcodes-gg-account-api-openapi.yml
- filename: barcodes-gg-barcodes-api-openapi.yml
  format: yaml
  label: Barcodes.GG Barcodes API
  slug: barcodes-gg-barcodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barcodes-gg/openapi/barcodes-gg-barcodes-api-openapi.yml
- filename: barcodes-gg-images-api-openapi.yml
  format: yaml
  label: Barcodes.GG Images API
  slug: barcodes-gg-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barcodes-gg/openapi/barcodes-gg-images-api-openapi.yml
- filename: barcodes-gg-legacy-v1-api-openapi.yml
  format: yaml
  label: Barcodes.GG Legacy v1 API
  slug: barcodes-gg-legacy-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barcodes-gg/openapi/barcodes-gg-legacy-v1-api-openapi.yml
- filename: barcodes-gg-products-api-openapi.yml
  format: yaml
  label: Barcodes.GG Products API
  slug: barcodes-gg-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barcodes-gg/openapi/barcodes-gg-products-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity ("you")
    type: individual
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Competing barcode database or service
    text: You do not use our data to build or improve a barcode or product database, API or service that competes with our Services.
  - summary: Presenting data as your own
    text: You do not present our data as your own data.
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
name: Barcodes.GG
provenance_date: '2026-11-09'
provider_name: Barcodes.GG
provider_slug: barcodes-gg
slug: barcodes-gg-eligibility
source_date: '2026-11-09'
source_filename: barcodes-gg-eligibility.yml
source_heading: Eligibility
source_page: https://barcodes.gg/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Barcodes.GG\naid: barcodes-gg\nurl: https://barcodes.gg/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity (\"you\")\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Competing barcode database or service\n  text:\
  \ You do not use our data to build or improve a barcode or product database, API or service that competes\n    with our Services.\n- summary: Presenting data as your own\n  text: You do not present our data as your own data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are intended for users who are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/barcodes-gg/eligibility/barcodes-gg-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Barcodes.GG's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Barcodes
- Sneaker
- Streetwear
---
