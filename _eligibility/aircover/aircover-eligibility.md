---
api_specs:
- filename: aircover-discovery-api-openapi.yml
  format: yaml
  label: Aircover Discovery API
  slug: aircover-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aircover/openapi/aircover-discovery-api-openapi.yml
- filename: aircover-mcp-api-openapi.yml
  format: yaml
  label: Aircover MCP API
  slug: aircover-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aircover/openapi/aircover-mcp-api-openapi.yml
- filename: aircover-oauth-api-openapi.yml
  format: yaml
  label: Aircover OAuth API
  slug: aircover-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aircover/openapi/aircover-oauth-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you're signing as an employee, contractor, or agent of an entity, you must be authorized to bind that entity and represent you have such authority.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: Customer may not provide to any person or export or re-export Services or related software in violation of restrictions, laws, or regulations of the United States Department of Commerce, the United States Department of Treasury Office of Foreign Assets Control
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
name: Aircover
provenance_date: '2026-11-09'
provider_name: Aircover
provider_slug: aircover
slug: aircover-eligibility
source_date: '2026-11-09'
source_filename: aircover-eligibility.yml
source_heading: Eligibility
source_page: https://www.aircover.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aircover\naid: aircover\nurl: https://www.aircover.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you're signing as an employee, contractor, or agent of an entity, you must be authorized to bind that\n    entity and represent you have such authority.\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: Customer may not provide to any person or export or re-export Services or related software in violation\n    of restrictions, laws, or regulations of the United States Department of Commerce,\
  \ the United States Department\n    of Treasury Office of Foreign Assets Control\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aircover/eligibility/aircover-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Aircover's own page on 2026-11-09.
synthetic: false
tags:
- Sales Enablement
- Conversation Intelligence
- Sales Coaching
- Revenue Intelligence
- AI Agents
- MCP
- Agent-Native
- CRM
- Meetings
- Transcription
- OAuth
- Authentication
---
