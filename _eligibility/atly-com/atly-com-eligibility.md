---
api_specs:
- filename: atly-com-mcp.json
  format: json
  label: Atly API
  slug: atly-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atly-com/openapi/atly-com-mcp.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals aged thirteen (13) years or older.
    type: individual
  minimum_age:
    text: The Site is only intended for individuals aged thirteen (13) years or older.
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
name: Atly
provenance_date: '2026-11-09'
provider_name: Atly
provider_slug: atly-com
slug: atly-com-eligibility
source_date: '2026-11-09'
source_filename: atly-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.atly.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atly\naid: atly-com\nurl: https://www.atly.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged thirteen (13) years or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is only intended for individuals aged thirteen (13) years or older.\n"
source_yaml_url: https://artifacts.apis.io/atly-com/eligibility/atly-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Atly's own page on 2026-11-09.
synthetic: false
tags:
- Location
- Recommendations
- Artificial Intelligence
- Mapping
- Personalization
---
