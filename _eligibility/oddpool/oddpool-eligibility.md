---
api_specs:
- filename: oddpool-feeds-asyncapi.yml
  format: yaml
  label: Oddpool WebSocket Feeds
  slug: oddpool-websocket-feeds
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/oddpool/asyncapi/oddpool-feeds-asyncapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No gambling or trading automation
    text: Use the Service for gambling, trading automation, or investment advice delivery.
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
name: Oddpool
provenance_date: '2026-11-10'
provider_name: Oddpool
provider_slug: oddpool
slug: oddpool-eligibility
source_date: '2026-11-10'
source_filename: oddpool-eligibility.yml
source_heading: Eligibility
source_page: https://www.oddpool.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oddpool\naid: oddpool\nurl: https://www.oddpool.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No gambling or trading automation\n  text: Use the Service for gambling, trading automation, or investment advice delivery.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/oddpool/eligibility/oddpool-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Oddpool's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Prediction Markets
- Market Data
- Financial Data
- Trading
- Fintech
- Data Aggregation
- WebSocket
- Historical Data
- Kalshi
- Polymarket
- Real-Time
---
