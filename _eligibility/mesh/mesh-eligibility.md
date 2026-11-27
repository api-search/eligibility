---
api_specs:
- filename: mesh-assets-api-openapi.yml
  format: yaml
  label: Mesh Assets API
  slug: mesh-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-assets-api-openapi.yml
- filename: mesh-balance-api-openapi.yml
  format: yaml
  label: Mesh Balance API
  slug: mesh-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-balance-api-openapi.yml
- filename: mesh-brokeraccountdetail-api-openapi.yml
  format: yaml
  label: Mesh BrokerAccountDetail API
  slug: mesh-brokeraccountdetail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-brokeraccountdetail-api-openapi.yml
- filename: mesh-managed-account-authentication-api-openapi.yml
  format: yaml
  label: Mesh Managed Account Authentication API
  slug: mesh-managed-account-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-managed-account-authentication-api-openapi.yml
- filename: mesh-managed-transfers-api-openapi.yml
  format: yaml
  label: Mesh Managed Transfers API
  slug: mesh-managed-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-managed-transfers-api-openapi.yml
- filename: mesh-portfolio-api-openapi.yml
  format: yaml
  label: Mesh Portfolio API
  slug: mesh-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-portfolio-api-openapi.yml
- filename: mesh-self-managed-account-authentication-api-openapi.yml
  format: yaml
  label: Mesh Self Managed Account Authentication API
  slug: mesh-self-managed-account-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-self-managed-account-authentication-api-openapi.yml
- filename: mesh-transactions-api-openapi.yml
  format: yaml
  label: Mesh Transactions API
  slug: mesh-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-transactions-api-openapi.yml
- filename: mesh-transfers-api-openapi.yml
  format: yaml
  label: Mesh Transfers API
  slug: mesh-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-transfers-api-openapi.yml
- filename: mesh-blockchainquery-api-openapi.yml
  format: yaml
  label: Mesh Blockchain Query API
  slug: mesh-blockchainquery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-blockchainquery-api-openapi.yml
- filename: mesh-cataloggassponsorship-api-openapi.yml
  format: yaml
  label: Mesh Catalog Gas Sponsorship API
  slug: mesh-cataloggassponsorship-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-cataloggassponsorship-api-openapi.yml
- filename: mesh-catalogsubscription-api-openapi.yml
  format: yaml
  label: Mesh Catalog Subscription API
  slug: mesh-catalogsubscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-catalogsubscription-api-openapi.yml
- filename: mesh-headless-bridging-api-openapi.yml
  format: yaml
  label: Mesh Headless Bridging API
  slug: mesh-headless-bridging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-headless-bridging-api-openapi.yml
- filename: mesh-integrations-account-information-api-openapi.yml
  format: yaml
  label: Mesh Integrations account information API
  slug: mesh-integrations-account-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-integrations-account-information-api-openapi.yml
- filename: mesh-rampkyc-api-openapi.yml
  format: yaml
  label: Mesh Ramp Kyc API
  slug: mesh-rampkyc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-rampkyc-api-openapi.yml
- filename: mesh-ramppayment-api-openapi.yml
  format: yaml
  label: Mesh Ramp Payment API
  slug: mesh-ramppayment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-ramppayment-api-openapi.yml
- filename: mesh-rampsession-api-openapi.yml
  format: yaml
  label: Mesh Ramp Session API
  slug: mesh-rampsession-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-rampsession-api-openapi.yml
- filename: mesh-tokennetworkpairs-api-openapi.yml
  format: yaml
  label: Mesh Token Network Pairs API
  slug: mesh-tokennetworkpairs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-tokennetworkpairs-api-openapi.yml
- filename: mesh-wallets-api-openapi.yml
  format: yaml
  label: Mesh Wallets API
  slug: mesh-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh/openapi/mesh-wallets-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: BY USING THE PRODUCT OR ANY SERVICES, YOU AFFIRM THAT YOU ARE OF LEGAL AGE TO ENTER INTO THIS AGREEMENT.
    type: individual
  - text: ANY CORPORATION, PARTNERSHIP OR OTHER ENTITY WITH WHICH YOU ARE ASSOCIATED
    type: business
  minimum_age:
    text: YOU AFFIRM THAT YOU ARE OF LEGAL AGE TO ENTER INTO THIS AGREEMENT
    value: legal age
  restricted_uses:
  - summary: Personal or non-business use
    text: use the Product for any personal (i.e., non-commercial or non-business) purpose
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
name: Mesh
provenance_date: '2026-11-10'
provider_name: Mesh
provider_slug: mesh
slug: mesh-eligibility
source_date: '2026-11-10'
source_filename: mesh-eligibility.yml
source_heading: Eligibility
source_page: https://www.meshpay.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mesh\naid: mesh\nurl: https://www.meshpay.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: BY USING THE PRODUCT OR ANY SERVICES, YOU AFFIRM THAT YOU ARE OF LEGAL AGE TO ENTER INTO THIS AGREEMENT.\n- type: business\n  text: ANY CORPORATION, PARTNERSHIP OR OTHER ENTITY WITH WHICH YOU ARE ASSOCIATED\nrestricted_uses:\n- summary: Personal or non-business use\n  text: use the Product for any personal (i.e., non-commercial or non-business) purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n \
  \ text: null\nminimum_age:\n  value: legal age\n  text: YOU AFFIRM THAT YOU ARE OF LEGAL AGE TO ENTER INTO THIS AGREEMENT\n"
source_yaml_url: https://artifacts.apis.io/mesh/eligibility/mesh-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mesh's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Payments
- Digital Assets
- Financial Services
- Wallets
- Exchange
- Transfers
- Stablecoins
- Embedded Finance
- Fintech
- On-Ramp
- Blockchain
---
