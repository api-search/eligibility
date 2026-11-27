---
api_specs:
- filename: supra-accounts-api-openapi.yml
  format: yaml
  label: Supra Accounts API
  slug: supra-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-accounts-api-openapi.yml
- filename: supra-block-api-openapi.yml
  format: yaml
  label: Supra Block API
  slug: supra-block-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-block-api-openapi.yml
- filename: supra-consensus-api-openapi.yml
  format: yaml
  label: Supra Consensus API
  slug: supra-consensus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-consensus-api-openapi.yml
- filename: supra-events-api-openapi.yml
  format: yaml
  label: Supra Events API
  slug: supra-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-events-api-openapi.yml
- filename: supra-faucet-api-openapi.yml
  format: yaml
  label: Supra Faucet API
  slug: supra-faucet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-faucet-api-openapi.yml
- filename: supra-proofs-api-openapi.yml
  format: yaml
  label: Supra Proofs API
  slug: supra-proofs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-proofs-api-openapi.yml
- filename: supra-tables-api-openapi.yml
  format: yaml
  label: Supra Tables API
  slug: supra-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-tables-api-openapi.yml
- filename: supra-transactions-api-openapi.yml
  format: yaml
  label: Supra Transactions API
  slug: supra-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-transactions-api-openapi.yml
- filename: supra-version-api-openapi.yml
  format: yaml
  label: Supra Version API
  slug: supra-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-version-api-openapi.yml
- filename: supra-view-api-openapi.yml
  format: yaml
  label: Supra View API
  slug: supra-view-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-view-api-openapi.yml
- filename: supra-websocket-api-openapi.yml
  format: yaml
  label: Supra Web Socket API
  slug: supra-websocket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-websocket-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - AF
    - AS
    - BS
    - BW
    - KH
    - CA
    - CN
    - KP
    - ET
    - GH
    - GU
    - IR
    - IQ
    - LY
    - NG
    - PK
    - PA
    - PR
    - WS
    - SA
    - RS
    - LK
    - SY
    - TT
    - TN
    - VI
    - US
    - YE
    served: []
    text: You are not a citizen of and/or do not have a (registered) address in Afghanistan, American Samoa, The Bahamas, Botswana, Cambodia, Canada, China
  entity_types:
  - text: You must be at least eighteen years old
    type: individual
  - text: you or the company or other legal entity that you representative
    type: business
  minimum_age:
    text: You must be at least eighteen years old;
    value: '18'
  restricted_uses:
  - summary: Laws and sanctions restrictions
    text: You will not use the Websites or Services if prohibited by applicable laws in your country
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- AF
- AS
- BS
- BW
- KH
- CA
- CN
- KP
- ET
- GH
- GU
- IR
- IQ
- LY
- NG
- PK
- PA
- PR
- WS
- SA
- RS
- LK
- SY
- TT
- TN
- VI
- US
- YE
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Supra
provenance_date: '2026-11-10'
provider_name: Supra
provider_slug: supra
slug: supra-eligibility
source_date: '2026-11-10'
source_filename: supra-eligibility.yml
source_heading: Eligibility
source_page: https://supra.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Supra\naid: supra\nurl: https://supra.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - AF\n  - AS\n  - BS\n  - BW\n  - KH\n  - CA\n  - CN\n  - KP\n  - ET\n  - GH\n  - GU\n  - IR\n  - IQ\n  - LY\n  - NG\n  - PK\n  - PA\n  - PR\n  - WS\n  - SA\n  - RS\n  - LK\n  - SY\n  - TT\n  - TN\n  - VI\n  - US\n  - YE\n  text: You are not a citizen of and/or do not have a (registered) address in Afghanistan, American Samoa, The Bahamas,\n    Botswana, Cambodia, Canada, China\nentity_types:\n- type: individual\n  text: You must be at least eighteen years old\n- type: business\n  text:\
  \ you or the company or other legal entity that you representative\nrestricted_uses:\n- summary: Laws and sanctions restrictions\n  text: You will not use the Websites or Services if prohibited by applicable laws in your country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen years old;\n"
source_yaml_url: https://artifacts.apis.io/supra/eligibility/supra-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Supra's own page on 2026-11-10.
synthetic: false
tags:
- Blockchain
- Layer 1
- Oracle
- Web3
- Market Data
- Smart Contracts
- Verifiable Randomness
- Cross-Chain Bridge
- Automation
- Move
- Cryptocurrency
- DeFi
---
