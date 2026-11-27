---
api_specs:
- filename: 9bot-com-br-discovery-api-openapi.yml
  format: yaml
  label: 9bot Discovery API
  slug: 9bot-com-br-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/9bot-com-br/openapi/9bot-com-br-discovery-api-openapi.yml
- filename: 9bot-com-br-health-api-openapi.yml
  format: yaml
  label: 9bot Health API
  slug: 9bot-com-br-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/9bot-com-br/openapi/9bot-com-br-health-api-openapi.yml
- filename: 9bot-com-br-mcp-api-openapi.yml
  format: yaml
  label: 9bot MCP API
  slug: 9bot-com-br-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/9bot-com-br/openapi/9bot-com-br-mcp-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you act for a company, group, or organization, you represent that you have authority to bind it.
    type: business
  minimum_age:
    text: Minors may use 9bot only where permitted by law and with any required authorization and supervision.
    value: null
  restricted_uses:
  - summary: Minors
    text: Minors may use 9bot only where permitted by law and with any required authorization and supervision.
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
name: 9bot
provenance_date: '2026-11-09'
provider_name: 9bot
provider_slug: 9bot-com-br
slug: 9bot-com-br-eligibility
source_date: '2026-11-09'
source_filename: 9bot-com-br-eligibility.yml
source_heading: Eligibility
source_page: https://9bot.com.br/en/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 9bot\naid: 9bot-com-br\nurl: https://9bot.com.br/en/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you act for a company, group, or organization, you represent that you have authority to bind it.\nrestricted_uses:\n- summary: Minors\n  text: Minors may use 9bot only where permitted by law and with any required authorization and supervision.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Minors may use 9bot only where permitted by law and with any\
  \ required authorization and supervision.\n"
source_yaml_url: https://artifacts.apis.io/9bot-com-br/eligibility/9bot-com-br-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from 9bot's own page on 2026-11-09.
synthetic: false
tags:
- WhatsApp
- Automation
- Bot
- Messaging
- Integration
---
