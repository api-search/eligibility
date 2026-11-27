---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Client (the counterparty ordering [24]7’s platform services)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No third-party access without consent
    text: Client shall not grant access to the Platform, including without limitation the Admin Console, to any third party, especially a direct competitor of [24]7, without [24]7’s prior written consent.
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
name: '[24]7.ai'
provenance_date: '2026-11-09'
provider_name: '[24]7.ai'
provider_slug: 247-ai
slug: 247-ai-eligibility
source_date: '2026-11-09'
source_filename: 247-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.247.ai/legal/platform-service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: '[24]7.ai'\naid: 247-ai\nurl: https://www.247.ai/legal/platform-service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Client (the counterparty ordering [24]7’s platform services)\nrestricted_uses:\n- summary: No third-party access without consent\n  text: Client shall not grant access to the Platform, including without limitation the Admin Console, to any third\n    party, especially a direct competitor of [24]7, without [24]7’s prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/247-ai/eligibility/247-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from [24]7.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Experience
- Conversational AI
- Contact Center
- Customer Service
- Chatbots
- CCaaS
- Artificial Intelligence
- Interaction Analytics
- Business Process Outsourcing
---
