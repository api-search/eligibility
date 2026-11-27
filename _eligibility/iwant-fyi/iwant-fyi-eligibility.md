---
api_specs:
- filename: iwant-fyi-agents-api-openapi.yml
  format: yaml
  label: iwant.fyi Agents API
  slug: iwant-fyi-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iwant-fyi/openapi/iwant-fyi-agents-api-openapi.yml
- filename: iwant-fyi-mcp-api-openapi.yml
  format: yaml
  label: iwant.fyi MCP API
  slug: iwant-fyi-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iwant-fyi/openapi/iwant-fyi-mcp-api-openapi.yml
- filename: iwant-fyi-wants-api-openapi.yml
  format: yaml
  label: iwant.fyi Wants API
  slug: iwant-fyi-wants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iwant-fyi/openapi/iwant-fyi-wants-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to use iwant.fyi
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must sign in with a valid Google account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: iwant.fyi
provenance_date: '2026-11-09'
provider_name: iwant.fyi
provider_slug: iwant-fyi
slug: iwant-fyi-eligibility
source_date: '2026-11-09'
source_filename: iwant-fyi-eligibility.yml
source_heading: Eligibility
source_page: https://iwant.fyi/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iwant.fyi\naid: iwant-fyi\nurl: https://iwant.fyi/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must sign in with a valid Google account\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use iwant.fyi\n"
source_yaml_url: https://artifacts.apis.io/iwant-fyi/eligibility/iwant-fyi-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from iwant.fyi's own page on 2026-11-09.
synthetic: false
tags:
- Agentic Commerce
- Marketplace
- AI Agents
- Purchase Intent
- Shopping
- Automotive
- MCP
- A2A
- Open Protocol
- x402
- Agent-Native
---
