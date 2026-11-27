---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are at least 18 years old or of the minimum age required in your jurisdiction to use or consent to use the Services and Website
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: you will access and use the Website and the Services in compliance with any and all applicable law(s), rules(s) or regulation(s)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must register and establish an account on the Website
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Visual Layer
provenance_date: '2026-11-10'
provider_name: Visual Layer
provider_slug: visual-layer
slug: visual-layer-eligibility
source_date: '2026-11-10'
source_filename: visual-layer-eligibility.yml
source_heading: Eligibility
source_page: https://docs.visual-layer.com/docs/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Visual Layer\naid: visual-layer\nurl: https://docs.visual-layer.com/docs/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: you will access and use the Website and the Services in compliance with any and all applicable law(s), rules(s)\n    or regulation(s)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must register and establish an account on the Website\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old or of the minimum age required in\
  \ your jurisdiction to use or consent to use\n    the Services and Website\n"
source_yaml_url: https://artifacts.apis.io/visual-layer/eligibility/visual-layer-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Visual Layer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Computer Vision
- Machine Learning
- Data Management
- Dataset Curation
- Unstructured Data
- Image
- Video
- Semantic Search
- Artificial Intelligence
---
