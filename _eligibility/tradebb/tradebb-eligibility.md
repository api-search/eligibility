---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use our Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use our Service.
    value: '18'
  restricted_uses:
  - summary: No investment advice or signals
    text: No investment advice or trading signals are provided.
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
name: TradeBB
provenance_date: '2026-11-10'
provider_name: TradeBB
provider_slug: tradebb
slug: tradebb-eligibility
source_date: '2026-11-10'
source_filename: tradebb-eligibility.yml
source_heading: Eligibility
source_page: https://www.tradebb.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TradeBB\naid: tradebb\nurl: https://www.tradebb.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use our Service.\nrestricted_uses:\n- summary: No investment advice or signals\n  text: No investment advice or trading signals are provided.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our Service.\n"
source_yaml_url: https://artifacts.apis.io/tradebb/eligibility/tradebb-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from TradeBB's own page on 2026-11-10.
synthetic: false
tags:
- Trading Journal
- Trade Analytics
- Fintech
- TradingTools
- Stocks
- Options
- Futures
- Foreign Exchange
- Cryptocurrency
- CFD
- AI Assistant
- Llms.txt
---
