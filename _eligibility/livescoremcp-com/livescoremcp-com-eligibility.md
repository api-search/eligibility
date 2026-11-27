---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Commercial use requires a licence. Full MCP access, which lifts that limit and permits use in a commercial product, is $100 per month, billed monthly against a written agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use needs a licence
    text: Commercial use requires a licence.
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
name: LiveScore MCP
provenance_date: '2026-11-09'
provider_name: LiveScore MCP
provider_slug: livescoremcp-com
slug: livescoremcp-com-eligibility
source_date: '2026-11-09'
source_filename: livescoremcp-com-eligibility.yml
source_heading: Eligibility
source_page: https://livescoremcp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LiveScore MCP\naid: livescoremcp-com\nurl: https://livescoremcp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Commercial use requires a licence. Full MCP access, which lifts that limit and permits use in a commercial\n    product, is $100 per month, billed monthly against a written agreement.\nrestricted_uses:\n- summary: Commercial use needs a licence\n  text: Commercial use requires a licence.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/livescoremcp-com/eligibility/livescoremcp-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from LiveScore MCP's own page on 2026-11-09.
synthetic: false
tags:
- Football
- Live Scores
- MCP
- Artificial Intelligence
- Sports Data
---
