---
api_specs:
- filename: maicoin-convert-api-openapi.yml
  format: yaml
  label: MaiCoin Convert API
  slug: maicoin-convert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maicoin/openapi/maicoin-convert-api-openapi.yml
- filename: maicoin-order-api-openapi.yml
  format: yaml
  label: MaiCoin Order API
  slug: maicoin-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maicoin/openapi/maicoin-order-api-openapi.yml
- filename: maicoin-public-api-openapi.yml
  format: yaml
  label: MaiCoin Public API
  slug: maicoin-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maicoin/openapi/maicoin-public-api-openapi.yml
- filename: maicoin-trade-api-openapi.yml
  format: yaml
  label: MaiCoin Trade API
  slug: maicoin-trade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maicoin/openapi/maicoin-trade-api-openapi.yml
- filename: maicoin-transaction-api-openapi.yml
  format: yaml
  label: MaiCoin Transaction API
  slug: maicoin-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maicoin/openapi/maicoin-transaction-api-openapi.yml
- filename: maicoin-user-api-openapi.yml
  format: yaml
  label: MaiCoin User API
  slug: maicoin-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maicoin/openapi/maicoin-user-api-openapi.yml
- filename: maicoin-wallet-api-openapi.yml
  format: yaml
  label: MaiCoin Wallet API
  slug: maicoin-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maicoin/openapi/maicoin-wallet-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: According to your citizenship and the regulations of the countries or areas that you are at (including but not limited to Japan, United States and European Economic Area), you may not be able to use part or all of the functions of the Site
  entity_types:
  - text: You must have attained the age of majority and must be of full legal capacity under the laws applicable to you to access and use MAX Exchange Services and this Site.
    type: individual
  - text: 包含所有自然人用戶及法人用戶
    type: business
  minimum_age:
    text: You must have attained the age of majority and must be of full legal capacity
    value: age of majority
  restricted_uses:
  - summary: Funds usable only for trading on MAX Exchange
    text: Funds in your MAX Exchange Account can be used only to trade on MAX Exchange.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: The Company implements certain KYC verifications procedures during your activation and subsequent access to or use of MAX Exchange Services and this Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MaiCoin
provenance_date: '2026-11-10'
provider_name: MaiCoin
provider_slug: maicoin
slug: maicoin-eligibility
source_date: '2026-11-10'
source_filename: maicoin-eligibility.yml
source_heading: Eligibility
source_page: https://assets.maicoin.com/max/MAX-Terms-of-Use.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MaiCoin\naid: maicoin\nurl: https://assets.maicoin.com/max/MAX-Terms-of-Use.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: According to your citizenship and the regulations of the countries or areas that you are at (including but\n    not limited to Japan, United States and European Economic Area), you may not be able to use part or all of the\n    functions of the Site\nentity_types:\n- type: individual\n  text: You must have attained the age of majority and must be of full legal capacity under the laws applicable\n    to you to access and use MAX Exchange\
  \ Services and this Site.\n- type: business\n  text: 包含所有自然人用戶及法人用戶\nrestricted_uses:\n- summary: Funds usable only for trading on MAX Exchange\n  text: Funds in your MAX Exchange Account can be used only to trade on MAX Exchange.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: The Company implements certain KYC verifications procedures during your activation and subsequent access\n    to or use of MAX Exchange Services and this Site.\nminimum_age:\n  value: age of majority\n  text: You must have attained the age of majority and must be of full legal capacity\n"
source_yaml_url: https://artifacts.apis.io/maicoin/eligibility/maicoin-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from MaiCoin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Digital Assets
- Exchange
- Trading
- Financial Services
- Market Data
- Blockchain
- Taiwan
- WebSocket
- Real-Time
---
