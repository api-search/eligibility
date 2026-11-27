---
api_specs:
- filename: mcpnest-openapi-generated.yml
  format: yaml
  label: MCPNest API
  slug: mcpnest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mcpnest/openapi/_ae-authored/mcpnest-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old to create an account.
    value: '16'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To publish MCP servers or access premium features, you must create an account via GitHub OAuth.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MCPNest
provenance_date: '2026-11-10'
provider_name: MCPNest
provider_slug: mcpnest
slug: mcpnest-eligibility
source_date: '2026-11-10'
source_filename: mcpnest-eligibility.yml
source_heading: Eligibility
source_page: https://mcpnest.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MCPNest\naid: mcpnest\nurl: https://mcpnest.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To publish MCP servers or access premium features, you must create an account via GitHub OAuth.\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/mcpnest/eligibility/mcpnest-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from MCPNest's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Cloud
- DevOps
- Artificial Intelligence
---
