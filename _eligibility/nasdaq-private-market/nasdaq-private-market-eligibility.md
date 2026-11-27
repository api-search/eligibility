---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are an individual accessing the Platform in Your personal capacity as a participant in a liquidity program or auction or other event, Your access and use of the Platform is governed by these TOU.
    type: individual
  - text: 'If You are accepting these TOU on behalf of Your employer or another entity, You represent and warrant that: (x) You have full legal authority to bind Your employer, or the applicable entity'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Investor services limited to accredited investors
    text: NPM Investor Services are available only to
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
name: Nasdaq Private Market
provenance_date: '2026-11-10'
provider_name: Nasdaq Private Market
provider_slug: nasdaq-private-market
slug: nasdaq-private-market-eligibility
source_date: '2026-11-10'
source_filename: nasdaq-private-market-eligibility.yml
source_heading: Eligibility
source_page: https://www.nasdaqprivatemarket.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nasdaq Private Market\naid: nasdaq-private-market\nurl: https://www.nasdaqprivatemarket.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If You are an individual accessing the Platform in Your personal capacity as a participant in a liquidity\n    program or auction or other event, Your access and use of the Platform is governed by these TOU.\n- type: business\n  text: 'If You are accepting these TOU on behalf of Your employer or another entity, You represent and warrant\n    that: (x) You have full legal authority\
  \ to bind Your employer, or the applicable entity'\nrestricted_uses:\n- summary: Investor services limited to accredited investors\n  text: NPM Investor Services are available only to\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nasdaq-private-market/eligibility/nasdaq-private-market-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Nasdaq Private Market's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Private Markets
- Secondary Market
- Market Data
- Financial Services
- Valuation
- Pre-IPO Equity
- Capital Markets
---
