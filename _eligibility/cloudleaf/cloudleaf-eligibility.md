---
api_specs:
- filename: cloudleaf-token-api-openapi.yml
  format: yaml
  label: ParkourSC Token API
  slug: cloudleaf-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudleaf/openapi/cloudleaf-token-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: You may not export or re-export any of the Company Products and Services except in compliance with the United States Export Administration Act and the related rules and regulations
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
name: ParkourSC
provenance_date: '2026-11-09'
provider_name: ParkourSC
provider_slug: cloudleaf
slug: cloudleaf-eligibility
source_date: '2026-11-09'
source_filename: cloudleaf-eligibility.yml
source_heading: Eligibility
source_page: https://www.parkoursc.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ParkourSC\naid: cloudleaf\nurl: https://www.parkoursc.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not export or re-export any of the Company Products and Services except in compliance with the United\n    States Export Administration Act and the related rules and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cloudleaf/eligibility/cloudleaf-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from ParkourSC's own page on 2026-11-09.
synthetic: false
tags:
- Supply Chain
- Artificial Intelligence
- Digital Twin
- Decision Intelligence
- Logistics
- Cloud
---
