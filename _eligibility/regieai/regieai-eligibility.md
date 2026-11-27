---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract.
    type: individual
  - text: If you accept these Terms on behalf of an entity, you represent that you are authorized to bind that entity
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Regulated eligibility decisions
    text: The Service is not designed for and must not be used to make decisions subject to the FCRA or other regulated eligibility determinations.
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
name: Regie.ai
provenance_date: '2026-11-10'
provider_name: Regie.ai
provider_slug: regieai
slug: regieai-eligibility
source_date: '2026-11-10'
source_filename: regieai-eligibility.yml
source_heading: Eligibility
source_page: https://regie.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Regie.ai\naid: regieai\nurl: https://regie.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract.\n- type: business\n  text: If you accept these Terms on behalf of an entity, you represent that you are authorized to bind that entity\nrestricted_uses:\n- summary: Regulated eligibility decisions\n  text: The Service is not designed for and must not be used to make decisions subject to the FCRA or other regulated\n    eligibility determinations.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/regieai/eligibility/regieai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Regie.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Apps
- Sales Engagement
- Sales AI
- Outbound
- Prospecting
- Revenue Operations
- AI Agents
---
