---
api_specs:
- filename: bommel-bot-agent-api-openapi.yml
  format: yaml
  label: bommel-bot Agent API
  slug: bommel-bot-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bommel-bot/openapi/bommel-bot-agent-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Fjord LLC makes no representation that the Service is appropriate or available for use in locations outside the United States.
  entity_types:
  - text: To use the Service, you must be at least 18 years of age and have the legal capacity to enter into binding contracts in your jurisdiction.
    type: individual
  minimum_age:
    text: You are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unauthorized commercial purposes
    text: Use of the Service for unauthorized commercial purposes
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
name: bommel-bot
provenance_date: '2026-11-09'
provider_name: bommel-bot
provider_slug: bommel-bot
slug: bommel-bot-eligibility
source_date: '2026-11-09'
source_filename: bommel-bot-eligibility.yml
source_heading: Eligibility
source_page: https://bommel.bot/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: bommel-bot\naid: bommel-bot\nurl: https://bommel.bot/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Fjord LLC makes no representation that the Service is appropriate or available for use in locations outside\n    the United States.\nentity_types:\n- type: individual\n  text: To use the Service, you must be at least 18 years of age and have the legal capacity to enter into binding\n    contracts in your jurisdiction.\nrestricted_uses:\n- summary: Unauthorized commercial purposes\n  text: Use of the Service for unauthorized commercial purposes\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/bommel-bot/eligibility/bommel-bot-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from bommel-bot's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
