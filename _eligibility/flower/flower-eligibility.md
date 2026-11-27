---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These ToS form a legal contract between you, either (a) an individual user or (b) a business organization
    type: individual
  - text: either (a) an individual user or (b) a business organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk applications excluded
    text: Use of the Platform in high-risk areas is excluded (operation of nuclear power plants, air traffic control systems, weapons of war, life-support equipment or comparable high-risk applications
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
name: Flower
provenance_date: '2026-11-09'
provider_name: Flower
provider_slug: flower
slug: flower-eligibility
source_date: '2026-11-09'
source_filename: flower-eligibility.yml
source_heading: Eligibility
source_page: https://flower.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flower\naid: flower\nurl: https://flower.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These ToS form a legal contract between you, either (a) an individual user or (b) a business organization\n- type: business\n  text: either (a) an individual user or (b) a business organization\nrestricted_uses:\n- summary: High-risk applications excluded\n  text: Use of the Platform in high-risk areas is excluded (operation of nuclear power plants, air traffic control\n    systems, weapons of war, life-support equipment\
  \ or comparable high-risk applications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flower/eligibility/flower-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Flower's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Federated Learning
- Federated AI
- Machine Learning
- Artificial Intelligence
- Privacy
- SDK
- On-Device AI
- Confidential Computing
- Open Source
---
