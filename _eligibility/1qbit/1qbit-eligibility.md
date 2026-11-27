---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are acting on behalf of a company or entity that you have the authority to bind such entity.
    type: business
  minimum_age:
    text: You may not use the Service and you may not accept this Agreement if you are not of a legal age to form a binding contract with 1QBit.
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: You are only entitled to access and use 1QBit.com for lawful purposes.
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
name: 1QBit
provenance_date: '2026-11-09'
provider_name: 1QBit
provider_slug: 1qbit
slug: 1qbit-eligibility
source_date: '2026-11-09'
source_filename: 1qbit-eligibility.yml
source_heading: Eligibility
source_page: https://1qbit.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 1QBit\naid: 1qbit\nurl: https://1qbit.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are acting on behalf of a company or entity that you have the authority to bind such entity.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You are only entitled to access and use 1QBit.com for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may not use the Service and you may not accept this Agreement if you are not of\
  \ a legal age to form\n    a binding contract with 1QBit.\n"
source_yaml_url: https://artifacts.apis.io/1qbit/eligibility/1qbit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from 1QBit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Quantum Computing
- Optimization
- Machine Learning
- Simulation
- Scientific Computing
- Research
- Canada
---
