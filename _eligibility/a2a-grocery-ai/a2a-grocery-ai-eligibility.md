---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Anyone may read status and class-level information.
    type: individual
  - text: Item-level information, pricing, availability and ordering are available only to makers, brand owners, private label, distributors, importers, brokers, retail buyers and their authorized agents.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Advertising prohibited
    text: no use of the service to advertise
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Presenting a credential you do not hold is a breach of these terms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: A2A Grocery
provenance_date: '2026-11-09'
provider_name: A2A Grocery
provider_slug: a2a-grocery-ai
slug: a2a-grocery-ai-eligibility
source_date: '2026-11-09'
source_filename: a2a-grocery-ai-eligibility.yml
source_heading: Eligibility
source_page: https://a2a-grocery.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: A2A Grocery\naid: a2a-grocery-ai\nurl: https://a2a-grocery.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Anyone may read status and class-level information.\n- type: business\n  text: Item-level information, pricing, availability and ordering are available only to makers, brand owners, private\n    label, distributors, importers, brokers, retail buyers and their authorized agents.\nrestricted_uses:\n- summary: Advertising prohibited\n  text: no use of the service to advertise\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Presenting a credential you do not hold is a breach of these terms.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/a2a-grocery-ai/eligibility/a2a-grocery-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from A2A Grocery's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Grocery
- Procurement
- Agents
- Marketplace
---
