---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Services not available in jurisdictions listed in the “List of Prohibited Jurisdictions” (externally maintained, not listed on this page).
  entity_types:
  - text: You are at least 18 years of age and have the full capacity to accept these Terms
    type: individual
  minimum_age:
    text: You are at least 18 years of age and have the full capacity to accept these Terms
    value: '18'
  restricted_uses:
  - summary: Margin trading crime
    text: Users shall not use margin trading to commit any crime against the law of the country where you belong, reside, pay tax, carry out business activities, or any other activities.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Prior to using our API or API Service, you must verify your identity through an API Key.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CoinEx
provenance_date: '2026-11-09'
provider_name: CoinEx
provider_slug: coinex
slug: coinex-eligibility
source_date: '2026-11-09'
source_filename: coinex-eligibility.yml
source_heading: Eligibility
source_page: https://www.coinex.com/en/service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoinEx\naid: coinex\nurl: https://www.coinex.com/en/service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Services not available in jurisdictions listed in the “List of Prohibited Jurisdictions” (externally maintained,\n    not listed on this page).\nentity_types:\n- type: individual\n  text: You are at least 18 years of age and have the full capacity to accept these Terms\nrestricted_uses:\n- summary: Margin trading crime\n  text: Users shall not use margin trading to commit any crime against the law of the country where you belong,\n    reside, pay tax, carry out business activities,\
  \ or any other activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Prior to using our API or API Service, you must verify your identity through an API Key.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age and have the full capacity to accept these Terms\n"
source_yaml_url: https://artifacts.apis.io/coinex/eligibility/coinex-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from CoinEx's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Exchange
- Spot Trading
- Futures
- Perpetual Contracts
- Market Data
- WebSocket
- Finance
---
