---
api_specs:
- filename: demodesk-externally-recorded-demos-api-openapi.yml
  format: yaml
  label: Demodesk Externally recorded demos API
  slug: demodesk-externally-recorded-demos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demodesk/openapi/demodesk-externally-recorded-demos-api-openapi.yml
- filename: demodesk-recordings-api-openapi.yml
  format: yaml
  label: Demodesk Recordings API
  slug: demodesk-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demodesk/openapi/demodesk-recordings-api-openapi.yml
- filename: demodesk-users-api-openapi.yml
  format: yaml
  label: Demodesk Users API
  slug: demodesk-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demodesk/openapi/demodesk-users-api-openapi.yml
- filename: demodesk-demodesk-public-api-api-openapi.yml
  format: yaml
  label: Demodesk Public API
  slug: demodesk-demodesk-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demodesk/openapi/demodesk-demodesk-public-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You (either an individual or a single entity
    type: individual
  - text: '"Entrepreneur" means any natural person, legal entity or partnership, having legal capacity that is not engaged in personal or familial usage in ordering or receiving SaaS while performing its commercial or independent professional or other work.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: The Software is not fault tolerant and is not designed, manufactured, or intended for use or resale as control equipment in hazardous environments requiring fail-safe performance
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
name: Demodesk
provenance_date: '2026-11-09'
provider_name: Demodesk
provider_slug: demodesk
slug: demodesk-eligibility
source_date: '2026-11-09'
source_filename: demodesk-eligibility.yml
source_heading: Eligibility
source_page: https://demodesk.ai/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Demodesk\naid: demodesk\nurl: https://demodesk.ai/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You (either an individual or a single entity\n- type: business\n  text: '\"Entrepreneur\" means any natural person, legal entity or partnership, having legal capacity that is not\n    engaged in personal or familial usage in ordering or receiving SaaS while performing its commercial or independent\n    professional or other work.'\nrestricted_uses:\n- summary: High-risk activities\n  text: The Software is not fault tolerant\
  \ and is not designed, manufactured, or intended for use or resale as control\n    equipment in hazardous environments requiring fail-safe performance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/demodesk/eligibility/demodesk-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Demodesk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sales
- Artificial Intelligence
- Conversation Intelligence
- Video Conferencing
- CRM
- Transcription
- Webhook
- MCP
---
