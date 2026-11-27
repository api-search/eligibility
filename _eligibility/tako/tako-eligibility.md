---
api_specs:
- filename: tako-agent-api-openapi.yml
  format: yaml
  label: Tako Agent API
  slug: tako-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tako/openapi/tako-agent-api-openapi.yml
- filename: tako-tako-api-openapi.yml
  format: yaml
  label: Tako API
  slug: tako-tako-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tako/openapi/tako-tako-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity and its affiliates to this TOS
    type: business
  minimum_age:
    text: you are 18 or older.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You may not export or re-export the Service in violation of U.S. export laws.
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
name: Tako
provenance_date: '2026-11-10'
provider_name: Tako
provider_slug: tako
slug: tako-eligibility
source_date: '2026-11-10'
source_filename: tako-eligibility.yml
source_heading: Eligibility
source_page: https://tako.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tako\naid: tako\nurl: https://tako.com/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such entity and its affiliates to this TOS\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not export or re-export the Service in violation of U.S. export laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you\
  \ are 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/tako/eligibility/tako-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Tako's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data
- Search
- Answer Engine
- Financial Data
- Knowledge Graph
- Agents
- MCP
- Data Visualization
---
