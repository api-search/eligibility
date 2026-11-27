---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 16+ and provide accurate account information.
    type: individual
  minimum_age:
    text: You must be 16+ and provide accurate account information.
    value: '16'
  restricted_uses:
  - summary: Unlawful material
    text: don't use the service to store or distribute unlawful material.
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
name: chat-recall
provenance_date: '2026-11-09'
provider_name: chat-recall
provider_slug: chatrecall-dev
slug: chatrecall-dev-eligibility
source_date: '2026-11-09'
source_filename: chatrecall-dev-eligibility.yml
source_heading: Eligibility
source_page: https://chatrecall.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: chat-recall\naid: chatrecall-dev\nurl: https://chatrecall.dev/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 16+ and provide accurate account information.\nrestricted_uses:\n- summary: Unlawful material\n  text: don't use the service to store or distribute unlawful material.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be 16+ and provide accurate account information.\n"
source_yaml_url: https://artifacts.apis.io/chatrecall-dev/eligibility/chatrecall-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from chat-recall's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Coding Assistants
- Developer Tools
- MCP
- Memory
- Search
- Secret Scanning
- Self-Hosted
- Open Source
---
