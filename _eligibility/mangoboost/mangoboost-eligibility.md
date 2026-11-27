---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Site is only for your personal and non-commercial use
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent purpose
    text: Use the Services for any unlawful or fraudulent purpose
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
name: MangoBoost
provenance_date: '2026-11-10'
provider_name: MangoBoost
provider_slug: mangoboost
slug: mangoboost-eligibility
source_date: '2026-11-10'
source_filename: mangoboost-eligibility.yml
source_heading: Eligibility
source_page: https://www.mangoboost.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MangoBoost\naid: mangoboost\nurl: https://www.mangoboost.io/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Site is only for your personal and non-commercial use\nrestricted_uses:\n- summary: Unlawful or fraudulent purpose\n  text: Use the Services for any unlawful or fraudulent purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mangoboost/eligibility/mangoboost-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from MangoBoost's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Infrastructure
- Data Center
- Semiconductors
- Hardware
- Storage
- Networking
- Inference
- GPU
- DPU
---
