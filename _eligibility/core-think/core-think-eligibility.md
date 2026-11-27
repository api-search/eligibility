---
api_specs:
- filename: core-think-openapi-generated.yml
  format: yaml
  label: Core Think API
  slug: core-think-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/core-think/openapi/_ae-authored/core-think-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old or the minimum age required in your country to use the Service
    value: '13'
  restricted_uses:
  - summary: High-stakes automated decisions
    text: Making high-stakes automated decisions that affect a person's safety, legal or material rights, or well-being.
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
name: Core Think
provenance_date: '2026-11-09'
provider_name: Core Think
provider_slug: core-think
slug: core-think-eligibility
source_date: '2026-11-09'
source_filename: core-think-eligibility.yml
source_heading: Eligibility
source_page: https://corethink.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Core Think\naid: core-think\nurl: https://corethink.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High-stakes automated decisions\n  text: Making high-stakes automated decisions that affect a person's safety, legal or material rights, or well-being.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old or the minimum age required in your country to use the Service\n"
source_yaml_url: https://artifacts.apis.io/core-think/eligibility/core-think-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Core Think's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Neurosymbolic
- Platform
- Machine Learning
---
