---
claim_count: 2
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
  - summary: No highly sensitive PII
    text: provide the Service with access to highly sensitive personally identifiable information, including, without limitation, social security and credit card numbers
  - summary: Compliance with laws including Fair Housing Act
    text: engage in any activity that violates applicable laws, rules or regulations (including, without limitation, the Fair Housing Act and the Real Estate Settlement Procedures Act)
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
name: Housewhisper
provenance_date: '2026-11-09'
provider_name: Housewhisper
provider_slug: housewhisper
slug: housewhisper-eligibility
source_date: '2026-11-09'
source_filename: housewhisper-eligibility.yml
source_heading: Eligibility
source_page: https://housewhisper.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Housewhisper\naid: housewhisper\nurl: https://housewhisper.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No highly sensitive PII\n  text: provide the Service with access to highly sensitive personally identifiable information, including, without\n    limitation, social security and credit card numbers\n- summary: Compliance with laws including Fair Housing Act\n  text: engage in any activity that violates applicable laws, rules or regulations (including, without limitation,\n    the Fair Housing Act and the\
  \ Real Estate Settlement Procedures Act)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/housewhisper/eligibility/housewhisper-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Housewhisper's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Artificial Intelligence
- AI Assistant
- Voice AI
- Lead Management
- CRM
- PropTech
- Sales Automation
---
