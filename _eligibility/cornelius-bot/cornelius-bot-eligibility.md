---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The beta is for individuals using their own accounts
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to enter into a contract.
    value: '18'
  restricted_uses:
  - summary: Illegal content
    text: store or process content that is illegal
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Access is by invitation, free of charge, and may be limited in numbers.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cornelius
provenance_date: '2026-11-09'
provider_name: Cornelius
provider_slug: cornelius-bot
slug: cornelius-bot-eligibility
source_date: '2026-11-09'
source_filename: cornelius-bot-eligibility.yml
source_heading: Eligibility
source_page: https://cornelius.bot/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cornelius\naid: cornelius-bot\nurl: https://cornelius.bot/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The beta is for individuals using their own accounts\nrestricted_uses:\n- summary: Illegal content\n  text: store or process content that is illegal\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Access is by invitation, free of charge, and may be limited in numbers.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into a contract.\n"
source_yaml_url: https://artifacts.apis.io/cornelius-bot/eligibility/cornelius-bot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Cornelius's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Personal Assistant
- Model Context Protocol
- Knowledge Graph
- Productivity
---
