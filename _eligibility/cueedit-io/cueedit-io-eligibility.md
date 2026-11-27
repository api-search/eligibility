---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must provide accurate and complete information when creating an account.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Harmful content
    text: Your content does not contain illegal, harmful, or objectionable material.
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
name: CueEditio
provenance_date: '2026-11-09'
provider_name: CueEditio
provider_slug: cueedit-io
slug: cueedit-io-eligibility
source_date: '2026-11-09'
source_filename: cueedit-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.cueedit.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CueEditio\naid: cueedit-io\nurl: https://www.cueedit.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must provide accurate and complete information when creating an account.\nrestricted_uses:\n- summary: Harmful content\n  text: Your content does not contain illegal, harmful, or objectionable material.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cueedit-io/eligibility/cueedit-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CueEditio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video Editing
- Artificial Intelligence
- Social Media
- Scheduling
- Instagram
- Direct Messaging
- Marketing
- MCP
- AI Agents
---
