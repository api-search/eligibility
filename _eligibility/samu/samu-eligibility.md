---
api_specs:
- filename: samu-meetings-api-openapi.yml
  format: yaml
  label: Samu Meetings API
  slug: samu-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/samu/openapi/samu-meetings-api-openapi.yml
- filename: samu-threads-api-openapi.yml
  format: yaml
  label: Samu Threads API
  slug: samu-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/samu/openapi/samu-threads-api-openapi.yml
- filename: samu-usuarios-api-openapi.yml
  format: yaml
  label: Samu Usuarios API
  slug: samu-usuarios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/samu/openapi/samu-usuarios-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Cliente: Empresa o grupo de empresas que contratan Samu.AI.'
    type: business
  minimum_age:
    text: null
    value: null
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
name: Samu
provenance_date: '2026-11-10'
provider_name: Samu
provider_slug: samu
slug: samu-eligibility
source_date: '2026-11-10'
source_filename: samu-eligibility.yml
source_heading: Eligibility
source_page: https://www.samu.ai/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Samu\naid: samu\nurl: https://www.samu.ai/terminos-y-condiciones\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Cliente: Empresa o grupo de empresas que contratan Samu.AI.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/samu/eligibility/samu-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Samu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Sales
- Sales Intelligence
- Conversation Intelligence
- CRM
- Call Recording
- Analytics
- Latin America
- Transcription
- WhatsApp
- MCP
- Agent-Native
---
