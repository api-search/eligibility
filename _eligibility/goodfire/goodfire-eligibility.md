---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Minors exploitation
    text: For the purpose of exploiting, harming, or attempting to exploit or harm minors in any way
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
name: Goodfire
provenance_date: '2026-11-09'
provider_name: Goodfire
provider_slug: goodfire
slug: goodfire-eligibility
source_date: '2026-11-09'
source_filename: goodfire-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.prod.website-files.com/67b4608695ee3b31a669d3a9/67b856d25635919af723e246_TermsOfUse.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Goodfire\naid: goodfire\nurl: https://cdn.prod.website-files.com/67b4608695ee3b31a669d3a9/67b856d25635919af723e246_TermsOfUse.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Minors exploitation\n  text: For the purpose of exploiting, harming, or attempting to exploit or harm minors in any way\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/goodfire/eligibility/goodfire-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Goodfire's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Interpretability
- LLM
- Model Steering
- Inference
- Developer Tools
- Research
---
