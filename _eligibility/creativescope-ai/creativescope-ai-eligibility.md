---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Misuse or infringing or unlawful use
    text: (c) misuse the Service to infringe others' rights or violate applicable law
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
name: CreativeScope
provenance_date: '2026-11-09'
provider_name: CreativeScope
provider_slug: creativescope-ai
slug: creativescope-ai-eligibility
source_date: '2026-11-09'
source_filename: creativescope-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.creativescope.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CreativeScope\naid: creativescope-ai\nurl: https://www.creativescope.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract.\nrestricted_uses:\n- summary: Misuse or infringing or unlawful use\n  text: (c) misuse the Service to infringe others' rights or violate applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding\
  \ contract.\n"
source_yaml_url: https://artifacts.apis.io/creativescope-ai/eligibility/creativescope-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CreativeScope's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobile Games
- Advertising
- Ad Intelligence
- User Acquisition
- Creative Analytics
- MCP
- AI Agents
---
