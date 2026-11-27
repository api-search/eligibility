---
api_specs:
- filename: hasmcp-providers-api-openapi.yml
  format: yaml
  label: HasMCP Providers API
  slug: hasmcp-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasmcp/openapi/hasmcp-providers-api-openapi.yml
- filename: hasmcp-servers-api-openapi.yml
  format: yaml
  label: HasMCP Servers API
  slug: hasmcp-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasmcp/openapi/hasmcp-servers-api-openapi.yml
- filename: hasmcp-variables-api-openapi.yml
  format: yaml
  label: HasMCP Variables API
  slug: hasmcp-variables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasmcp/openapi/hasmcp-variables-api-openapi.yml
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
  - summary: Unlawful endpoint access
    text: Facilitate access to endpoints that violate local or international laws.
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
name: HasMCP
provenance_date: '2026-11-09'
provider_name: HasMCP
provider_slug: hasmcp
slug: hasmcp-eligibility
source_date: '2026-11-09'
source_filename: hasmcp-eligibility.yml
source_heading: Eligibility
source_page: https://hasmcp.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HasMCP\naid: hasmcp\nurl: https://hasmcp.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful endpoint access\n  text: Facilitate access to endpoints that violate local or international laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hasmcp/eligibility/hasmcp-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from HasMCP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- No-Code
- Low-Code
- MCP
- API Gateway
---
