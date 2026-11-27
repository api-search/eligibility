---
api_specs:
- filename: wsc-sports-feed-api-openapi.yml
  format: yaml
  label: WSC Sports Feed API
  slug: wsc-sports-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsc-sports/openapi/wsc-sports-feed-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is only intended for individuals aged thirteen (13) years or older.
    type: individual
  minimum_age:
    text: The Website is only intended for individuals aged thirteen (13) years or older.
    value: '13'
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
name: WSC Sports
provenance_date: '2026-11-10'
provider_name: WSC Sports
provider_slug: wsc-sports
slug: wsc-sports-eligibility
source_date: '2026-11-10'
source_filename: wsc-sports-eligibility.yml
source_heading: Eligibility
source_page: https://wsc-sports.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WSC Sports\naid: wsc-sports\nurl: https://wsc-sports.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is only intended for individuals aged thirteen (13) years or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Website is only intended for individuals aged thirteen (13) years or older.\n"
source_yaml_url: https://artifacts.apis.io/wsc-sports/eligibility/wsc-sports-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from WSC Sports's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports
- Video
- Media
- Artificial Intelligence
- Content
- Streaming
- SDK
- Highlights
- Personalization
---
