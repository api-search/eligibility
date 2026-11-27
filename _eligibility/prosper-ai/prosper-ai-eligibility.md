---
api_specs:
- filename: prosper-ai-api-keys-api-openapi.yml
  format: yaml
  label: Prosper AI API Keys API
  slug: prosper-ai-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosper-ai/openapi/prosper-ai-api-keys-api-openapi.yml
- filename: prosper-ai-call-logs-api-openapi.yml
  format: yaml
  label: Prosper AI Call Logs API
  slug: prosper-ai-call-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosper-ai/openapi/prosper-ai-call-logs-api-openapi.yml
- filename: prosper-ai-campaigns-api-openapi.yml
  format: yaml
  label: Prosper AI Campaigns API
  slug: prosper-ai-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosper-ai/openapi/prosper-ai-campaigns-api-openapi.yml
- filename: prosper-ai-live-calls-api-openapi.yml
  format: yaml
  label: Prosper AI Live Calls API
  slug: prosper-ai-live-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosper-ai/openapi/prosper-ai-live-calls-api-openapi.yml
- filename: prosper-ai-status-api-openapi.yml
  format: yaml
  label: Prosper AI Status API
  slug: prosper-ai-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosper-ai/openapi/prosper-ai-status-api-openapi.yml
- filename: prosper-ai-targets-api-openapi.yml
  format: yaml
  label: Prosper AI Targets API
  slug: prosper-ai-targets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosper-ai/openapi/prosper-ai-targets-api-openapi.yml
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
  - summary: Unlawful purposes and telemarketing violations
    text: You will not use the Service for any unlawful purpose, including violating federal and state telemarketing laws
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
name: Prosper AI
provenance_date: '2026-11-10'
provider_name: Prosper AI
provider_slug: prosper-ai
slug: prosper-ai-eligibility
source_date: '2026-11-10'
source_filename: prosper-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.getprosper.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prosper AI\naid: prosper-ai\nurl: https://www.getprosper.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes and telemarketing violations\n  text: You will not use the Service for any unlawful purpose, including violating federal and state telemarketing\n    laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prosper-ai/eligibility/prosper-ai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Prosper AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Voice AI
- Revenue Cycle Management
- Patient Access
- EHR Integration
- AI Agents
- MCP
---
