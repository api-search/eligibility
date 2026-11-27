---
api_specs:
- filename: mesh-connect-assets-api-openapi.yml
  format: yaml
  label: Mesh Connect Assets API
  slug: mesh-connect-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh-connect/openapi/mesh-connect-assets-api-openapi.yml
- filename: mesh-connect-auth-token-api-openapi.yml
  format: yaml
  label: Mesh Connect Auth token API
  slug: mesh-connect-auth-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh-connect/openapi/mesh-connect-auth-token-api-openapi.yml
- filename: mesh-connect-balance-api-openapi.yml
  format: yaml
  label: Mesh Connect Balance API
  slug: mesh-connect-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh-connect/openapi/mesh-connect-balance-api-openapi.yml
- filename: mesh-connect-brokeraccountdetail-api-openapi.yml
  format: yaml
  label: Mesh Connect BrokerAccountDetail API
  slug: mesh-connect-brokeraccountdetail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh-connect/openapi/mesh-connect-brokeraccountdetail-api-openapi.yml
- filename: mesh-connect-main-clients-api-openapi.yml
  format: yaml
  label: Mesh Connect Main Clients API
  slug: mesh-connect-main-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh-connect/openapi/mesh-connect-main-clients-api-openapi.yml
- filename: mesh-connect-managed-account-authentication-api-openapi.yml
  format: yaml
  label: Mesh Connect Managed Account Authentication API
  slug: mesh-connect-managed-account-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh-connect/openapi/mesh-connect-managed-account-authentication-api-openapi.yml
- filename: mesh-connect-managed-transfers-api-openapi.yml
  format: yaml
  label: Mesh Connect Managed Transfers API
  slug: mesh-connect-managed-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh-connect/openapi/mesh-connect-managed-transfers-api-openapi.yml
- filename: mesh-connect-portfolio-api-openapi.yml
  format: yaml
  label: Mesh Connect Portfolio API
  slug: mesh-connect-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh-connect/openapi/mesh-connect-portfolio-api-openapi.yml
- filename: mesh-connect-registered-clients-api-openapi.yml
  format: yaml
  label: Mesh Connect Registered Clients API
  slug: mesh-connect-registered-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh-connect/openapi/mesh-connect-registered-clients-api-openapi.yml
- filename: mesh-connect-self-managed-account-authentication-api-openapi.yml
  format: yaml
  label: Mesh Connect Self Managed Account Authentication API
  slug: mesh-connect-self-managed-account-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh-connect/openapi/mesh-connect-self-managed-account-authentication-api-openapi.yml
- filename: mesh-connect-transactions-api-openapi.yml
  format: yaml
  label: Mesh Connect Transactions API
  slug: mesh-connect-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh-connect/openapi/mesh-connect-transactions-api-openapi.yml
- filename: mesh-connect-transfers-api-openapi.yml
  format: yaml
  label: Mesh Connect Transfers API
  slug: mesh-connect-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesh-connect/openapi/mesh-connect-transfers-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE AN INDIVIDUAL ACCESSING OR USING THE PRODUCT OR ANY SERVICES ON BEHALF OF, OR FOR THE BENEFIT OF, ANY CORPORATION, PARTNERSHIP OR OTHER ENTITY WITH WHICH YOU ARE ASSOCIATED (AN “ORGANIZATION”), THEN YOU ARE AGREEING TO THIS AGREEMENT ON BEHALF OF YOURSELF AND SUCH ORGANIZATION
    type: individual
  - text: IF YOU ARE AN INDIVIDUAL ACCESSING OR USING THE PRODUCT OR ANY SERVICES ON BEHALF OF, OR FOR THE BENEFIT OF, ANY CORPORATION, PARTNERSHIP OR OTHER ENTITY WITH WHICH YOU ARE ASSOCIATED (AN “ORGANIZATION”), THEN YOU ARE AGREEING TO THIS AGREEMENT ON BEHALF OF YOURSELF AND SUCH ORGANIZATION
    type: business
  minimum_age:
    text: BY USING THE PRODUCT OR ANY SERVICES, YOU AFFIRM THAT YOU ARE OF LEGAL AGE TO ENTER INTO THIS AGREEMENT.
    value: legal age
  restricted_uses:
  - summary: Personal, non-commercial use prohibited
    text: use the Product for any personal (i.e., non-commercial or non-business) purpose, or for any purpose that is fraudulent or otherwise tortious or unlawful
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
name: Mesh Connect
provenance_date: '2026-11-10'
provider_name: Mesh Connect
provider_slug: mesh-connect
slug: mesh-connect-eligibility
source_date: '2026-11-10'
source_filename: mesh-connect-eligibility.yml
source_heading: Eligibility
source_page: https://www.meshpay.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mesh Connect\naid: mesh-connect\nurl: https://www.meshpay.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: IF YOU ARE AN INDIVIDUAL ACCESSING OR USING THE PRODUCT OR ANY SERVICES ON BEHALF OF, OR FOR THE BENEFIT\n    OF, ANY CORPORATION, PARTNERSHIP OR OTHER ENTITY WITH WHICH YOU ARE ASSOCIATED (AN “ORGANIZATION”), THEN YOU\n    ARE AGREEING TO THIS AGREEMENT ON BEHALF OF YOURSELF AND SUCH ORGANIZATION\n- type: business\n  text: IF YOU ARE AN INDIVIDUAL ACCESSING OR USING THE PRODUCT OR ANY SERVICES ON BEHALF OF,\
  \ OR FOR THE BENEFIT\n    OF, ANY CORPORATION, PARTNERSHIP OR OTHER ENTITY WITH WHICH YOU ARE ASSOCIATED (AN “ORGANIZATION”), THEN YOU\n    ARE AGREEING TO THIS AGREEMENT ON BEHALF OF YOURSELF AND SUCH ORGANIZATION\nrestricted_uses:\n- summary: Personal, non-commercial use prohibited\n  text: use the Product for any personal (i.e., non-commercial or non-business) purpose, or for any purpose that\n    is fraudulent or otherwise tortious or unlawful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: BY USING THE PRODUCT OR ANY SERVICES, YOU AFFIRM THAT YOU ARE OF LEGAL AGE TO ENTER INTO THIS AGREEMENT.\n"
source_yaml_url: https://artifacts.apis.io/mesh-connect/eligibility/mesh-connect-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mesh Connect's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Crypto Infrastructure
- Crypto Payments
- Digital Assets
- Wallets
- Exchange
- Embedded Finance
- Stablecoins
- Payments
---
