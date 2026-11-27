---
api_specs:
- filename: eng-api
  format: yaml
  label: TrojAI Platform API
  slug: trojai-platform-api
  spec_type: OpenAPI
  url: https://docs.troj.ai/reference/eng-api
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: our free licence for individuals only
    type: individual
  - text: our subscription package for corporations
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial purpose use of materials
    text: use the materials for any commercial purpose, or for any public display (commercial or non-commercial)
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
name: TrojAI
provenance_date: '2026-11-10'
provider_name: TrojAI
provider_slug: trojai
slug: trojai-eligibility
source_date: '2026-11-10'
source_filename: trojai-eligibility.yml
source_heading: Eligibility
source_page: https://troj.ai/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TrojAI\naid: trojai\nurl: https://troj.ai/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: our free licence for individuals only\n- type: business\n  text: our subscription package for corporations\nrestricted_uses:\n- summary: No commercial purpose use of materials\n  text: use the materials for any commercial purpose, or for any public display (commercial or non-commercial)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trojai/eligibility/trojai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from TrojAI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Security
- Machine Learning
- LLM Security
- Red Teaming
- AI Firewall
- Prompt Injection
- Model Risk
- MLOps
- AI Agents
---
