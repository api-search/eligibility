---
api_specs:
- filename: compeller-ai-auth-api-openapi.yml
  format: yaml
  label: Compeller Auth API
  slug: compeller-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-auth-api-openapi.yml
- filename: compeller-ai-compels-api-openapi.yml
  format: yaml
  label: Compeller Compels API
  slug: compeller-ai-compels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-compels-api-openapi.yml
- filename: compeller-ai-discovery-api-openapi.yml
  format: yaml
  label: Compeller Discovery API
  slug: compeller-ai-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-discovery-api-openapi.yml
- filename: compeller-ai-lighting-api-openapi.yml
  format: yaml
  label: Compeller Lighting API
  slug: compeller-ai-lighting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-lighting-api-openapi.yml
- filename: compeller-ai-media-api-openapi.yml
  format: yaml
  label: Compeller Media API
  slug: compeller-ai-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-media-api-openapi.yml
- filename: compeller-ai-music-api-openapi.yml
  format: yaml
  label: Compeller Music API
  slug: compeller-ai-music-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-music-api-openapi.yml
- filename: compeller-ai-renderings-api-openapi.yml
  format: yaml
  label: Compeller Renderings API
  slug: compeller-ai-renderings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-renderings-api-openapi.yml
- filename: compeller-ai-webhooks-api-openapi.yml
  format: yaml
  label: Compeller Webhooks API
  slug: compeller-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compeller-ai/openapi/compeller-ai-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company makes no representations that Company Properties are appropriate or available for use in other locations.
  entity_types:
  - text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH COMPANY
    type: individual
  - text: PERSONALLY OR ON BEHALF OF THE ENTITY YOU HAVE NAMED AS THE USER, AND TO BIND THAT ENTITY TO THE TERMS OF USE
    type: business
  minimum_age:
    text: You represent that you are (i) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: No prohibited purposes
    text: you agree not to use Company Properties for any purpose that is prohibited by this Agreement or by applicable law.
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
name: Compeller
provenance_date: '2026-11-09'
provider_name: Compeller
provider_slug: compeller-ai
slug: compeller-ai-eligibility
source_date: '2026-11-09'
source_filename: compeller-ai-eligibility.yml
source_heading: Eligibility
source_page: https://compeller.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Compeller\naid: compeller-ai\nurl: https://compeller.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Company makes no representations that Company Properties are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH COMPANY\n- type: business\n  text: PERSONALLY OR ON BEHALF OF THE ENTITY YOU HAVE NAMED AS THE USER, AND TO BIND THAT ENTITY TO THE TERMS OF\n    USE\nrestricted_uses:\n- summary: No prohibited purposes\n  text: you agree not to use Company Properties for any purpose\
  \ that is prohibited by this Agreement or by applicable\n    law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are (i) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/compeller-ai/eligibility/compeller-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Compeller's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI
- Music
- Video Generation
- Live Performance
- Audio Reactive Visuals
- MCP
---
