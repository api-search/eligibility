---
api_specs:
- filename: hifi-account-api-openapi.yml
  format: yaml
  label: Hifi Account API
  slug: hifi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-account-api-openapi.yml
- filename: hifi-common-api-openapi.yml
  format: yaml
  label: Hifi Common API
  slug: hifi-common-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-common-api-openapi.yml
- filename: hifi-cross-chain-bridge-api-openapi.yml
  format: yaml
  label: Hifi Cross-Chain Bridge API
  slug: hifi-cross-chain-bridge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-cross-chain-bridge-api-openapi.yml
- filename: hifi-crypto-transfer-api-openapi.yml
  format: yaml
  label: Hifi Crypto Transfer API
  slug: hifi-crypto-transfer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-crypto-transfer-api-openapi.yml
- filename: hifi-file-api-openapi.yml
  format: yaml
  label: Hifi File API
  slug: hifi-file-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-file-api-openapi.yml
- filename: hifi-kyc-api-openapi.yml
  format: yaml
  label: Hifi Kyc API
  slug: hifi-kyc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-kyc-api-openapi.yml
- filename: hifi-offramp-api-openapi.yml
  format: yaml
  label: Hifi Offramp API
  slug: hifi-offramp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-offramp-api-openapi.yml
- filename: hifi-onramp-api-openapi.yml
  format: yaml
  label: Hifi Onramp API
  slug: hifi-onramp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-onramp-api-openapi.yml
- filename: hifi-reporting-api-openapi.yml
  format: yaml
  label: Hifi Reporting API
  slug: hifi-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-reporting-api-openapi.yml
- filename: hifi-settlement-rules-api-openapi.yml
  format: yaml
  label: Hifi Settlement Rules API
  slug: hifi-settlement-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-settlement-rules-api-openapi.yml
- filename: hifi-token-swap-api-openapi.yml
  format: yaml
  label: Hifi Token Swap API
  slug: hifi-token-swap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-token-swap-api-openapi.yml
- filename: hifi-transfer-approvals-api-openapi.yml
  format: yaml
  label: Hifi Transfer Approvals API
  slug: hifi-transfer-approvals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-transfer-approvals-api-openapi.yml
- filename: hifi-user-api-openapi.yml
  format: yaml
  label: Hifi User API
  slug: hifi-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-user-api-openapi.yml
- filename: hifi-virtual-account-api-openapi.yml
  format: yaml
  label: Hifi Virtual Account API
  slug: hifi-virtual-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-virtual-account-api-openapi.yml
- filename: hifi-wallet-api-openapi.yml
  format: yaml
  label: Hifi Wallet API
  slug: hifi-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-wallet-api-openapi.yml
- filename: hifi-canton-offers-api-openapi.yml
  format: yaml
  label: Hifi Canton Offers API
  slug: hifi-canton-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-canton-offers-api-openapi.yml
- filename: hifi-external-account-api-openapi.yml
  format: yaml
  label: Hifi External Account API
  slug: hifi-external-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-external-account-api-openapi.yml
- filename: hifi-orchestration-address-api-openapi.yml
  format: yaml
  label: Hifi Orchestration Address API
  slug: hifi-orchestration-address-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-orchestration-address-api-openapi.yml
- filename: hifi-rfi-api-openapi.yml
  format: yaml
  label: Hifi RFI API
  slug: hifi-rfi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hifi/openapi/hifi-rfi-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: 'You may not access or use the Site or Services if you are: (a) located in, or a resident or national of, any country subject to U.S. trade sanctions or embargoes (including Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions of Ukraine)'
  entity_types:
  - text: You must be at least eighteen (18) years of age, or the age of majority in your jurisdiction (whichever is higher), to access or use the Site or Services.
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years of age, or the age of majority in your jurisdiction (whichever is higher)
    value: '18'
  restricted_uses:
  - summary: Informational use only
    text: The Site and Services are provided for informational purposes only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hifi
provenance_date: '2026-11-09'
provider_name: Hifi
provider_slug: hifi
slug: hifi-eligibility
source_date: '2026-11-09'
source_filename: hifi-eligibility.yml
source_heading: Eligibility
source_page: https://www.hifi.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hifi\naid: hifi\nurl: https://www.hifi.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: 'You may not access or use the Site or Services if you are: (a) located in, or a resident or national of,\n    any country subject to U.S. trade sanctions or embargoes (including Cuba, Iran, North Korea, Syria, and the\n    Crimea, Donetsk, and Luhansk regions of Ukraine)'\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years of age, or the age of majority in your jurisdiction (whichever\n    is higher), to access\
  \ or use the Site or Services.\nrestricted_uses:\n- summary: Informational use only\n  text: The Site and Services are provided for informational purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age, or the age of majority in your jurisdiction (whichever\n    is higher)\n"
source_yaml_url: https://artifacts.apis.io/hifi/eligibility/hifi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Hifi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Stablecoins
- Payments
- Money Movement
- On-Ramp
- Off-Ramp
- Cryptocurrency
- Fintech
- KYC
- Virtual Accounts
- Cross-Chain
- Financial Infrastructure
---
