---
api_specs:
- filename: siftingio-asyncapi.yaml
  format: yaml
  label: SiftingIO Live Stream
  slug: siftingio-live-stream
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/siftingio/asyncapi/siftingio-asyncapi.yaml
- filename: siftingio-commodities-api-openapi.yml
  format: yaml
  label: SiftingIO Commodities API
  slug: siftingio-commodities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-commodities-api-openapi.yml
- filename: siftingio-convert-api-openapi.yml
  format: yaml
  label: SiftingIO Convert API
  slug: siftingio-convert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-convert-api-openapi.yml
- filename: siftingio-crypto-api-openapi.yml
  format: yaml
  label: SiftingIO Crypto API
  slug: siftingio-crypto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-crypto-api-openapi.yml
- filename: siftingio-dex-api-openapi.yml
  format: yaml
  label: SiftingIO DEX API
  slug: siftingio-dex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-dex-api-openapi.yml
- filename: siftingio-filers-api-openapi.yml
  format: yaml
  label: SiftingIO Filers API
  slug: siftingio-filers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-filers-api-openapi.yml
- filename: siftingio-forex-api-openapi.yml
  format: yaml
  label: SiftingIO Forex API
  slug: siftingio-forex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-forex-api-openapi.yml
- filename: siftingio-live-api-openapi.yml
  format: yaml
  label: SiftingIO Live API
  slug: siftingio-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-live-api-openapi.yml
- filename: siftingio-markets-api-openapi.yml
  format: yaml
  label: SiftingIO Markets API
  slug: siftingio-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-markets-api-openapi.yml
- filename: siftingio-signals-api-openapi.yml
  format: yaml
  label: SiftingIO Signals API
  slug: siftingio-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-signals-api-openapi.yml
- filename: siftingio-stocks-api-openapi.yml
  format: yaml
  label: SiftingIO Stocks API
  slug: siftingio-stocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-stocks-api-openapi.yml
- filename: siftingio-economic-calendar-api-openapi.yml
  format: yaml
  label: SiftingIO Economic Calendar API
  slug: siftingio-economic-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-economic-calendar-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: you are not located in, organized under the laws of, or ordinarily resident in any country or territory subject to comprehensive U.S. or applicable trade sanctions (including, as of the effective date, Cuba, Iran, North Korea, Syria, and the Crimea
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) and legally capable of entering into a binding contract.
    type: individual
  - text: If you are agreeing on behalf of an organization, you represent that you have authority to bind that organization
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: use the Service in connection with high-risk activities where failure or inaccuracy could lead to death, personal injury, or material environmental damage
  - summary: Fraud and market manipulation
    text: use the Service to facilitate fraud, market manipulation, money laundering, terrorist financing, or other unlawful conduct
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SiftingIO
provenance_date: '2026-11-10'
provider_name: SiftingIO
provider_slug: siftingio
slug: siftingio-eligibility
source_date: '2026-11-10'
source_filename: siftingio-eligibility.yml
source_heading: Eligibility
source_page: https://sifting.io/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SiftingIO\naid: siftingio\nurl: https://sifting.io/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: you are not located in, organized under the laws of, or ordinarily resident in any country or territory\n    subject to comprehensive U.S. or applicable trade sanctions (including, as of the effective date, Cuba, Iran,\n    North Korea, Syria, and the Crimea\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) and legally capable of entering\n    into a binding contract.\n\
  - type: business\n  text: If you are agreeing on behalf of an organization, you represent that you have authority to bind that organization\nrestricted_uses:\n- summary: High-risk activities\n  text: use the Service in connection with high-risk activities where failure or inaccuracy could lead to death,\n    personal injury, or material environmental damage\n- summary: Fraud and market manipulation\n  text: use the Service to facilitate fraud, market manipulation, money laundering, terrorist financing, or other\n    unlawful conduct\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/siftingio/eligibility/siftingio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from SiftingIO's own page on 2026-11-10.
synthetic: false
tags:
- Financial market data
- Stocks/equities
- Foreign Exchange
- Cryptocurrency
- DeFi/on-chain
- Commodities
- SEC Filings
- XBRL
- Fundamentals
- Fintech
- Quant/trading infrastructure
- Real-Time Streaming
- WebSocket
- FIX
- Financial Data
- Market Data
- Stocks
- DeFi
- Real-Time
- REST API
- MCP Server
- Agent-Native
---
