---
api_specs:
- filename: allium-explorer-api-openapi.yml
  format: yaml
  label: Allium Explorer API
  slug: allium-explorer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allium/openapi/allium-explorer-api-openapi.yml
- filename: allium-ping-api-openapi.yml
  format: yaml
  label: Allium Ping API
  slug: allium-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allium/openapi/allium-ping-api-openapi.yml
- filename: allium-polygon-api-openapi.yml
  format: yaml
  label: Allium Polygon API
  slug: allium-polygon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allium/openapi/allium-polygon-api-openapi.yml
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
  - summary: Personal data
    text: Customer represents and warrants that it will not provide access, transfer, or otherwise make available to Allium any personally identifiable information or personal data subject to applicable law or regulation
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
name: Allium
provenance_date: '2026-11-09'
provider_name: Allium
provider_slug: allium
slug: allium-eligibility
source_date: '2026-11-09'
source_filename: allium-eligibility.yml
source_heading: Eligibility
source_page: https://www.allium.so/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Allium\naid: allium\nurl: https://www.allium.so/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal data\n  text: Customer represents and warrants that it will not provide access, transfer, or otherwise make available\n    to Allium any personally identifiable information or personal data subject to applicable law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/allium/eligibility/allium-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Allium's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Analytics
- Blockchain
- Cryptocurrency
- Web3
- Data Infrastructure
- Real-Time Data
- Stablecoins
- DeFi
- Machine Payments
---
