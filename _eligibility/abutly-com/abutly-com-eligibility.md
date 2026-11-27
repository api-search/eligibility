---
api_specs:
- filename: abutly-com-dataset-api-openapi.yml
  format: yaml
  label: abutly-com Dataset API
  slug: abutly-com-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abutly-com/openapi/abutly-com-dataset-api-openapi.yml
- filename: abutly-com-mcp-api-openapi.yml
  format: yaml
  label: abutly-com MCP API
  slug: abutly-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abutly-com/openapi/abutly-com-mcp-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Nothing here applies outside England and Wales.
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
name: abutly-com
provenance_date: '2026-11-09'
provider_name: abutly-com
provider_slug: abutly-com
slug: abutly-com-eligibility
source_date: '2026-11-09'
source_filename: abutly-com-eligibility.yml
source_heading: Eligibility
source_page: https://abutly.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: abutly-com\naid: abutly-com\nurl: https://abutly.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Nothing here applies outside England and Wales.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/abutly-com/eligibility/abutly-com-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from abutly-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Legal Tech
- PartyWall
- United Kingdom
---
