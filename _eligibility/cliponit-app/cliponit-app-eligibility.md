---
api_specs:
- filename: cliponit-app-account-api-openapi.yml
  format: yaml
  label: ClipOnIt Account API
  slug: cliponit-app-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-account-api-openapi.yml
- filename: cliponit-app-agents-api-openapi.yml
  format: yaml
  label: ClipOnIt Agents API
  slug: cliponit-app-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-agents-api-openapi.yml
- filename: cliponit-app-auth-api-openapi.yml
  format: yaml
  label: ClipOnIt Auth API
  slug: cliponit-app-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-auth-api-openapi.yml
- filename: cliponit-app-billing-api-openapi.yml
  format: yaml
  label: ClipOnIt Billing API
  slug: cliponit-app-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-billing-api-openapi.yml
- filename: cliponit-app-clips-api-openapi.yml
  format: yaml
  label: ClipOnIt Clips API
  slug: cliponit-app-clips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-clips-api-openapi.yml
- filename: cliponit-app-enrich-api-openapi.yml
  format: yaml
  label: ClipOnIt Enrich API
  slug: cliponit-app-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-enrich-api-openapi.yml
- filename: cliponit-app-explainer-api-openapi.yml
  format: yaml
  label: ClipOnIt Explainer API
  slug: cliponit-app-explainer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-explainer-api-openapi.yml
- filename: cliponit-app-smart-api-openapi.yml
  format: yaml
  label: ClipOnIt Smart API
  slug: cliponit-app-smart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-smart-api-openapi.yml
- filename: cliponit-app-tiktok-api-openapi.yml
  format: yaml
  label: ClipOnIt Tiktok API
  slug: cliponit-app-tiktok-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-tiktok-api-openapi.yml
- filename: cliponit-app-videos-api-openapi.yml
  format: yaml
  label: ClipOnIt Videos API
  slug: cliponit-app-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-videos-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per person, with a valid email address.
    type: individual
  minimum_age:
    text: You must be at least 16 years old.
    value: '16'
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
name: ClipOnIt
provenance_date: '2026-11-09'
provider_name: ClipOnIt
provider_slug: cliponit-app
slug: cliponit-app-eligibility
source_date: '2026-11-09'
source_filename: cliponit-app-eligibility.yml
source_heading: Eligibility
source_page: https://cliponit.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClipOnIt\naid: cliponit-app\nurl: https://cliponit.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account per person, with a valid email address.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/cliponit-app/eligibility/cliponit-app-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from ClipOnIt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Artificial Intelligence
- Short-Form Video
- Video Editing
- MCP
- Content Creation
- Social Media
---
