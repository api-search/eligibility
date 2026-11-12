---
api_specs:
- filename: corvio-ai-agent-collaboration-api-openapi.yml
  format: yaml
  label: Corvio Agent collaboration API
  slug: corvio-ai-agent-collaboration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-agent-collaboration-api-openapi.yml
- filename: corvio-ai-public-api-v1-api-openapi.yml
  format: yaml
  label: Corvio Public API v1 API
  slug: corvio-ai-public-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-public-api-v1-api-openapi.yml
- filename: corvio-ai-public-api-v1-files-api-openapi.yml
  format: yaml
  label: Corvio Public API v1 - Files API
  slug: corvio-ai-public-api-v1-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-public-api-v1-files-api-openapi.yml
- filename: corvio-ai-public-api-v1-local-markdown-sync-api-openapi.yml
  format: yaml
  label: Corvio Public API v1 - Local Markdown Sync API
  slug: corvio-ai-public-api-v1-local-markdown-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-public-api-v1-local-markdown-sync-api-openapi.yml
- filename: corvio-ai-public-api-v1-source-publication-api-openapi.yml
  format: yaml
  label: Corvio Public API v1 - Source publication API
  slug: corvio-ai-public-api-v1-source-publication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-public-api-v1-source-publication-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent and warrant that you are at least eighteen (18) years of age and have legal capacity to enter into binding contracts
    type: individual
  - text: if you are using the Service on behalf of an entity, that you have authority to bind that entity
    type: business
  minimum_age:
    text: you represent and warrant that you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: use the Service for high-risk activities where failure could lead to death, personal injury, or significant property or environmental damage
  - summary: Regulated professional advice
    text: the Service is not intended to provide legal, medical, financial, accounting, investment, or other regulated professional advice
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
name: Corvio
provenance_date: '2026-11-09'
provider_name: Corvio
provider_slug: corvio-ai
slug: corvio-ai-eligibility
source_date: '2026-11-09'
source_filename: corvio-ai-eligibility.yml
source_heading: Eligibility
source_page: https://corvio.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corvio\naid: corvio-ai\nurl: https://corvio.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent and warrant that you are at least eighteen (18) years of age and have legal capacity to enter\n    into binding contracts\n- type: business\n  text: if you are using the Service on behalf of an entity, that you have authority to bind that entity\nrestricted_uses:\n- summary: High-risk activities\n  text: use the Service for high-risk activities where failure could lead to death, personal injury, or significant\n    property\
  \ or environmental damage\n- summary: Regulated professional advice\n  text: the Service is not intended to provide legal, medical, financial, accounting, investment, or other regulated\n    professional advice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/corvio-ai/eligibility/corvio-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Corvio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Notes
- Knowledge Management
- Workspace
- AI Agents
- MCP
- Developer API
- CLI
---
