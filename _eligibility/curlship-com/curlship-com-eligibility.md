---
api_specs:
- filename: curlship-com-badge-api-openapi.yml
  format: yaml
  label: CurlShip Badge API
  slug: curlship-com-badge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curlship-com/openapi/curlship-com-badge-api-openapi.yml
- filename: curlship-com-billing-api-openapi.yml
  format: yaml
  label: CurlShip Billing API
  slug: curlship-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curlship-com/openapi/curlship-com-billing-api-openapi.yml
- filename: curlship-com-edits-api-openapi.yml
  format: yaml
  label: CurlShip Edits API
  slug: curlship-com-edits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curlship-com/openapi/curlship-com-edits-api-openapi.yml
- filename: curlship-com-listings-api-openapi.yml
  format: yaml
  label: CurlShip Listings API
  slug: curlship-com-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curlship-com/openapi/curlship-com-listings-api-openapi.yml
- filename: curlship-com-stats-api-openapi.yml
  format: yaml
  label: CurlShip Stats API
  slug: curlship-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curlship-com/openapi/curlship-com-stats-api-openapi.yml
- filename: curlship-com-x402-api-openapi.yml
  format: yaml
  label: CurlShip X402 API
  slug: curlship-com-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curlship-com/openapi/curlship-com-x402-api-openapi.yml
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
  - summary: Adult content disclosure
    text: Say that it is for adults in your own page description.
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
name: CurlShip
provenance_date: '2026-11-09'
provider_name: CurlShip
provider_slug: curlship-com
slug: curlship-com-eligibility
source_date: '2026-11-09'
source_filename: curlship-com-eligibility.yml
source_heading: Eligibility
source_page: https://curlship.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CurlShip\naid: curlship-com\nurl: https://curlship.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Adult content disclosure\n  text: Say that it is for adults in your own page description.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/curlship-com/eligibility/curlship-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from CurlShip's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Directory
- Product Listings
- Developer Tools
- MCP
- AI Agents
- REST API
- Launch Platform
---
