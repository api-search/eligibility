---
api_specs:
- filename: horsetruth-horses-api-openapi.yml
  format: yaml
  label: Horse Truth Horses API
  slug: horsetruth-horses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/horsetruth/openapi/horsetruth-horses-api-openapi.yml
- filename: horsetruth-identity-api-openapi.yml
  format: yaml
  label: Horse Truth Identity API
  slug: horsetruth-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/horsetruth/openapi/horsetruth-identity-api-openapi.yml
- filename: horsetruth-machine-api-openapi.yml
  format: yaml
  label: Horse Truth Machine API
  slug: horsetruth-machine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/horsetruth/openapi/horsetruth-machine-api-openapi.yml
- filename: horsetruth-mcp-api-openapi.yml
  format: yaml
  label: Horse Truth MCP API
  slug: horsetruth-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/horsetruth/openapi/horsetruth-mcp-api-openapi.yml
- filename: horsetruth-sandbox-api-openapi.yml
  format: yaml
  label: Horse Truth Sandbox API
  slug: horsetruth-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/horsetruth/openapi/horsetruth-sandbox-api-openapi.yml
- filename: horsetruth-x402-api-openapi.yml
  format: yaml
  label: Horse Truth X402 API
  slug: horsetruth-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/horsetruth/openapi/horsetruth-x402-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: For people aged 18 and over.
    value: '18'
  restricted_uses:
  - summary: Not betting advice
    text: Not betting advice.
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
name: Horse Truth
provenance_date: '2026-11-09'
provider_name: Horse Truth
provider_slug: horsetruth
slug: horsetruth-eligibility
source_date: '2026-11-09'
source_filename: horsetruth-eligibility.yml
source_heading: Eligibility
source_page: https://horsetruth.com.au/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Horse Truth\naid: horsetruth\nurl: https://horsetruth.com.au/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not betting advice\n  text: Not betting advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: For people aged 18 and over.\n"
source_yaml_url: https://artifacts.apis.io/horsetruth/eligibility/horsetruth-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Horse Truth's own page on 2026-11-09.
synthetic: false
tags:
- Racehorse Intelligence
- Horse Reports
- Developers
- Trainers
---
