---
api_specs:
- filename: solana-accounts-api-openapi.yml
  format: yaml
  label: Solana Accounts API
  slug: solana-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solana/openapi/solana-accounts-api-openapi.yml
- filename: solana-blocks-api-openapi.yml
  format: yaml
  label: Solana Blocks API
  slug: solana-blocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solana/openapi/solana-blocks-api-openapi.yml
- filename: solana-cluster-api-openapi.yml
  format: yaml
  label: Solana Cluster API
  slug: solana-cluster-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solana/openapi/solana-cluster-api-openapi.yml
- filename: solana-economics-api-openapi.yml
  format: yaml
  label: Solana Economics API
  slug: solana-economics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solana/openapi/solana-economics-api-openapi.yml
- filename: solana-tokens-api-openapi.yml
  format: yaml
  label: Solana Tokens API
  slug: solana-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solana/openapi/solana-tokens-api-openapi.yml
- filename: solana-transactions-api-openapi.yml
  format: yaml
  label: Solana Transactions API
  slug: solana-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solana/openapi/solana-transactions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for users who are at least 18 years old.
    type: individual
  - text: If you use the Service on behalf of another person or entity, (a) all references to "you" throughout the EULA will include that person or entity
    type: business
  minimum_age:
    text: The Service is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Prohibited activities
    text: The Service may not be used in connection with any commercial endeavors except those that are specifically endorsed or approved by us.
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
name: Solana
provenance_date: '2026-11-10'
provider_name: Solana
provider_slug: solana
slug: solana-eligibility
source_date: '2026-11-10'
source_filename: solana-eligibility.yml
source_heading: Eligibility
source_page: https://solana.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Solana\naid: solana\nurl: https://solana.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is intended for users who are at least 18 years old.\n- type: business\n  text: If you use the Service on behalf of another person or entity, (a) all references to \"you\" throughout the\n    EULA will include that person or entity\nrestricted_uses:\n- summary: Prohibited activities\n  text: The Service may not be used in connection with any commercial endeavors except those that are specifically\n    endorsed or approved by\
  \ us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/solana/eligibility/solana-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Solana's own page on 2026-11-10.
synthetic: false
tags:
- Solana
- Blockchain
- Cryptocurrency
- Web3
- DeFi
- Transaction
- Tokens
---
