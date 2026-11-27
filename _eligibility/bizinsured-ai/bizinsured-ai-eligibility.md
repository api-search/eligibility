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
  - summary: Not insurance advice
    text: The information, recommendations, and premium estimates provided by BizInsured are for educational and informational purposes only.
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
name: BizInsured.ai
provenance_date: '2026-11-09'
provider_name: BizInsured.ai
provider_slug: bizinsured-ai
slug: bizinsured-ai-eligibility
source_date: '2026-11-09'
source_filename: bizinsured-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bizinsured.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BizInsured.ai\naid: bizinsured-ai\nurl: https://bizinsured.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not insurance advice\n  text: The information, recommendations, and premium estimates provided by BizInsured are for educational and informational\n    purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bizinsured-ai/eligibility/bizinsured-ai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from BizInsured.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Artificial Intelligence
- Commercial
- BOP
- Quotes
---
