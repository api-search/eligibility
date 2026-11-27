---
api_specs:
- filename: degenhedge-com-fees-api-openapi.yml
  format: yaml
  label: DegenHedge Fees API
  slug: degenhedge-com-fees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/degenhedge-com/openapi/degenhedge-com-fees-api-openapi.yml
- filename: degenhedge-com-market-data-api-openapi.yml
  format: yaml
  label: DegenHedge market data API
  slug: degenhedge-com-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/degenhedge-com/openapi/degenhedge-com-market-data-api-openapi.yml
- filename: degenhedge-com-record-api-openapi.yml
  format: yaml
  label: DegenHedge Record API
  slug: degenhedge-com-record-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/degenhedge-com/openapi/degenhedge-com-record-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for users in the United States.
  entity_types:
  - text: You must be at least 18 years old and of legal age to form a binding contract in your jurisdiction.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and of legal age to form a binding contract in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: No unlawful gambling
    text: use the Service unlawfully or to facilitate unlawful gambling
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
name: DegenHedge
provenance_date: '2026-11-09'
provider_name: DegenHedge
provider_slug: degenhedge-com
slug: degenhedge-com-eligibility
source_date: '2026-11-09'
source_filename: degenhedge-com-eligibility.yml
source_heading: Eligibility
source_page: https://degenhedge.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DegenHedge\naid: degenhedge-com\nurl: https://degenhedge.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for users in the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and of legal age to form a binding contract in your jurisdiction.\nrestricted_uses:\n- summary: No unlawful gambling\n  text: use the Service unlawfully or to facilitate unlawful gambling\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18\
  \ years old and of legal age to form a binding contract in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/degenhedge-com/eligibility/degenhedge-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from DegenHedge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Prediction Markets
- Kalshi
- Bitcoin
- Trading Signals
- Telegram
- Sports Betting
- MCP
- Market Data
---
