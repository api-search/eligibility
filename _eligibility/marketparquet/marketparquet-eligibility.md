---
api_specs:
- filename: marketparquet-api-v1-api-openapi.yml
  format: yaml
  label: MarketParquet API V1 API
  slug: marketparquet-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketparquet/openapi/marketparquet-api-v1-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per person or organization.
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a working email address -- it is how purchases are delivered and billing problems are resolved.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MarketParquet
provenance_date: '2026-11-10'
provider_name: MarketParquet
provider_slug: marketparquet
slug: marketparquet-eligibility
source_date: '2026-11-10'
source_filename: marketparquet-eligibility.yml
source_heading: Eligibility
source_page: https://marketparquet.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MarketParquet\naid: marketparquet\nurl: https://marketparquet.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account per person or organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a working email address -- it is how purchases are delivered and billing problems are resolved.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/marketparquet/eligibility/marketparquet-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from MarketParquet's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Data
- Market Data
---
