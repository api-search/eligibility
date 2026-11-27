---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer, please note that these terms of use, their subject matter and their formation, are governed by English law.
    type: individual
  - text: If you are a business, these terms of use, their subject matter and their formation (and any non-contractual disputes or claims) are governed by English law.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Enzai
provenance_date: '2026-11-09'
provider_name: Enzai
provider_slug: enzai
slug: enzai-eligibility
source_date: '2026-11-09'
source_filename: enzai-eligibility.yml
source_heading: Eligibility
source_page: https://www.enz.ai/policies/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enzai\naid: enzai\nurl: https://www.enz.ai/policies/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer, please note that these terms of use, their subject matter and their formation, are\n    governed by English law.\n- type: business\n  text: If you are a business, these terms of use, their subject matter and their formation (and any non-contractual\n    disputes or claims) are governed by English law.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/enzai/eligibility/enzai-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Enzai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Governance
- Artificial Intelligence
- Compliance
- Risk Management
- AI Registry
- EU AI Act
- Enterprise Software
---
