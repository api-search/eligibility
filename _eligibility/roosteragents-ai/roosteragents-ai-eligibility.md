---
api_specs:
- filename: roosteragents-ai-agent-readiness-api-openapi.yml
  format: yaml
  label: roosteragents-ai Agent Readiness API
  slug: roosteragents-ai-agent-readiness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roosteragents-ai/openapi/roosteragents-ai-agent-readiness-api-openapi.yml
- filename: roosteragents-ai-gateway-api-openapi.yml
  format: yaml
  label: roosteragents-ai Gateway API
  slug: roosteragents-ai-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roosteragents-ai/openapi/roosteragents-ai-gateway-api-openapi.yml
- filename: roosteragents-ai-mcp-api-openapi.yml
  format: yaml
  label: roosteragents-ai MCP API
  slug: roosteragents-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roosteragents-ai/openapi/roosteragents-ai-mcp-api-openapi.yml
- filename: roosteragents-ai-scan-api-openapi.yml
  format: yaml
  label: roosteragents-ai Scan API
  slug: roosteragents-ai-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roosteragents-ai/openapi/roosteragents-ai-scan-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and the authorized user of the mobile number you provide.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and the authorized user of the mobile number you provide.
    value: '18'
  restricted_uses:
  - summary: Unlawful purpose
    text: using the service for any unlawful purpose.
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
name: roosteragents-ai
provenance_date: '2026-11-10'
provider_name: roosteragents-ai
provider_slug: roosteragents-ai
slug: roosteragents-ai-eligibility
source_date: '2026-11-10'
source_filename: roosteragents-ai-eligibility.yml
source_heading: Eligibility
source_page: https://roosteragents.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: roosteragents-ai\naid: roosteragents-ai\nurl: https://roosteragents.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and the authorized user of the mobile number you provide.\nrestricted_uses:\n- summary: Unlawful purpose\n  text: using the service for any unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and the authorized user of the mobile number you provide.\n"
source_yaml_url: https://artifacts.apis.io/roosteragents-ai/eligibility/roosteragents-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from roosteragents-ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- Automation
- Software-as-a-Service
- Data
---
