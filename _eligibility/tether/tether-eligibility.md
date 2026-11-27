---
api_specs:
- filename: tether-api-keys-api-openapi.yml
  format: yaml
  label: Tether API Keys API
  slug: tether-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tether/openapi/tether-api-keys-api-openapi.yml
- filename: tether-chains-api-openapi.yml
  format: yaml
  label: Tether Chains API
  slug: tether-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tether/openapi/tether-chains-api-openapi.yml
- filename: tether-health-api-openapi.yml
  format: yaml
  label: Tether Health API
  slug: tether-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tether/openapi/tether-health-api-openapi.yml
- filename: tether-token-balances-api-openapi.yml
  format: yaml
  label: Tether Token Balances API
  slug: tether-token-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tether/openapi/tether-token-balances-api-openapi.yml
- filename: tether-token-transfers-api-openapi.yml
  format: yaml
  label: Tether Token Transfers API
  slug: tether-token-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tether/openapi/tether-token-transfers-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: any individual under the age of eighteen (18) years or who does not have the capacity to contract under these Terms under applicable laws
    value: '18'
  restricted_uses:
  - summary: Use by Prohibited Persons
    text: 'The Site and its content is not intended for use by or on behalf of: (i) any Sanctioned Persons'
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
name: Tether
provenance_date: '2026-11-10'
provider_name: Tether
provider_slug: tether
slug: tether-eligibility
source_date: '2026-11-10'
source_filename: tether-eligibility.yml
source_heading: Eligibility
source_page: https://tether.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tether\naid: tether\nurl: https://tether.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use by Prohibited Persons\n  text: 'The Site and its content is not intended for use by or on behalf of: (i) any Sanctioned Persons'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: any individual under the age of eighteen (18) years or who does not have the capacity to contract under\n    these Terms under applicable laws\n"
source_yaml_url: https://artifacts.apis.io/tether/eligibility/tether-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Tether's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Stablecoins
- Cryptocurrency
- Blockchain
- Wallets
- Digital Assets
- Payments
- Self-Custody
- Multi-Chain
- Agents
- MCP
- Open Source
- Stablecoin Issuance
---
