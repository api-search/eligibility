---
api_specs:
- filename: reload-channels-api-openapi.yml
  format: yaml
  label: Reload Channels API
  slug: reload-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reload/openapi/reload-channels-api-openapi.yml
- filename: reload-files-api-openapi.yml
  format: yaml
  label: Reload Files API
  slug: reload-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reload/openapi/reload-files-api-openapi.yml
- filename: reload-memory-api-openapi.yml
  format: yaml
  label: Reload Memory API
  slug: reload-memory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reload/openapi/reload-memory-api-openapi.yml
- filename: reload-messages-api-openapi.yml
  format: yaml
  label: Reload Messages API
  slug: reload-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reload/openapi/reload-messages-api-openapi.yml
- filename: reload-tasks-api-openapi.yml
  format: yaml
  label: Reload Tasks API
  slug: reload-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reload/openapi/reload-tasks-api-openapi.yml
- filename: reload-workspace-api-openapi.yml
  format: yaml
  label: Reload Workspace API
  slug: reload-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reload/openapi/reload-workspace-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract to use Reload.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to use Reload.
    value: '18'
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
name: Reload
provenance_date: '2026-11-10'
provider_name: Reload
provider_slug: reload
slug: reload-eligibility
source_date: '2026-11-10'
source_filename: reload-eligibility.yml
source_heading: Eligibility
source_page: https://reload.work/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reload\naid: reload\nurl: https://reload.work/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract to use Reload.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract to use Reload.\n"
source_yaml_url: https://artifacts.apis.io/reload/eligibility/reload-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Reload's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Agents
- Agent Orchestration
- Team Chat
- Collaboration
- Memory
- Context Graph
- MCP
- Developer Tools
- Task
- Productivity
---
