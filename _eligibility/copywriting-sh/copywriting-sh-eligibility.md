---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in, and are not a national or resident of, any country or region subject to comprehensive U.S. sanctions or export restrictions
  entity_types:
  - text: You must be at least 18 years old and able to form a legally binding contract to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to form a legally binding contract to use the Service.
    value: '18'
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
name: Copywriting MCP
provenance_date: '2026-11-09'
provider_name: Copywriting MCP
provider_slug: copywriting-sh
slug: copywriting-sh-eligibility
source_date: '2026-11-09'
source_filename: copywriting-sh-eligibility.yml
source_heading: Eligibility
source_page: https://copywriting.sh/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Copywriting MCP\naid: copywriting-sh\nurl: https://copywriting.sh/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in, and are not a national or resident of, any country or region subject to comprehensive\n    U.S. sanctions or export restrictions\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a legally binding contract to use the Service.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\
  \ and able to form a legally binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/copywriting-sh/eligibility/copywriting-sh-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Copywriting MCP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Copywriting
- MCP
- Model Context Protocol
- AI Agents
- Knowledge Base
- Marketing
- Content Writing
---
