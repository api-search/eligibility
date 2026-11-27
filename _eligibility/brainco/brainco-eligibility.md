---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: solely for your own personal, noncommercial use
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial exploitation
    text: you shall not license, sell, rent, lease, transfer, assign, distribute, host, or otherwise commercially exploit the Services
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
name: BrainCo
provenance_date: '2026-11-09'
provider_name: BrainCo
provider_slug: brainco
slug: brainco-eligibility
source_date: '2026-11-09'
source_filename: brainco-eligibility.yml
source_heading: Eligibility
source_page: https://brainco.tech/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BrainCo\naid: brainco\nurl: https://brainco.tech/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: solely for your own personal, noncommercial use\nrestricted_uses:\n- summary: Commercial exploitation\n  text: you shall not license, sell, rent, lease, transfer, assign, distribute, host, or otherwise commercially\n    exploit the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brainco/eligibility/brainco-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from BrainCo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Neurotechnology
- Brain-Computer Interface
- EEG
- Wearables
- Robotics
- SDK
- Education
---
