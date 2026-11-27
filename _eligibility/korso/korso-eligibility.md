---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and give an address that is yours.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and give an address that is yours.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: use the Site for anything unlawful.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We decide whom to invite and when, and we may stop offering access this way at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Korso
provenance_date: '2026-11-09'
provider_name: Korso
provider_slug: korso
slug: korso-eligibility
source_date: '2026-11-09'
source_filename: korso-eligibility.yml
source_heading: Eligibility
source_page: https://korsoai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Korso\naid: korso\nurl: https://korsoai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and give an address that is yours.\nrestricted_uses:\n- summary: Unlawful use\n  text: use the Site for anything unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We decide whom to invite and when, and we may stop offering access this way at any time.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and give an address that is yours.\n"
source_yaml_url: https://artifacts.apis.io/korso/eligibility/korso-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Korso's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- MCP
- Developer Tools
- Open Source
- Agent Coordination
- Y Combinator
---
