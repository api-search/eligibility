---
api_specs:
- filename: botx402-io-agent-api-openapi.yml
  format: yaml
  label: BotX402 Agent API
  slug: botx402-io-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botx402-io/openapi/botx402-io-agent-api-openapi.yml
- filename: botx402-io-base-address-balance-api-openapi.yml
  format: yaml
  label: BotX402 Base Address Balance API
  slug: botx402-io-base-address-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botx402-io/openapi/botx402-io-base-address-balance-api-openapi.yml
- filename: botx402-io-well-known-api-openapi.yml
  format: yaml
  label: BotX402 .well Known API
  slug: botx402-io-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botx402-io/openapi/botx402-io-well-known-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you're using a bot for an organisation, you confirm you have authority to bind that organisation to these terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old.
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
name: BotX402
provenance_date: '2026-11-09'
provider_name: BotX402
provider_slug: botx402-io
slug: botx402-io-eligibility
source_date: '2026-11-09'
source_filename: botx402-io-eligibility.yml
source_heading: Eligibility
source_page: https://botx402.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BotX402\naid: botx402-io\nurl: https://botx402.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you're using a bot for an organisation, you confirm you have authority to bind that organisation to these\n    terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/botx402-io/eligibility/botx402-io-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from BotX402's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pay-per-use
- Bots
- Business
- Automation
- SaaS-alternative
---
