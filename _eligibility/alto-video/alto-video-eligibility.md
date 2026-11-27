---
api_specs:
- filename: alto-video-openapi-generated.yml
  format: yaml
  label: Alto API
  slug: alto-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alto-video/openapi/_ae-authored/alto-video-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using Alto for a company, you confirm you can bind that company.
    type: business
  minimum_age:
    text: You must be 16 or older.
    value: '16'
  restricted_uses:
  - summary: Illegal or harmful content
    text: anything illegal where you or your viewers are, sexual content involving minors, or content that harasses or threatens a person
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
name: Alto
provenance_date: '2026-11-09'
provider_name: Alto
provider_slug: alto-video
slug: alto-video-eligibility
source_date: '2026-11-09'
source_filename: alto-video-eligibility.yml
source_heading: Eligibility
source_page: https://alto.video/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alto\naid: alto-video\nurl: https://alto.video/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using Alto for a company, you confirm you can bind that company.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: anything illegal where you or your viewers are, sexual content involving minors, or content that harasses\n    or threatens a person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be 16 or older.\n"
source_yaml_url: https://artifacts.apis.io/alto-video/eligibility/alto-video-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Alto's own page on 2026-11-09.
synthetic: false
tags:
- Video Hosting
- Sales Enablement
- Demo Analytics
- Privacy
- Software-as-a-Service
---
