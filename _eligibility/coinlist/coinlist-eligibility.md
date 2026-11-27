---
api_specs:
- filename: coinlist-kyc-api-openapi.yml
  format: yaml
  label: CoinList KYC API
  slug: coinlist-kyc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinlist/openapi/coinlist-kyc-api-openapi.yml
- filename: coinlist-offers-api-openapi.yml
  format: yaml
  label: CoinList Offers API
  slug: coinlist-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinlist/openapi/coinlist-offers-api-openapi.yml
- filename: coinlist-participations-api-openapi.yml
  format: yaml
  label: CoinList Participations API
  slug: coinlist-participations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinlist/openapi/coinlist-participations-api-openapi.yml
- filename: coinlist-pii-api-openapi.yml
  format: yaml
  label: CoinList Pii API
  slug: coinlist-pii-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinlist/openapi/coinlist-pii-api-openapi.yml
- filename: coinlist-requirements-api-openapi.yml
  format: yaml
  label: CoinList Requirements API
  slug: coinlist-requirements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinlist/openapi/coinlist-requirements-api-openapi.yml
- filename: coinlist-swap-api-openapi.yml
  format: yaml
  label: CoinList Swap API
  slug: coinlist-swap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinlist/openapi/coinlist-swap-api-openapi.yml
- filename: coinlist-token-api-openapi.yml
  format: yaml
  label: CoinList Token API
  slug: coinlist-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinlist/openapi/coinlist-token-api-openapi.yml
- filename: coinlist-wallet-api-openapi.yml
  format: yaml
  label: CoinList Wallet API
  slug: coinlist-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinlist/openapi/coinlist-wallet-api-openapi.yml
- filename: coinlist-wallet-ownership-api-openapi.yml
  format: yaml
  label: CoinList Wallet Ownership API
  slug: coinlist-wallet-ownership-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinlist/openapi/coinlist-wallet-ownership-api-openapi.yml
- filename: coinlist-oauth-api-openapi.yml
  format: yaml
  label: CoinList O Auth API
  slug: coinlist-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinlist/openapi/coinlist-oauth-api-openapi.yml
- filename: coinlist-ondo-api-openapi.yml
  format: yaml
  label: CoinList Ondo API
  slug: coinlist-ondo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinlist/openapi/coinlist-ondo-api-openapi.yml
- filename: coinlist-document-submissions-api-openapi.yml
  format: yaml
  label: CoinList document submissions API
  slug: coinlist-document-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinlist/openapi/coinlist-document-submissions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To be eligible to use our Site and Services you must be at least 18 years old and meet other threshold criteria as determined by CoinList in its sole discretion.
    type: individual
  - text: If you access or use the Services on behalf of an entity, platform, issuer, or other organization, you represent and warrant that you are authorized to bind that entity or organization to this Agreement
    type: business
  minimum_age:
    text: you must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Prohibited businesses and uses
    text: you agree and represent that you will not engage in any Prohibited Business or Prohibited Use, as defined in Appendix 1 herein.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: During registration of your CoinList Account, you agree to provide us with any information we may request for the purposes of identity verification
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CoinList
provenance_date: '2026-11-09'
provider_name: CoinList
provider_slug: coinlist
slug: coinlist-eligibility
source_date: '2026-11-09'
source_filename: coinlist-eligibility.yml
source_heading: Eligibility
source_page: https://coinlist.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoinList\naid: coinlist\nurl: https://coinlist.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To be eligible to use our Site and Services you must be at least 18 years old and meet other threshold criteria\n    as determined by CoinList in its sole discretion.\n- type: business\n  text: If you access or use the Services on behalf of an entity, platform, issuer, or other organization, you represent\n    and warrant that you are authorized to bind that entity or organization to this Agreement\nrestricted_uses:\n\
  - summary: Prohibited businesses and uses\n  text: you agree and represent that you will not engage in any Prohibited Business or Prohibited Use, as defined\n    in Appendix 1 herein.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: During registration of your CoinList Account, you agree to provide us with any information we may request\n    for the purposes of identity verification\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/coinlist/eligibility/coinlist-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from CoinList's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Cryptocurrency
- Token Sales
- Tokenized Equities
- KYC
- OAuth
- Blockchain
- Digital Assets
- Embedded Finance
- Authentication
---
