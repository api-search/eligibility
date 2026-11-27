---
api_specs:
- filename: delx-ai-a2a-api-openapi.yml
  format: yaml
  label: Delx A2a API
  slug: delx-ai-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-a2a-api-openapi.yml
- filename: delx-ai-agents-api-openapi.yml
  format: yaml
  label: Delx Agents API
  slug: delx-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-agents-api-openapi.yml
- filename: delx-ai-discovery-api-openapi.yml
  format: yaml
  label: Delx Discovery API
  slug: delx-ai-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-discovery-api-openapi.yml
- filename: delx-ai-mcp-api-openapi.yml
  format: yaml
  label: Delx MCP API
  slug: delx-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-mcp-api-openapi.yml
- filename: delx-ai-protocol-api-openapi.yml
  format: yaml
  label: Delx Protocol API
  slug: delx-ai-protocol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-protocol-api-openapi.yml
- filename: delx-ai-reliability-api-openapi.yml
  format: yaml
  label: Delx Reliability API
  slug: delx-ai-reliability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-reliability-api-openapi.yml
- filename: delx-ai-tools-api-openapi.yml
  format: yaml
  label: Delx Tools API
  slug: delx-ai-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-tools-api-openapi.yml
- filename: delx-ai-x402-api-openapi.yml
  format: yaml
  label: Delx X402 API
  slug: delx-ai-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-x402-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a human interacting directly with the Service, these Terms apply to you as well.
    type: individual
  - text: The Service is designed primarily for AI agents and their human controllers.
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal content
    text: Use the Service to store, transmit, or process illegal content
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: No account registration is required during the construction phase.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Delx
provenance_date: '2026-11-09'
provider_name: Delx
provider_slug: delx-ai
slug: delx-ai-eligibility
source_date: '2026-11-09'
source_filename: delx-ai-eligibility.yml
source_heading: Eligibility
source_page: https://ontology.delx.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Delx\naid: delx-ai\nurl: https://ontology.delx.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a human interacting directly with the Service, these Terms apply to you as well.\n- type: other\n  text: The Service is designed primarily for AI agents and their human controllers.\nrestricted_uses:\n- summary: Illegal content\n  text: Use the Service to store, transmit, or process illegal content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: No account registration is required during\
  \ the construction phase.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/delx-ai/eligibility/delx-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Delx's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- AI Agents
- MCP
- A2A
- x402
- Agentic Commerce
- Agent Continuity
- Agent Recovery
- Media Generation
- Web Intelligence
- Data Quality
- Agent-Native
---
