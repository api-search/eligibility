---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The company or person who accesses or uses the Product.
    type: individual
  - text: If the person accepting this Agreement is doing so on behalf of a company
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: use the Product with any High Risk Activities or with any activity prohibited by Applicable Laws
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
name: CodSpeed
provenance_date: '2026-11-09'
provider_name: CodSpeed
provider_slug: codspeed
slug: codspeed-eligibility
source_date: '2026-11-09'
source_filename: codspeed-eligibility.yml
source_heading: Eligibility
source_page: https://codspeed.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CodSpeed\naid: codspeed\nurl: https://codspeed.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The company or person who accesses or uses the Product.\n- type: business\n  text: If the person accepting this Agreement is doing so on behalf of a company\nrestricted_uses:\n- summary: High-risk activities\n  text: use the Product with any High Risk Activities or with any activity prohibited by Applicable Laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/codspeed/eligibility/codspeed-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from CodSpeed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Performance
- Benchmarking
- Continuous Integration
- Developer Tools
- Observability
- Testing
- DevOps
- Artificial Intelligence
- MCP
---
