---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You means the individual accessing the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: individual
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
name: Scimar
provenance_date: '2026-11-10'
provider_name: Scimar
provider_slug: scimar
slug: scimar-eligibility
source_date: '2026-11-10'
source_filename: scimar-eligibility.yml
source_heading: Eligibility
source_page: https://scimar.ca/about/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scimar\naid: scimar\nurl: https://scimar.ca/about/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You means the individual accessing the Service, or the company, or other legal entity on behalf of which\n    such individual is accessing or using the Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/scimar/eligibility/scimar-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Scimar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biotechnology
- Life Sciences
- Pharmaceuticals
- Diabetes
- Diagnostics
- Clinical Trials
- Health
- Nutrition
- Research
- Canada
- Content
---
