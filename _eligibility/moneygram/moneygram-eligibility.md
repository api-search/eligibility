---
api_specs:
- filename: moneygram-accounts-api-openapi.yml
  format: yaml
  label: MoneyGram Accounts API
  slug: moneygram-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-accounts-api-openapi.yml
- filename: moneygram-amend-api-openapi.yml
  format: yaml
  label: MoneyGram Amend API
  slug: moneygram-amend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-amend-api-openapi.yml
- filename: moneygram-fx-rate-api-openapi.yml
  format: yaml
  label: MoneyGram Fx Rate API
  slug: moneygram-fx-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-fx-rate-api-openapi.yml
- filename: moneygram-oauth-api-openapi.yml
  format: yaml
  label: MoneyGram OAuth API
  slug: moneygram-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-oauth-api-openapi.yml
- filename: moneygram-partnerconnect-api-openapi.yml
  format: yaml
  label: MoneyGram Partnerconnect API
  slug: moneygram-partnerconnect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-partnerconnect-api-openapi.yml
- filename: moneygram-reference-data-api-openapi.yml
  format: yaml
  label: MoneyGram Reference Data API
  slug: moneygram-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-reference-data-api-openapi.yml
- filename: moneygram-transactions-api-openapi.yml
  format: yaml
  label: MoneyGram Transactions API
  slug: moneygram-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-transactions-api-openapi.yml
- filename: moneygram-transfer-api-openapi.yml
  format: yaml
  label: MoneyGram Transfer API
  slug: moneygram-transfer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-transfer-api-openapi.yml
- filename: moneygram-transfers-api-openapi.yml
  format: yaml
  label: MoneyGram Transfers API
  slug: moneygram-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-transfers-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - BY
    - CU
    - IR
    - KP
    - RU
    served:
    - US
    text: be a United States resident and be at least eighteen (18) years of age; ... IN OR ORDINARILY RESIDENT IN BELARUS, CUBA, IRAN, NORTH KOREA, RUSSIA, OR THE CRIMEA/SEVASTOPOL, LUHANSK, OR DONETSK REGIONS OF UKRAINE.
  entity_types:
  - text: the individual purchaser of the Services
    type: individual
  minimum_age:
    text: be at least eighteen (18) years of age (or the applicable age of majority and contractual capacity)
    value: '18'
  restricted_uses:
  - summary: Escrow, trust or gambling
    text: (I) FOR ESCROW, TRUST OR GAMBLING PURPOSES
  - summary: Tobacco products
    text: (V) FOR THE SALE OR PURCHASE OF TOBACCO OR TOBACCO RELATED PRODUCTS
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: If MoneyGram accepts your application, it will establish your User Account and activate it for use to access the Services
excluded_countries:
- BY
- CU
- IR
- KP
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MoneyGram
provenance_date: '2026-11-10'
provider_name: MoneyGram
provider_slug: moneygram
slug: moneygram-eligibility
source_date: '2026-11-10'
source_filename: moneygram-eligibility.yml
source_heading: Eligibility
source_page: https://www.moneygram.com/us/en/help-center/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MoneyGram\naid: moneygram\nurl: https://www.moneygram.com/us/en/help-center/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded:\n  - BY\n  - CU\n  - IR\n  - KP\n  - RU\n  text: be a United States resident and be at least eighteen (18) years of age; ... IN OR ORDINARILY RESIDENT IN\n    BELARUS, CUBA, IRAN, NORTH KOREA, RUSSIA, OR THE CRIMEA/SEVASTOPOL, LUHANSK, OR DONETSK REGIONS OF UKRAINE.\nentity_types:\n- type: individual\n  text: the individual purchaser of the Services\nrestricted_uses:\n- summary: Escrow, trust or gambling\n  text: (I) FOR ESCROW, TRUST OR GAMBLING\
  \ PURPOSES\n- summary: Tobacco products\n  text: (V) FOR THE SALE OR PURCHASE OF TOBACCO OR TOBACCO RELATED PRODUCTS\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: If MoneyGram accepts your application, it will establish your User Account and activate it for use to access\n    the Services\nminimum_age:\n  value: '18'\n  text: be at least eighteen (18) years of age (or the applicable age of majority and contractual capacity)\n"
source_yaml_url: https://artifacts.apis.io/moneygram/eligibility/moneygram-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from MoneyGram's own page on 2026-11-10.
synthetic: false
tags:
- Money
- Payments
- Transfer
- Fintech
- Global
---
