---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Basic and Investor plans are strictly for personal use unless explicitly stated otherwise.
    type: individual
  - text: Personal use plans can’t be used by any business even internally without a written approval.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal use plans
    text: Our Basic and Investor plans are strictly for personal use unless explicitly stated otherwise.
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
name: Mboum
provenance_date: '2026-11-10'
provider_name: Mboum
provider_slug: mboum
slug: mboum-eligibility
source_date: '2026-11-10'
source_filename: mboum-eligibility.yml
source_heading: Eligibility
source_page: https://mboum.com/pages/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mboum\naid: mboum\nurl: https://mboum.com/pages/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Our Basic and Investor plans are strictly for personal use unless explicitly stated otherwise.\n- type: business\n  text: Personal use plans can’t be used by any business even internally without a written approval.\nrestricted_uses:\n- summary: Personal use plans\n  text: Our Basic and Investor plans are strictly for personal use unless explicitly stated otherwise.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mboum/eligibility/mboum-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Mboum's own page on 2026-11-10.
synthetic: false
tags:
- Stocks
- Stock Market
- Options
- options market
- Trading
- Quotes
- Market Data
- Technical Indicators
- SEC Filings
- Insider Trading
- IPO
- Dividends
- Earnings
- Historical Data
- Screener
- Cryptocurrency
---
