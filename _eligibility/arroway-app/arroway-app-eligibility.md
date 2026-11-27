---
api_specs:
- filename: arroway-app-mcp.json
  format: json
  label: Arroway MCP API
  slug: arroway-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arroway-app/openapi/arroway-app-mcp.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You need to be 18 or older.
    type: individual
  - text: If you are signing in for your work, you are telling us you are allowed to put that employer's decisions here.
    type: business
  minimum_age:
    text: You need to be 18 or older.
    value: '18'
  restricted_uses:
  - summary: Personal data only where lawful
    text: Personal data about other people only where the work genuinely needs it and you have a lawful basis to record it.
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
name: Arroway
provenance_date: '2026-11-09'
provider_name: Arroway
provider_slug: arroway-app
slug: arroway-app-eligibility
source_date: '2026-11-09'
source_filename: arroway-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.arroway.app/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arroway\naid: arroway-app\nurl: https://www.arroway.app/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You need to be 18 or older.\n- type: business\n  text: If you are signing in for your work, you are telling us you are allowed to put that employer's decisions\n    here.\nrestricted_uses:\n- summary: Personal data only where lawful\n  text: Personal data about other people only where the work genuinely needs it and you have a lawful basis to record\n    it.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You need to be 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/arroway-app/eligibility/arroway-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Arroway's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Collaboration
- Memory
- Teamwork
- Automation
---
