---
api_specs:
- filename: debank-account-api-openapi.yml
  format: yaml
  label: DeBank Account API
  slug: debank-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debank/openapi/debank-account-api-openapi.yml
- filename: debank-app-protocol-api-openapi.yml
  format: yaml
  label: DeBank App Protocol API
  slug: debank-app-protocol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debank/openapi/debank-app-protocol-api-openapi.yml
- filename: debank-chain-api-openapi.yml
  format: yaml
  label: DeBank Chain API
  slug: debank-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debank/openapi/debank-chain-api-openapi.yml
- filename: debank-cloud-api-openapi.yml
  format: yaml
  label: DeBank Cloud API
  slug: debank-cloud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debank/openapi/debank-cloud-api-openapi.yml
- filename: debank-official-api-openapi.yml
  format: yaml
  label: DeBank Official API
  slug: debank-official-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debank/openapi/debank-official-api-openapi.yml
- filename: debank-pool-api-openapi.yml
  format: yaml
  label: DeBank Pool API
  slug: debank-pool-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debank/openapi/debank-pool-api-openapi.yml
- filename: debank-protocol-api-openapi.yml
  format: yaml
  label: DeBank Protocol API
  slug: debank-protocol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debank/openapi/debank-protocol-api-openapi.yml
- filename: debank-token-api-openapi.yml
  format: yaml
  label: DeBank Token API
  slug: debank-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debank/openapi/debank-token-api-openapi.yml
- filename: debank-user-api-openapi.yml
  format: yaml
  label: DeBank User API
  slug: debank-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debank/openapi/debank-user-api-openapi.yml
- filename: debank-wallet-api-openapi.yml
  format: yaml
  label: DeBank Wallet API
  slug: debank-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debank/openapi/debank-wallet-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are entering into or accepting these terms on behalf of a legal entity, you represent and warrant that you have the right, authority and capacity to bind such entity and its affiliates to these terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent or unlawful use
    text: Subscriber shall not use the Services to store, transmit for fraudulent purposes or in violation of applicable laws and governmental regulations;
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
name: DeBank
provenance_date: '2026-11-09'
provider_name: DeBank
provider_slug: debank
slug: debank-eligibility
source_date: '2026-11-09'
source_filename: debank-eligibility.yml
source_heading: Eligibility
source_page: https://docs.cloud.debank.com/en/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DeBank\naid: debank\nurl: https://docs.cloud.debank.com/en/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you are entering into or accepting these terms on behalf of a legal entity, you represent and warrant\n    that you have the right, authority and capacity to bind such entity and its affiliates to these terms\nrestricted_uses:\n- summary: Fraudulent or unlawful use\n  text: Subscriber shall not use the Services to store, transmit for fraudulent purposes or in violation of applicable\n    laws and governmental\
  \ regulations;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/debank/eligibility/debank-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from DeBank's own page on 2026-11-09.
synthetic: false
tags:
- Web3
- DeFi
- Blockchain
- Cryptocurrency
- Portfolio Tracking
- On-Chain Data
- Wallets
- Token Data
- NFT
- Ethereum
- OAuth
- Market Data
- Authentication
---
