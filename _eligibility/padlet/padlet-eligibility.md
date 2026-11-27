---
api_specs:
- filename: padlet-ai-recipe-boards-api-openapi.yml
  format: yaml
  label: Padlet AI Recipe Boards API
  slug: padlet-ai-recipe-boards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/padlet/openapi/padlet-ai-recipe-boards-api-openapi.yml
- filename: padlet-boards-api-openapi.yml
  format: yaml
  label: Padlet Boards API
  slug: padlet-boards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/padlet/openapi/padlet-boards-api-openapi.yml
- filename: padlet-comments-api-openapi.yml
  format: yaml
  label: Padlet Comments API
  slug: padlet-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/padlet/openapi/padlet-comments-api-openapi.yml
- filename: padlet-organizations-api-openapi.yml
  format: yaml
  label: Padlet Organizations API
  slug: padlet-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/padlet/openapi/padlet-organizations-api-openapi.yml
- filename: padlet-posts-api-openapi.yml
  format: yaml
  label: Padlet Posts API
  slug: padlet-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/padlet/openapi/padlet-posts-api-openapi.yml
- filename: padlet-reactions-api-openapi.yml
  format: yaml
  label: Padlet Reactions API
  slug: padlet-reactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/padlet/openapi/padlet-reactions-api-openapi.yml
- filename: padlet-users-api-openapi.yml
  format: yaml
  label: Padlet Users API
  slug: padlet-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/padlet/openapi/padlet-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Padlet is not currently directed to children under the age of 13
    value: '13'
  restricted_uses:
  - summary: Children under 13
    text: Padlet is not currently directed to children under the age of 13 and such children may only use the Padlet Services with guidance, supervision and consent of their parents, guardians and/or authorized school officials.
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
name: Padlet
provenance_date: '2026-11-10'
provider_name: Padlet
provider_slug: padlet
slug: padlet-eligibility
source_date: '2026-11-10'
source_filename: padlet-eligibility.yml
source_heading: Eligibility
source_page: https://legal.padlet.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Padlet\naid: padlet\nurl: https://legal.padlet.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Children under 13\n  text: Padlet is not currently directed to children under the age of 13 and such children may only use the Padlet\n    Services with guidance, supervision and consent of their parents, guardians and/or authorized school officials.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Padlet is not currently directed to children under the age\
  \ of 13\n"
source_yaml_url: https://artifacts.apis.io/padlet/eligibility/padlet-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Padlet's own page on 2026-11-10.
synthetic: false
tags:
- Collaboration
- Education
- Visual Collaboration
- Content
- Boards
- Productivity
- JSON:API
- MCP
- EdTech
---
