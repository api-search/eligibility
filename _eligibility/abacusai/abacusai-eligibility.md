---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual or juridical entity that registers for and/or uses the Services
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use policy
    text: to engage in, promote or encourage illegal activity
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
name: Abacus.ai
provenance_date: '2026-11-09'
provider_name: Abacus.ai
provider_slug: abacusai
slug: abacusai-eligibility
source_date: '2026-11-09'
source_filename: abacusai-eligibility.yml
source_heading: Eligibility
source_page: https://abacus.ai/customer-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Abacus.ai\naid: abacusai\nurl: https://abacus.ai/customer-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the individual or juridical entity that registers for and/or uses the Services\nrestricted_uses:\n- summary: Acceptable use policy\n  text: to engage in, promote or encourage illegal activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/abacusai/eligibility/abacusai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Abacus.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Generative AI
- LLM
- AI Agents
- MLOps
- Enterprise AI
- Data Science
---
