---
api_specs:
- filename: agent-api.yaml
  format: yaml
  label: callagent.pro Agent API
  slug: agent-api
  spec_type: OpenAPI
  url: https://www.callagent.pro/openapi/agent-api.yaml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have the legal capacity to enter into contracts to use our Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and have the legal capacity to enter into contracts to use our Service.
    value: '18'
  restricted_uses:
  - summary: Unsolicited marketing calls and TCPA violations
    text: Violate telemarketing laws or regulations (including TCPA, Do Not Call lists)
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
name: callagent.pro
provenance_date: '2026-11-09'
provider_name: callagent.pro
provider_slug: callagentpro
slug: callagentpro-eligibility
source_date: '2026-11-09'
source_filename: callagentpro-eligibility.yml
source_heading: Eligibility
source_page: https://www.callagent.pro/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: callagent.pro\naid: callagentpro\nurl: https://www.callagent.pro/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have the legal capacity to enter into contracts to use our Service.\nrestricted_uses:\n- summary: Unsolicited marketing calls and TCPA violations\n  text: Violate telemarketing laws or regulations (including TCPA, Do Not Call lists)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years\
  \ old and have the legal capacity to enter into contracts to use our Service.\n"
source_yaml_url: https://artifacts.apis.io/callagentpro/eligibility/callagentpro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from callagent.pro's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Voice
- Telephony
- Phone Agents
- SIP
- x402
- Call Automation
---
