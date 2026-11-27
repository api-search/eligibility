---
api_specs:
- filename: legendtrade-ws-asyncapi.yml
  format: yaml
  label: Legend WebSocket API
  slug: websocket
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/legendtrade/asyncapi/legendtrade-ws-asyncapi.yml
- filename: legendtrade-health-api-openapi.yml
  format: yaml
  label: LegendTrade Health API
  slug: legendtrade-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/legendtrade/openapi/legendtrade-health-api-openapi.yml
- filename: legendtrade-info-api-openapi.yml
  format: yaml
  label: LegendTrade Info API
  slug: legendtrade-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/legendtrade/openapi/legendtrade-info-api-openapi.yml
- filename: legendtrade-market-data-api-openapi.yml
  format: yaml
  label: LegendTrade Market Data API
  slug: legendtrade-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/legendtrade/openapi/legendtrade-market-data-api-openapi.yml
- filename: legendtrade-wallets-api-openapi.yml
  format: yaml
  label: LegendTrade Wallets API
  slug: legendtrade-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/legendtrade/openapi/legendtrade-wallets-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - US
    - CU
    - IR
    - KP
    - SY
    - MM
    served: []
    text: such as the United States of America and its territories, Cuba, Iran, North Korea, Syria, the Crimea, Donetsk, and Luhansk regions of Ukraine, Myanmar
  entity_types:
  - text: '"Person" includes, but is not limited to, any individual, corporation, partnership, limited liability company, association, trust, or other entity or organization.'
    type: business
  minimum_age:
    text: be at least eighteen (18) years of age (or the age of majority in their jurisdiction, whichever is greater)
    value: '18'
  restricted_uses:
  - summary: Restricted Persons and Territories
    text: Restricted Persons must not use Transaction Features.
  - summary: Where law prohibits
    text: Users must not use Transaction Features where applicable law prohibits their use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Company reserves the right, at any time and in its sole discretion, to require Users to provide information and documentation for the purpose of identity verification, jurisdictional compliance, or anti-money laundering screening.
excluded_countries:
- US
- CU
- IR
- KP
- SY
- MM
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LegendTrade
provenance_date: '2026-11-09'
provider_name: LegendTrade
provider_slug: legendtrade
slug: legendtrade-eligibility
source_date: '2026-11-09'
source_filename: legendtrade-eligibility.yml
source_heading: Eligibility
source_page: https://www.legend.trade/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LegendTrade\naid: legendtrade\nurl: https://www.legend.trade/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  - CU\n  - IR\n  - KP\n  - SY\n  - MM\n  text: such as the United States of America and its territories, Cuba, Iran, North Korea, Syria, the Crimea, Donetsk,\n    and Luhansk regions of Ukraine, Myanmar\nentity_types:\n- type: business\n  text: '\"Person\" includes, but is not limited to, any individual, corporation, partnership, limited liability company,\n    association, trust, or other entity or organization.'\nrestricted_uses:\n- summary: Restricted Persons and Territories\n\
  \  text: Restricted Persons must not use Transaction Features.\n- summary: Where law prohibits\n  text: Users must not use Transaction Features where applicable law prohibits their use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Company reserves the right, at any time and in its sole discretion, to require Users to provide information\n    and documentation for the purpose of identity verification, jurisdictional compliance, or anti-money laundering\n    screening.\nminimum_age:\n  value: '18'\n  text: be at least eighteen (18) years of age (or the age of majority in their jurisdiction, whichever is greater)\n"
source_yaml_url: https://artifacts.apis.io/legendtrade/eligibility/legendtrade-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from LegendTrade's own page on 2026-11-09.
synthetic: false
tags:
- Company
- DeFi
- Trading
- Cryptocurrency
- Perpetual Futures
- Social Trading
- Copy Trading
- Market Data
- Hyperliquid
- WebSocket
- Real-Time
---
