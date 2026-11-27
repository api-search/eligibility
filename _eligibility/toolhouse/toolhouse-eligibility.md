---
api_specs:
- filename: toolhouse-agent-runs-api-openapi.yml
  format: yaml
  label: Toolhouse Agent Runs API
  slug: toolhouse-agent-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-agent-runs-api-openapi.yml
- filename: toolhouse-api-keys-api-openapi.yml
  format: yaml
  label: Toolhouse API Keys API
  slug: toolhouse-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-api-keys-api-openapi.yml
- filename: toolhouse-backoffice-api-openapi.yml
  format: yaml
  label: Toolhouse Backoffice API
  slug: toolhouse-backoffice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-backoffice-api-openapi.yml
- filename: toolhouse-logs-api-openapi.yml
  format: yaml
  label: Toolhouse Logs API
  slug: toolhouse-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-logs-api-openapi.yml
- filename: toolhouse-metrics-api-openapi.yml
  format: yaml
  label: Toolhouse Metrics API
  slug: toolhouse-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-metrics-api-openapi.yml
- filename: toolhouse-sdk-api-api-openapi.yml
  format: yaml
  label: Toolhouse SDK API
  slug: toolhouse-sdk-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-sdk-api-api-openapi.yml
- filename: toolhouse-user-api-api-openapi.yml
  format: yaml
  label: Toolhouse User API
  slug: toolhouse-user-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-user-api-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old or the age of majority in your jurisdiction, whichever is greater, to use the Platform.
    type: individual
  - text: If you are using Toolhouse on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old or the age of majority in your jurisdiction, whichever is greater, to use the Platform.
    value: '18'
  restricted_uses:
  - summary: AI model training
    text: 'You are expressly prohibited from: Using the Platform, its tools, services, or infrastructure to train, fine-tune, or develop any AI Models'
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
name: Toolhouse
provenance_date: '2026-11-10'
provider_name: Toolhouse
provider_slug: toolhouse
slug: toolhouse-eligibility
source_date: '2026-11-10'
source_filename: toolhouse-eligibility.yml
source_heading: Eligibility
source_page: https://toolhouse.ai/en/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Toolhouse\naid: toolhouse\nurl: https://toolhouse.ai/en/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old or the age of majority in your jurisdiction, whichever is greater, to\n    use the Platform.\n- type: business\n  text: If you are using Toolhouse on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization to these Terms\nrestricted_uses:\n- summary: AI model training\n  text: 'You are expressly prohibited from: Using the Platform, its tools,\
  \ services, or infrastructure to train,\n    fine-tune, or develop any AI Models'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the age of majority in your jurisdiction, whichever is greater, to\n    use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/toolhouse/eligibility/toolhouse-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Toolhouse's own page on 2026-11-10.
synthetic: false
tags:
- Agent Infrastructure
- AI Agents
- AI Workers
- Backend-as-a-Service
- MCP
- MCP Discovery
- RAG
- Tools
- Workers API
---
