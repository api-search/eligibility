---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent and warrant that you are at least eighteen (18) years of age and are not a person barred from receiving the Services
    type: individual
  minimum_age:
    text: you represent and warrant that you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: Use of the Services is not for emergencies.
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
name: Q Bio
provenance_date: '2026-11-10'
provider_name: Q Bio
provider_slug: q-bio
slug: q-bio-eligibility
source_date: '2026-11-10'
source_filename: q-bio-eligibility.yml
source_heading: Eligibility
source_page: https://q.bio/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Q Bio\naid: q-bio\nurl: https://q.bio/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent and warrant that you are at least eighteen (18) years of age and are not a person barred from\n    receiving the Services\nrestricted_uses:\n- summary: Not for emergencies\n  text: Use of the Services is not for emergencies.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least eighteen (18) years\
  \ of age\n"
source_yaml_url: https://artifacts.apis.io/q-bio/eligibility/q-bio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Q Bio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Preventive Health
- Medical Imaging
- MRI
- Genomics
- Longevity
- Health Data
---
