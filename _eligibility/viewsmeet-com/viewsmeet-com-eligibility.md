---
api_specs:
- filename: viewsmeet-com-agent-api-openapi.yml
  format: yaml
  label: ViewsMeet Agent API
  slug: viewsmeet-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-agent-api-openapi.yml
- filename: viewsmeet-com-agents-api-openapi.yml
  format: yaml
  label: ViewsMeet Agents API
  slug: viewsmeet-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-agents-api-openapi.yml
- filename: viewsmeet-com-assessments-api-openapi.yml
  format: yaml
  label: ViewsMeet Assessments API
  slug: viewsmeet-com-assessments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-assessments-api-openapi.yml
- filename: viewsmeet-com-connections-api-openapi.yml
  format: yaml
  label: ViewsMeet Connections API
  slug: viewsmeet-com-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-connections-api-openapi.yml
- filename: viewsmeet-com-experiments-api-openapi.yml
  format: yaml
  label: ViewsMeet Experiments API
  slug: viewsmeet-com-experiments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-experiments-api-openapi.yml
- filename: viewsmeet-com-mcp-api-openapi.yml
  format: yaml
  label: ViewsMeet MCP API
  slug: viewsmeet-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-mcp-api-openapi.yml
- filename: viewsmeet-com-personality-api-openapi.yml
  format: yaml
  label: ViewsMeet Personality API
  slug: viewsmeet-com-personality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-personality-api-openapi.yml
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
  - summary: Unlawful, harmful, or sensitive content
    text: Attempts to inject or distribute unlawful, harmful, or sensitive content are outside authorized use.
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
name: ViewsMeet
provenance_date: '2026-11-10'
provider_name: ViewsMeet
provider_slug: viewsmeet-com
slug: viewsmeet-com-eligibility
source_date: '2026-11-10'
source_filename: viewsmeet-com-eligibility.yml
source_heading: Eligibility
source_page: https://viewsmeet.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ViewsMeet\naid: viewsmeet-com\nurl: https://viewsmeet.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, harmful, or sensitive content\n  text: Attempts to inject or distribute unlawful, harmful, or sensitive content are outside authorized use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/viewsmeet-com/eligibility/viewsmeet-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from ViewsMeet's own page on 2026-11-10.
synthetic: false
tags:
- Social
- Games
- Personality Assessment
- Surveys & Polls
- Agent-Native
- MCP
- A2A
- Research
- Psychology
- Consumer
- Cloudflare Workers
---
