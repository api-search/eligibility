---
api_specs:
- filename: dadan-io-openapi-generated.yml
  format: yaml
  label: Dadan Recording Request API
  slug: recording-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dadan-io/openapi/_ae-authored/dadan-io-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Enterprise accounts for organizational use
    type: business
  minimum_age:
    text: null
    value: null
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
name: Dadan
provenance_date: '2026-11-09'
provider_name: Dadan
provider_slug: dadan-io
slug: dadan-io-eligibility
source_date: '2026-11-09'
source_filename: dadan-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.dadan.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dadan\naid: dadan-io\nurl: https://www.dadan.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Enterprise accounts for organizational use\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dadan-io/eligibility/dadan-io-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Dadan's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Screen Recording
- Video Hosting
- Video Analytics
- MCP
- AI Agents
---
