---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  - text: in the case of an individual accepting this Agreement on such individual’s own behalf, such individual
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors barred
    text: Customer may not access the Software or Services if Customer is a direct competitor of Obot AI, except with Obot AI’s prior written consent.
  - summary: No monitoring of availability or performance
    text: Customer may not access the Software or Services for purposes of monitoring their availability, performance or functionality.
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
name: Obot
provenance_date: '2026-11-10'
provider_name: Obot
provider_slug: obot
slug: obot-eligibility
source_date: '2026-11-10'
source_filename: obot-eligibility.yml
source_heading: Eligibility
source_page: https://obot.ai/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Obot\naid: obot\nurl: https://obot.ai/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\n- type: individual\n  text: in the case of an individual accepting this Agreement on such individual’s own behalf, such individual\nrestricted_uses:\n- summary: Direct competitors barred\n  text: Customer may not access the Software or Services if Customer is a direct competitor of Obot\
  \ AI, except with\n    Obot AI’s prior written consent.\n- summary: No monitoring of availability or performance\n  text: Customer may not access the Software or Services for purposes of monitoring their availability, performance\n    or functionality.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/obot/eligibility/obot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Obot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- AI Agents
- MCP Gateway
- Open Source
- Agent Governance
- Access Control
- Developer Tools
---
