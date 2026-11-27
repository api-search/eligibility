---
api_specs:
- filename: opensea-account-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Account Endpoints API
  slug: opensea-account-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-account-endpoints-api-openapi.yml
- filename: opensea-analytics-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Analytics Endpoints API
  slug: opensea-analytics-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-analytics-endpoints-api-openapi.yml
- filename: opensea-auth-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Auth Endpoints API
  slug: opensea-auth-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-auth-endpoints-api-openapi.yml
- filename: opensea-chain-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Chain Endpoints API
  slug: opensea-chain-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-chain-endpoints-api-openapi.yml
- filename: opensea-collection-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Collection Endpoints API
  slug: opensea-collection-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-collection-endpoints-api-openapi.yml
- filename: opensea-contract-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Contract Endpoints API
  slug: opensea-contract-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-contract-endpoints-api-openapi.yml
- filename: opensea-drops-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Drops Endpoints API
  slug: opensea-drops-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-drops-endpoints-api-openapi.yml
- filename: opensea-listing-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Listing Endpoints API
  slug: opensea-listing-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-listing-endpoints-api-openapi.yml
- filename: opensea-nft-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea NFT Endpoints API
  slug: opensea-nft-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-nft-endpoints-api-openapi.yml
- filename: opensea-offer-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Offer Endpoints API
  slug: opensea-offer-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-offer-endpoints-api-openapi.yml
- filename: opensea-order-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Order Endpoints API
  slug: opensea-order-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-order-endpoints-api-openapi.yml
- filename: opensea-search-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Search Endpoints API
  slug: opensea-search-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-search-endpoints-api-openapi.yml
- filename: opensea-swap-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Swap Endpoints API
  slug: opensea-swap-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-swap-endpoints-api-openapi.yml
- filename: opensea-token-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Token Endpoints API
  slug: opensea-token-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-token-endpoints-api-openapi.yml
- filename: opensea-tool-endpoints-beta-api-openapi.yml
  format: yaml
  label: OpenSea Tool Endpoints [Beta] API
  slug: opensea-tool-endpoints-beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-tool-endpoints-beta-api-openapi.yml
- filename: opensea-transaction-endpoints-api-openapi.yml
  format: yaml
  label: OpenSea Transaction Endpoints API
  slug: opensea-transaction-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensea/openapi/opensea-transaction-endpoints-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'You agree not to use the Platform, or otherwise enable access to the Platform, if: You are located in, ordinarily resident in, or organized under the laws of a U.S.-sanctioned country.'
  entity_types:
  - text: Users must be at least 18 years old to use the Platform.
    type: individual
  - text: 'If you are using the Platform on behalf of an entity, such as a company or other organization, then you represent and warrant that: You are authorized to bind the entity to these Terms.'
    type: business
  minimum_age:
    text: Users must be at least 18 years old to use the Platform.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons or countries
    text: You are subject to sanctions imposed by the U.S. Government, any other government, or the United Nations.
  - summary: Automated access without authorization
    text: Not to employ automated tools (e.g., scrapers, bots, crawlers) to access, extract, or manipulate Platform data without authorization.
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
name: OpenSea
provenance_date: '2026-11-10'
provider_name: OpenSea
provider_slug: opensea
slug: opensea-eligibility
source_date: '2026-11-10'
source_filename: opensea-eligibility.yml
source_heading: Eligibility
source_page: https://opensea.io/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenSea\naid: opensea\nurl: https://opensea.io/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'You agree not to use the Platform, or otherwise enable access to the Platform, if: You are located in,\n    ordinarily resident in, or organized under the laws of a U.S.-sanctioned country.'\nentity_types:\n- type: individual\n  text: Users must be at least 18 years old to use the Platform.\n- type: business\n  text: 'If you are using the Platform on behalf of an entity, such as a company or other organization, then you\n    represent and warrant that: You are authorized to bind the\
  \ entity to these Terms.'\nrestricted_uses:\n- summary: Sanctioned persons or countries\n  text: You are subject to sanctions imposed by the U.S. Government, any other government, or the United Nations.\n- summary: Automated access without authorization\n  text: Not to employ automated tools (e.g., scrapers, bots, crawlers) to access, extract, or manipulate Platform\n    data without authorization.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users must be at least 18 years old to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/opensea/eligibility/opensea-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from OpenSea's own page on 2026-11-10.
synthetic: false
tags:
- NFT
- Marketplace
- Web3
- Blockchain
- Trading
- Digital Assets
- A2A
- Ethereum
---
