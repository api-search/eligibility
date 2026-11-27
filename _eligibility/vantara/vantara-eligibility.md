---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Consumer: Any User qualifying as such under applicable law.'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use restrictions
    text: Users are solely responsible for making sure that their use of this Application and/or the Service violates no applicable law, regulations or third-party rights.
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
name: Milana
provenance_date: '2026-11-10'
provider_name: Milana
provider_slug: vantara
slug: vantara-eligibility
source_date: '2026-11-10'
source_filename: vantara-eligibility.yml
source_heading: Eligibility
source_page: https://getmilana.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Milana\naid: vantara\nurl: https://getmilana.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'Consumer: Any User qualifying as such under applicable law.'\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: Users are solely responsible for making sure that their use of this Application and/or the Service violates\n    no applicable law, regulations or third-party rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vantara/eligibility/vantara-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Milana's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Session Replay
- Product Analytics
- Developer Tools
- Agents
- SDK
---
