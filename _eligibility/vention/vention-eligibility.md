---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'When you create an Account on behalf of a legal entity, then, you represent and warrant that: (a) said legal entity is duly formed, validly existing and in good standing under the laws of its jurisdiction'
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
name: Vention
provenance_date: '2026-11-10'
provider_name: Vention
provider_slug: vention
slug: vention-eligibility
source_date: '2026-11-10'
source_filename: vention-eligibility.yml
source_heading: Eligibility
source_page: https://vention.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vention\naid: vention\nurl: https://vention.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'When you create an Account on behalf of a legal entity, then, you represent and warrant that: (a) said\n    legal entity is duly formed, validly existing and in good standing under the laws of its jurisdiction'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vention/eligibility/vention-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Vention's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Physical AI
- Manufacturing
- Industrial Automation
- Robotics
- Motion Control
- Python SDK
- Digital Twin
---
