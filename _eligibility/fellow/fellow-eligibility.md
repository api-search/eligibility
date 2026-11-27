---
api_specs:
- filename: fellow-action-items-api-openapi.yml
  format: yaml
  label: Fellow Action Items API
  slug: fellow-action-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-action-items-api-openapi.yml
- filename: fellow-notes-api-openapi.yml
  format: yaml
  label: Fellow Notes API
  slug: fellow-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-notes-api-openapi.yml
- filename: fellow-recordings-api-openapi.yml
  format: yaml
  label: Fellow Recordings API
  slug: fellow-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-recordings-api-openapi.yml
- filename: fellow-users-api-openapi.yml
  format: yaml
  label: Fellow Users API
  slug: fellow-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-users-api-openapi.yml
- filename: fellow-webhooks-api-openapi.yml
  format: yaml
  label: Fellow Webhooks API
  slug: fellow-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: THESE TERMS OF USE APPLY TO ALL INDIVIDUALS WHO USE THE SERVICES
    type: individual
  - text: has entered into a Master Services Agreement or other agreement with Fellow to access the Platform
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No patient or unlawful data
    text: 'Use the Platform to upload, collect, transmit, store, use or process any patient information or other data:'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: All Users must register for an account to use the Platform
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fellow
provenance_date: '2026-11-09'
provider_name: Fellow
provider_slug: fellow
slug: fellow-eligibility
source_date: '2026-11-09'
source_filename: fellow-eligibility.yml
source_heading: Eligibility
source_page: https://fellow.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fellow\naid: fellow\nurl: https://fellow.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: THESE TERMS OF USE APPLY TO ALL INDIVIDUALS WHO USE THE SERVICES\n- type: business\n  text: has entered into a Master Services Agreement or other agreement with Fellow to access the Platform\nrestricted_uses:\n- summary: No patient or unlawful data\n  text: 'Use the Platform to upload, collect, transmit, store, use or process any patient information or other data:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: All Users must register for an account to use the Platform\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fellow/eligibility/fellow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Fellow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Meetings
- Artificial Intelligence
- Meeting Notes
- Transcription
- Productivity
- Action Items
- Webhook
- MCP
---
