---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You may use the Platform only if you: • are at least eighteen (18) years of age; • are legally competent to contract under applicable law;'
    type: individual
  minimum_age:
    text: 'You may use the Platform only if you: • are at least eighteen (18) years of age;'
    value: '18'
  restricted_uses:
  - summary: Misuse of prescriptions and fraud
    text: The Company reserves the right to suspend or terminate access where misuse, fraud, abuse, or patient-safety concerns arise.
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
name: zelta-in
provenance_date: '2026-11-10'
provider_name: zelta-in
provider_slug: zelta-in
slug: zelta-in-eligibility
source_date: '2026-11-10'
source_filename: zelta-in-eligibility.yml
source_heading: Eligibility
source_page: https://zelta.in/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: zelta-in\naid: zelta-in\nurl: https://zelta.in/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You may use the Platform only if you: • are at least eighteen (18) years of age; • are legally competent\n    to contract under applicable law;'\nrestricted_uses:\n- summary: Misuse of prescriptions and fraud\n  text: The Company reserves the right to suspend or terminate access where misuse, fraud, abuse, or patient-safety\n    concerns arise.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: 'You may use the Platform only if you: • are at least eighteen (18) years of age;'\n"
source_yaml_url: https://artifacts.apis.io/zelta-in/eligibility/zelta-in-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from zelta-in's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Analytics
- Advertising
- Privacy
- Marketing
---
