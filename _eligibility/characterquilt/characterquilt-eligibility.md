---
api_specs:
- filename: characterquilt-branding-api-openapi.yml
  format: yaml
  label: CharacterQuilt Branding API
  slug: characterquilt-branding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/characterquilt/openapi/characterquilt-branding-api-openapi.yml
- filename: characterquilt-discovery-api-openapi.yml
  format: yaml
  label: CharacterQuilt Discovery API
  slug: characterquilt-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/characterquilt/openapi/characterquilt-discovery-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: a U.S. embargoed country or region (currently the Crimea, Luhansk or Donetsk regions, Cuba, Iran, North Korea, Sudan or Syria)
  entity_types:
  - text: the entity referenced in the Order
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competition with Innabox
    text: use the Service for any use in competition with or with the intent to develop or compete with Innabox's Services
  - summary: Export restrictions
    text: Customer will not permit any Authorized User to access or use any Service in a U.S. embargoed country or region
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CharacterQuilt
provenance_date: '2026-11-09'
provider_name: CharacterQuilt
provider_slug: characterquilt
slug: characterquilt-eligibility
source_date: '2026-11-09'
source_filename: characterquilt-eligibility.yml
source_heading: Eligibility
source_page: https://www.characterquilt.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CharacterQuilt\naid: characterquilt\nurl: https://www.characterquilt.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: a U.S. embargoed country or region (currently the Crimea, Luhansk or Donetsk regions, Cuba, Iran, North\n    Korea, Sudan or Syria)\nentity_types:\n- type: business\n  text: the entity referenced in the Order\nrestricted_uses:\n- summary: Competition with Innabox\n  text: use the Service for any use in competition with or with the intent to develop or compete with Innabox's\n    Services\n- summary: Export restrictions\n\
  \  text: Customer will not permit any Authorized User to access or use any Service in a U.S. embargoed country or\n    region\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/characterquilt/eligibility/characterquilt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from CharacterQuilt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- Artificial Intelligence
- AI Agents
- Marketing Automation
- Campaign Management
- Brand Identity
- Computer Use Agents
- Y Combinator
- Data
- MCP
---
