---
api_specs:
- filename: vidmob-media-api-openapi.yml
  format: yaml
  label: VidMob Media API
  slug: vidmob-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidmob/openapi/vidmob-media-api-openapi.yml
- filename: vidmob-organization-api-openapi.yml
  format: yaml
  label: VidMob Organization API
  slug: vidmob-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidmob/openapi/vidmob-organization-api-openapi.yml
- filename: vidmob-scoring-api-openapi.yml
  format: yaml
  label: VidMob Scoring API
  slug: vidmob-scoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidmob/openapi/vidmob-scoring-api-openapi.yml
- filename: vidmob-workspaces-api-openapi.yml
  format: yaml
  label: VidMob Workspaces API
  slug: vidmob-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidmob/openapi/vidmob-workspaces-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least 18 years of age and have the authority to enter into these Terms on your own behalf
    type: individual
  - text: If you are using the Platform on behalf of a Customer, your Account will be associated with the relevant Customer organization account
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Competing with Vidmob
    text: Use the Platform for purposes of competing with Vidmob.
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
name: VidMob
provenance_date: '2026-11-10'
provider_name: VidMob
provider_slug: vidmob
slug: vidmob-eligibility
source_date: '2026-11-10'
source_filename: vidmob-eligibility.yml
source_heading: Eligibility
source_page: https://vidmob.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VidMob\naid: vidmob\nurl: https://vidmob.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least 18 years of age and have the authority to enter into these Terms on your own behalf\n- type: business\n  text: If you are using the Platform on behalf of a Customer, your Account will be associated with the relevant\n    Customer organization account\nrestricted_uses:\n- summary: Competing with Vidmob\n  text: Use the Platform for purposes of competing with Vidmob.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/vidmob/eligibility/vidmob-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from VidMob's own page on 2026-11-10.
synthetic: false
tags:
- Creative Intelligence
- creative-data
- Advertising
- Marketing
- Media Measurement
- Video
- Computer Vision
- Creative Analytics
- AdTech
- MCP
- Agent-Native
- MarTech
---
