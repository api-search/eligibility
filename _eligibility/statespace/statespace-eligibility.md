---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are 13 years or older, are capable of forming a binding contract with Statespace, and are not barred from using the Services under applicable law.
    type: individual
  minimum_age:
    text: You may use the Services only if you are 13 years or older
    value: '13'
  restricted_uses:
  - summary: Non-commercial personal use
    text: solely for your personal and non-commercial purposes
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
name: Statespace
provenance_date: '2026-11-10'
provider_name: Statespace
provider_slug: statespace
slug: statespace-eligibility
source_date: '2026-11-10'
source_filename: statespace-eligibility.yml
source_heading: Eligibility
source_page: https://aimlabs.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Statespace\naid: statespace\nurl: https://aimlabs.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 13 years or older, are capable of forming a binding contract with\n    Statespace, and are not barred from using the Services under applicable law.\nrestricted_uses:\n- summary: Non-commercial personal use\n  text: solely for your personal and non-commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n\
  \  text: You may use the Services only if you are 13 years or older\n"
source_yaml_url: https://artifacts.apis.io/statespace/eligibility/statespace-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Statespace's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Gaming
- Esports
- Aim Training
- Analytics
- Consumer
---
