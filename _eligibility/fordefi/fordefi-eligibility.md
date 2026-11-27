---
api_specs:
- filename: fordefi-address-book-api-openapi.yml
  format: yaml
  label: Fordefi Address Book API
  slug: fordefi-address-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-address-book-api-openapi.yml
- filename: fordefi-assets-api-openapi.yml
  format: yaml
  label: Fordefi Assets API
  slug: fordefi-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-assets-api-openapi.yml
- filename: fordefi-audit-log-api-openapi.yml
  format: yaml
  label: Fordefi Audit Log API
  slug: fordefi-audit-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-audit-log-api-openapi.yml
- filename: fordefi-authorization-tokens-api-openapi.yml
  format: yaml
  label: Fordefi Authorization Tokens API
  slug: fordefi-authorization-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-authorization-tokens-api-openapi.yml
- filename: fordefi-batch-transactions-api-openapi.yml
  format: yaml
  label: Fordefi Batch Transactions API
  slug: fordefi-batch-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-batch-transactions-api-openapi.yml
- filename: fordefi-blockchains-api-openapi.yml
  format: yaml
  label: Fordefi Blockchains API
  slug: fordefi-blockchains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-blockchains-api-openapi.yml
- filename: fordefi-enclave-keys-api-openapi.yml
  format: yaml
  label: Fordefi Enclave Keys API
  slug: fordefi-enclave-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-enclave-keys-api-openapi.yml
- filename: fordefi-end-users-api-openapi.yml
  format: yaml
  label: Fordefi End Users API
  slug: fordefi-end-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-end-users-api-openapi.yml
- filename: fordefi-exports-api-openapi.yml
  format: yaml
  label: Fordefi Exports API
  slug: fordefi-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-exports-api-openapi.yml
- filename: fordefi-organizations-api-openapi.yml
  format: yaml
  label: Fordefi Organizations API
  slug: fordefi-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-organizations-api-openapi.yml
- filename: fordefi-swaps-api-openapi.yml
  format: yaml
  label: Fordefi Swaps API
  slug: fordefi-swaps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-swaps-api-openapi.yml
- filename: fordefi-transactions-api-openapi.yml
  format: yaml
  label: Fordefi Transactions API
  slug: fordefi-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-transactions-api-openapi.yml
- filename: fordefi-user-groups-api-openapi.yml
  format: yaml
  label: Fordefi User Groups API
  slug: fordefi-user-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-user-groups-api-openapi.yml
- filename: fordefi-users-api-openapi.yml
  format: yaml
  label: Fordefi Users API
  slug: fordefi-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-users-api-openapi.yml
- filename: fordefi-vault-groups-api-openapi.yml
  format: yaml
  label: Fordefi Vault Groups API
  slug: fordefi-vault-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-vault-groups-api-openapi.yml
- filename: fordefi-vaults-api-openapi.yml
  format: yaml
  label: Fordefi Vaults API
  slug: fordefi-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-vaults-api-openapi.yml
- filename: fordefi-webhooks-api-openapi.yml
  format: yaml
  label: Fordefi Webhooks API
  slug: fordefi-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fordefi/openapi/fordefi-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: solely for your own personal and non-commercial use
    type: individual
  minimum_age:
    text: YOU REPRESENT THAT YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Infringement or unlawful use
    text: use any Fordefi Materials to infringe, misappropriate or violate any third party's Intellectual Property Rights
  - summary: Advertising on the website
    text: upload or publish any advertisement or promotional material on the Website
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
name: Fordefi
provenance_date: '2026-11-09'
provider_name: Fordefi
provider_slug: fordefi
slug: fordefi-eligibility
source_date: '2026-11-09'
source_filename: fordefi-eligibility.yml
source_heading: Eligibility
source_page: https://fordefi.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fordefi\naid: fordefi\nurl: https://fordefi.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: solely for your own personal and non-commercial use\nrestricted_uses:\n- summary: Infringement or unlawful use\n  text: use any Fordefi Materials to infringe, misappropriate or violate any third party's Intellectual Property\n    Rights\n- summary: Advertising on the website\n  text: upload or publish any advertisement or promotional material on the Website\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU REPRESENT THAT YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/fordefi/eligibility/fordefi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Fordefi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cryptocurrency
- Digital Assets
- Wallets
- Custody
- Blockchain
- DeFi
- MPC
- Payments
---
