---
api_specs:
- filename: wazirx-websocket-api-openapi.yml
  format: yaml
  label: WazirX WebSocket API
  slug: wazirx-websocket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wazirx/openapi/wazirx-websocket-api-openapi.yml
- filename: wazirx-account-api-openapi.yml
  format: yaml
  label: WazirX Account API
  slug: wazirx-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wazirx/openapi/wazirx-account-api-openapi.yml
- filename: wazirx-general-api-openapi.yml
  format: yaml
  label: WazirX General API
  slug: wazirx-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wazirx/openapi/wazirx-general-api-openapi.yml
- filename: wazirx-market-data-api-openapi.yml
  format: yaml
  label: WazirX Market Data API
  slug: wazirx-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wazirx/openapi/wazirx-market-data-api-openapi.yml
- filename: wazirx-sub-account-api-openapi.yml
  format: yaml
  label: WazirX Sub-Account API
  slug: wazirx-sub-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wazirx/openapi/wazirx-sub-account-api-openapi.yml
- filename: wazirx-trading-api-openapi.yml
  format: yaml
  label: WazirX Trading API
  slug: wazirx-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wazirx/openapi/wazirx-trading-api-openapi.yml
- filename: wazirx-wallet-api-openapi.yml
  format: yaml
  label: WazirX Wallet API
  slug: wazirx-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wazirx/openapi/wazirx-wallet-api-openapi.yml
- filename: wazirx-websocket-api-openapi.yml
  format: yaml
  label: WazirX WebSocket API
  slug: wazirx-websocket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wazirx/openapi/wazirx-websocket-api-openapi.yml
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
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: create an account with your email address and complete KYC verification using your PAN card and Aadhaar
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: WazirX
provenance_date: '2026-11-10'
provider_name: WazirX
provider_slug: wazirx
slug: wazirx-eligibility
source_date: '2026-11-10'
source_filename: wazirx-eligibility.yml
source_heading: Eligibility
source_page: https://wazirx.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WazirX\naid: wazirx\nurl: https://wazirx.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: create an account with your email address and complete KYC verification using your PAN card and Aadhaar\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wazirx/eligibility/wazirx-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from WazirX's own page on 2026-11-10.
synthetic: false
tags:
- Cryptocurrency
- Exchange
- Trading
- INR
- India
- Bitcoin
- WebSocket
- Market Data
---
