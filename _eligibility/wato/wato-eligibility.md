---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using Wato on behalf of a company or other organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Expert advice substitution
    text: use Wato outputs as a substitute for professional legal, medical, financial, security, or other expert advice without appropriate review
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
name: Wato
provenance_date: '2026-11-10'
provider_name: Wato
provider_slug: wato
slug: wato-eligibility
source_date: '2026-11-10'
source_filename: wato-eligibility.yml
source_heading: Eligibility
source_page: https://www.watolabs.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wato\naid: wato\nurl: https://www.watolabs.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using Wato on behalf of a company or other organization, you represent that you have authority\n    to bind that organization to these Terms.\nrestricted_uses:\n- summary: Expert advice substitution\n  text: use Wato outputs as a substitute for professional legal, medical, financial, security, or other expert advice\n    without appropriate review\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wato/eligibility/wato-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Wato's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- AI Agents
- Agent Governance
- Team Memory
- Connectors
- Agent Skills
- Automation
- Developer Tools
- Y Combinator
---
