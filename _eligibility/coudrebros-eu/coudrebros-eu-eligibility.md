---
api_specs:
- filename: coudrebros-eu-auth-api-openapi.yml
  format: yaml
  label: Coudre Bros. Auth API
  slug: coudrebros-eu-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-auth-api-openapi.yml
- filename: coudrebros-eu-health-api-openapi.yml
  format: yaml
  label: Coudre Bros. Health API
  slug: coudrebros-eu-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-health-api-openapi.yml
- filename: coudrebros-eu-mint-api-openapi.yml
  format: yaml
  label: Coudre Bros. Mint API
  slug: coudrebros-eu-mint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-mint-api-openapi.yml
- filename: coudrebros-eu-notary-api-openapi.yml
  format: yaml
  label: Coudre Bros. Notary API
  slug: coudrebros-eu-notary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-notary-api-openapi.yml
- filename: coudrebros-eu-payment-api-openapi.yml
  format: yaml
  label: Coudre Bros. Payment API
  slug: coudrebros-eu-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-payment-api-openapi.yml
- filename: coudrebros-eu-prerequisites-api-openapi.yml
  format: yaml
  label: Coudre Bros. Prerequisites API
  slug: coudrebros-eu-prerequisites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-prerequisites-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This service is intended for individuals over the age of 18.
    type: individual
  minimum_age:
    text: This service is intended for individuals over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Caller responsible for content
    text: The caller (including AI agents acting on behalf of their operator) bears sole responsibility for any content they cause to be written to the blockchain or pinned to IPFS through this service.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: No account, dashboard, or KYC.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coudre Bros.
provenance_date: '2026-11-09'
provider_name: Coudre Bros.
provider_slug: coudrebros-eu
slug: coudrebros-eu-eligibility
source_date: '2026-11-09'
source_filename: coudrebros-eu-eligibility.yml
source_heading: Eligibility
source_page: https://www.coudrebros.eu/nft_api/#legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coudre Bros.\naid: coudrebros-eu\nurl: https://www.coudrebros.eu/nft_api/#legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This service is intended for individuals over the age of 18.\nrestricted_uses:\n- summary: Caller responsible for content\n  text: The caller (including AI agents acting on behalf of their operator) bears sole responsibility for any content\n    they cause to be written to the blockchain or pinned to IPFS through this service.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: No\
  \ account, dashboard, or KYC.\nminimum_age:\n  value: '18'\n  text: This service is intended for individuals over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/coudrebros-eu/eligibility/coudrebros-eu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Coudre Bros.'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cardano
- Blockchain
- Stake Pool
- NFT
- Minting
- Notary
- AI Agents
- MCP
- Web3
---
