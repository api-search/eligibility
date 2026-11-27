---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Dialogus provides AI voice agents that handle phone conversations on behalf of enterprise customers
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or unlawful automated calls
    text: You may not use the services to violate law, to place unlawful automated calls
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
name: Dialogus
provenance_date: '2026-11-09'
provider_name: Dialogus
provider_slug: dialogus
slug: dialogus-eligibility
source_date: '2026-11-09'
source_filename: dialogus-eligibility.yml
source_heading: Eligibility
source_page: https://www.dialoguslabs.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dialogus\naid: dialogus\nurl: https://www.dialoguslabs.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Dialogus provides AI voice agents that handle phone conversations on behalf of enterprise customers\nrestricted_uses:\n- summary: Unlawful or unlawful automated calls\n  text: You may not use the services to violate law, to place unlawful automated calls\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dialogus/eligibility/dialogus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Dialogus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice Agents
- AI Agents
- Conversational AI
- Customer Service
- Contact Center
- Collection
- Compliance
---
