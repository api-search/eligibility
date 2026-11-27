---
api_specs:
- filename: blocklottos-com-advertising-api-openapi.yml
  format: yaml
  label: Block Lottos Advertising API
  slug: blocklottos-com-advertising-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blocklottos-com/openapi/blocklottos-com-advertising-api-openapi.yml
- filename: blocklottos-com-affiliate-api-openapi.yml
  format: yaml
  label: Block Lottos Affiliate API
  slug: blocklottos-com-affiliate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blocklottos-com/openapi/blocklottos-com-affiliate-api-openapi.yml
- filename: blocklottos-com-agents-api-openapi.yml
  format: yaml
  label: Block Lottos Agents API
  slug: blocklottos-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blocklottos-com/openapi/blocklottos-com-agents-api-openapi.yml
- filename: blocklottos-com-lottery-api-openapi.yml
  format: yaml
  label: Block Lottos Lottery API
  slug: blocklottos-com-lottery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blocklottos-com/openapi/blocklottos-com-lottery-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Block Lottos does not operate in jurisdictions where online lotteries are prohibited.
  entity_types:
  - text: You must be at least 18 years of age (or the legal age for gambling in your jurisdiction) to use Block Lottos.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age (or the legal age for gambling in your jurisdiction) to use Block Lottos.
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
name: Block Lottos
provenance_date: '2026-11-09'
provider_name: Block Lottos
provider_slug: blocklottos-com
slug: blocklottos-com-eligibility
source_date: '2026-11-09'
source_filename: blocklottos-com-eligibility.yml
source_heading: Eligibility
source_page: https://blocklottos.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Block Lottos\naid: blocklottos-com\nurl: https://blocklottos.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Block Lottos does not operate in jurisdictions where online lotteries are prohibited.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age (or the legal age for gambling in your jurisdiction) to use Block Lottos.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the legal age for gambling in your jurisdiction)\
  \ to use Block Lottos.\n"
source_yaml_url: https://artifacts.apis.io/blocklottos-com/eligibility/blocklottos-com-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Block Lottos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Lottery
- Blockchain
- Web3
- Gaming
- Cryptocurrency
- Advertising
- Affiliate Marketing
- AI Agents
- Base
- Polygon
- USDC
- Smart Contracts
- A2A
---
