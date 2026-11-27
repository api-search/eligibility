---
api_specs:
- filename: mcpbundles-local-runtime-api-openapi.yml
  format: yaml
  label: MCPBundles Local Runtime API
  slug: mcpbundles-local-runtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mcpbundles/openapi/mcpbundles-local-runtime-api-openapi.yml
- filename: mcpbundles-tunnel-api-openapi.yml
  format: yaml
  label: MCPBundles Tunnel API
  slug: mcpbundles-tunnel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mcpbundles/openapi/mcpbundles-tunnel-api-openapi.yml
- filename: mcpbundles-graph-ql-api-openapi.yml
  format: yaml
  label: MCPBundles Graph QL API
  slug: mcpbundles-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mcpbundles/openapi/mcpbundles-graph-ql-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: designed for legitimate use by individuals and organizations
    type: individual
  - text: designed for legitimate use by individuals and organizations
    type: business
  minimum_age:
    text: Children under the age of 13 are prohibited from using MCP Bundles services.
    value: '13'
  restricted_uses:
  - summary: Children under 13 prohibited
    text: Children under the age of 13 are prohibited from using MCP Bundles services.
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
name: MCPBundles
provenance_date: '2026-11-10'
provider_name: MCPBundles
provider_slug: mcpbundles
slug: mcpbundles-eligibility
source_date: '2026-11-10'
source_filename: mcpbundles-eligibility.yml
source_heading: Eligibility
source_page: https://www.mcpbundles.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MCPBundles\naid: mcpbundles\nurl: https://www.mcpbundles.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: designed for legitimate use by individuals and organizations\n- type: business\n  text: designed for legitimate use by individuals and organizations\nrestricted_uses:\n- summary: Children under 13 prohibited\n  text: Children under the age of 13 are prohibited from using MCP Bundles services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Children\
  \ under the age of 13 are prohibited from using MCP Bundles services.\n"
source_yaml_url: https://artifacts.apis.io/mcpbundles/eligibility/mcpbundles-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from MCPBundles's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Directory
- ManagedCloudPlatforms
- Tools
- Integration
---
