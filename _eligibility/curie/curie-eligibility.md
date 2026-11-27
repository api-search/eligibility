---
api_specs:
- filename: curie-catalog-api-openapi.yml
  format: yaml
  label: Curie Catalog API
  slug: curie-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curie/openapi/curie-catalog-api-openapi.yml
- filename: curie-products-api-openapi.yml
  format: yaml
  label: Curie Products API
  slug: curie-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curie/openapi/curie-products-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use the App, you must have a valid Shopify store.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purpose
    text: Use the App for any unlawful purpose or in violation of any applicable laws or regulations
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
name: Curie
provenance_date: '2026-11-09'
provider_name: Curie
provider_slug: curie
slug: curie-eligibility
source_date: '2026-11-09'
source_filename: curie-eligibility.yml
source_heading: Eligibility
source_page: https://chat.curie.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curie\naid: curie\nurl: https://chat.curie.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: To use the App, you must have a valid Shopify store.\nrestricted_uses:\n- summary: Unlawful purpose\n  text: Use the App for any unlawful purpose or in violation of any applicable laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/curie/eligibility/curie-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Curie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commerce
- E-Commerce
- Shopify
- Artificial Intelligence
- MCP
- Agentic Commerce
- Product Discovery
- 3D
---
