---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years of age to use the Service. If you are between 13 and 18, you may only use the Service under the supervision and consent of a parent or guardian.
    type: individual
  minimum_age:
    text: You must be at least 13 years of age to use the Service.
    value: '13'
  restricted_uses:
  - summary: Group chats with minors
    text: do not add Tomo to, or ask Tomo to start, a Group Chat that includes anyone under 13, or anyone under 18 who does not have a parent or guardian's permission to use the Service.
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
name: Tomo
provenance_date: '2026-11-10'
provider_name: Tomo
provider_slug: tomo
slug: tomo-eligibility
source_date: '2026-11-10'
source_filename: tomo-eligibility.yml
source_heading: Eligibility
source_page: https://www.tomo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tomo\naid: tomo\nurl: https://www.tomo.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age to use the Service. If you are between 13 and 18, you may only use\n    the Service under the supervision and consent of a parent or guardian.\nrestricted_uses:\n- summary: Group chats with minors\n  text: do not add Tomo to, or ask Tomo to start, a Group Chat that includes anyone under 13, or anyone under 18\n    who does not have a parent or guardian's permission to use the Service.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/tomo/eligibility/tomo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Tomo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Apps
- Personal Assistant
- Conversational AI
- Consumer AI
- Messaging
- SMS
- Artificial Intelligence
---
