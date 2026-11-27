---
api_specs:
- filename: archome-ai-openapi-generated.yml
  format: yaml
  label: Archome AI API
  slug: archome-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archome-ai/openapi/_ae-authored/archome-ai-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to register.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to register.
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
name: Archome AI
provenance_date: '2026-11-09'
provider_name: Archome AI
provider_slug: archome-ai
slug: archome-ai-eligibility
source_date: '2026-11-09'
source_filename: archome-ai-eligibility.yml
source_heading: Eligibility
source_page: https://archome.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Archome AI\naid: archome-ai\nurl: https://archome.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to register.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to register.\n"
source_yaml_url: https://artifacts.apis.io/archome-ai/eligibility/archome-ai-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Archome AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Virtual Staging
- Architectural Rendering
- Design Tools
- Software-as-a-Service
---
