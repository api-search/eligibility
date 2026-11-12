---
api_specs:
- filename: clipkit-dev-openapi-generated.yml
  format: yaml
  label: Clipkit Render API
  slug: clipkit-dev-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipkit-dev/openapi/_ae-authored/clipkit-dev-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use the Service.
    type: individual
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization, and "you" refers to that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use the Service.
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
name: Clipkit
provenance_date: '2026-11-09'
provider_name: Clipkit
provider_slug: clipkit-dev
slug: clipkit-dev-eligibility
source_date: '2026-11-09'
source_filename: clipkit-dev-eligibility.yml
source_heading: Eligibility
source_page: https://www.clipkit.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clipkit\naid: clipkit-dev\nurl: https://www.clipkit.dev/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use the Service.\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization, and \"you\" refers to that organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/clipkit-dev/eligibility/clipkit-dev-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Clipkit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Video Rendering
- AI Agents
- MCP
- JSON
- Open Source
- Developer Tools
---
