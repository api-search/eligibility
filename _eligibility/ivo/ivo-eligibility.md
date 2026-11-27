---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: use the Services with any High Risk Activities or with activity prohibited by Applicable Laws
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
name: Ivo
provenance_date: '2026-11-09'
provider_name: Ivo
provider_slug: ivo
slug: ivo-eligibility
source_date: '2026-11-09'
source_filename: ivo-eligibility.yml
source_heading: Eligibility
source_page: https://www.ivo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ivo\naid: ivo\nurl: https://www.ivo.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High-risk activities\n  text: use the Services with any High Risk Activities or with activity prohibited by Applicable Laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/ivo/eligibility/ivo-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Ivo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal AI
- Contract Review
- Contract Intelligence
- Legal Tech
- Contract Lifecycle Management
- Redlining
- Enterprise
- AI Agents
---
