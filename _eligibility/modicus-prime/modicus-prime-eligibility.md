---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual or entity that wishes to access and use the Services
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: that prohibit or restrict the export or re-export of the Services or any Customer Data outside the US
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
name: Modicus Prime
provenance_date: '2026-11-10'
provider_name: Modicus Prime
provider_slug: modicus-prime
slug: modicus-prime-eligibility
source_date: '2026-11-10'
source_filename: modicus-prime-eligibility.yml
source_heading: Eligibility
source_page: https://modicusprime.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Modicus Prime\naid: modicus-prime\nurl: https://modicusprime.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the individual or entity that wishes to access and use the Services\nrestricted_uses:\n- summary: Export restrictions\n  text: that prohibit or restrict the export or re-export of the Services or any Customer Data outside the US\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/modicus-prime/eligibility/modicus-prime-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Modicus Prime's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Governance
- AI Management System
- Pharmaceuticals
- Life Sciences
- GxP Compliance
- Model Validation
- Quality Management
- Regulatory
- Enterprise AI
---
