---
api_specs:
- filename: agent-ready-dev-mcp-api-openapi.yml
  format: yaml
  label: Agent Ready MCP API
  slug: agent-ready-dev-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-ready-dev/openapi/agent-ready-dev-mcp-api-openapi.yml
- filename: agent-ready-dev-nlweb-api-openapi.yml
  format: yaml
  label: Agent Ready NL Web API
  slug: agent-ready-dev-nlweb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-ready-dev/openapi/agent-ready-dev-nlweb-api-openapi.yml
- filename: agent-ready-dev-scans-api-openapi.yml
  format: yaml
  label: Agent Ready Scans API
  slug: agent-ready-dev-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-ready-dev/openapi/agent-ready-dev-scans-api-openapi.yml
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
  - summary: Unlawful use
    text: Use the Service to violate any law or third-party right.
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
name: Agent Ready
provenance_date: '2026-11-09'
provider_name: Agent Ready
provider_slug: agent-ready-dev
slug: agent-ready-dev-eligibility
source_date: '2026-11-09'
source_filename: agent-ready-dev-eligibility.yml
source_heading: Eligibility
source_page: https://agent-ready.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agent Ready\naid: agent-ready-dev\nurl: https://agent-ready.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: Use the Service to violate any law or third-party right.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agent-ready-dev/eligibility/agent-ready-dev-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Agent Ready's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- Agent Readiness
- Website Scanning
- Developer Tools
- MCP
- A2A
- Llms.txt
- x402
- NLWeb
- Accessibility
- Agent-Native
- Australia
---
