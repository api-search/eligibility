---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old to use Rindler.
    value: '13'
  restricted_uses:
  - summary: Harm to identifiable people
    text: Use Rindler to facilitate harassment, intimate-imagery non-consensual collection, or other harm to identifiable people.
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
name: Rindler
provenance_date: '2026-11-10'
provider_name: Rindler
provider_slug: rindler
slug: rindler-eligibility
source_date: '2026-11-10'
source_filename: rindler-eligibility.yml
source_heading: Eligibility
source_page: https://rindler.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rindler\naid: rindler\nurl: https://rindler.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harm to identifiable people\n  text: Use Rindler to facilitate harassment, intimate-imagery non-consensual collection, or other harm to identifiable\n    people.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use Rindler.\n"
source_yaml_url: https://artifacts.apis.io/rindler/eligibility/rindler-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Rindler's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- AI Agents
- Browser Automation
- Structured Data
- Website to API
- Agent Tools
- Y Combinator
---
