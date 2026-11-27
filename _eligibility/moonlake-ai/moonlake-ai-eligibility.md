---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you can provide consent to data processing under the laws of your territory)
    type: individual
  minimum_age:
    text: You may use the Services only if you are at least 13 years of age
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You may need to provide additional information to verify your identity before completing your Transaction
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MoonLake AI
provenance_date: '2026-11-10'
provider_name: MoonLake AI
provider_slug: moonlake-ai
slug: moonlake-ai-eligibility
source_date: '2026-11-10'
source_filename: moonlake-ai-eligibility.yml
source_heading: Eligibility
source_page: https://moonlakeai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MoonLake AI\naid: moonlake-ai\nurl: https://moonlakeai.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you\n    can provide consent to data processing under the laws of your territory)\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your Transaction\nminimum_age:\n  value: '13'\n  text:\
  \ You may use the Services only if you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/moonlake-ai/eligibility/moonlake-ai-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from MoonLake AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- World Models
- Simulation
- Embodied AI
- Robotics
- 3D Generation
- Digital Twin
- Synthetic Data
---
