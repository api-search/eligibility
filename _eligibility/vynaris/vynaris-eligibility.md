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
  - summary: Child sexual exploitation material
    text: Create, solicit, possess, or distribute child sexual exploitation material.
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
name: Vynaris
provenance_date: '2026-11-10'
provider_name: Vynaris
provider_slug: vynaris
slug: vynaris-eligibility
source_date: '2026-11-10'
source_filename: vynaris-eligibility.yml
source_heading: Eligibility
source_page: https://vynaris.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vynaris\naid: vynaris\nurl: https://vynaris.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Child sexual exploitation material\n  text: Create, solicit, possess, or distribute child sexual exploitation material.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vynaris/eligibility/vynaris-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Vynaris's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- LLM Gateway
- LLM Router / Aggregator
- Inference / Model Serving
- AI Cost Management / FinOps
- Developer Tools
- Agent Infrastructure
---
