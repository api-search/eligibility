---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: 'US phone numbers only: Our service is designed for US mobile carriers under A2P 10DLC regulations'
  entity_types:
  - text: This program is for guests with an active or upcoming stay, however you booked
    type: individual
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
name: Lance
provenance_date: '2026-11-09'
provider_name: Lance
provider_slug: lance
slug: lance-eligibility
source_date: '2026-11-09'
source_filename: lance-eligibility.yml
source_heading: Eligibility
source_page: https://www.lance.live/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lance\naid: lance\nurl: https://www.lance.live/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: 'US phone numbers only: Our service is designed for US mobile carriers under A2P 10DLC regulations'\nentity_types:\n- type: individual\n  text: This program is for guests with an active or upcoming stay, however you booked\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lance/eligibility/lance-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Lance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Hospitality
- Hotels
- Hotel Operations
- Voice AI
- Customer Service
- Computer Use Agents
- Software-as-a-Service
---
