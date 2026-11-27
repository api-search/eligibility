---
api_specs:
- filename: agora-accounts-api-openapi.yml
  format: yaml
  label: Agora Accounts API
  slug: agora-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora/openapi/agora-accounts-api-openapi.yml
- filename: agora-auth-api-openapi.yml
  format: yaml
  label: Agora Auth API
  slug: agora-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora/openapi/agora-auth-api-openapi.yml
- filename: agora-metrics-api-openapi.yml
  format: yaml
  label: Agora Metrics API
  slug: agora-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora/openapi/agora-metrics-api-openapi.yml
- filename: agora-routes-api-openapi.yml
  format: yaml
  label: Agora Routes API
  slug: agora-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora/openapi/agora-routes-api-openapi.yml
- filename: agora-transactions-api-openapi.yml
  format: yaml
  label: Agora Transactions API
  slug: agora-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora/openapi/agora-transactions-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - US
    - AF
    - BY
    - BA
    - MM
    - BI
    - CF
    - CD
    - CU
    - ET
    - HT
    - IR
    - IQ
    - LB
    - LY
    - ML
    - NI
    - KP
    - GW
    - PK
    - SO
    - SS
    - SD
    - SY
    - UA
    - VE
    - YE
    - ZW
    - RU
    served: []
    text: Russia, or any other country or territory on which the United States imposes sanctions or embargoes goods.
  entity_types:
  - text: you must be a corporation, legal person, entity, or other organization
    type: business
  - text: You are less than 18 years of age.
    type: individual
  minimum_age:
    text: You are less than 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Prohibited transactions
    text: money laundering; terrorist financing
  - summary: Prohibited activities
    text: Weapons vendors, sellers and manufacturers; Illegal/controlled substance vendors; Drugs and Drug Paraphernalia; Adult Content and Escort Services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to cause AUSD to be minted or redeemed directly by Agora, you must be a verified customer of Agora.
excluded_countries:
- US
- AF
- BY
- BA
- MM
- BI
- CF
- CD
- CU
- ET
- HT
- IR
- IQ
- LB
- LY
- ML
- NI
- KP
- GW
- PK
- SO
- SS
- SD
- SY
- UA
- VE
- YE
- ZW
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agora
provenance_date: '2026-11-09'
provider_name: Agora
provider_slug: agora
slug: agora-eligibility
source_date: '2026-11-09'
source_filename: agora-eligibility.yml
source_heading: Eligibility
source_page: https://static.agora.finance/termsofuse.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agora\naid: agora\nurl: https://static.agora.finance/termsofuse.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - US\n  - AF\n  - BY\n  - BA\n  - MM\n  - BI\n  - CF\n  - CD\n  - CU\n  - ET\n  - HT\n  - IR\n  - IQ\n  - LB\n  - LY\n  - ML\n  - NI\n  - KP\n  - GW\n  - PK\n  - SO\n  - SS\n  - SD\n  - SY\n  - UA\n  - VE\n  - YE\n  - ZW\n  - RU\n  text: Russia, or any other country or territory on which the United States imposes sanctions or embargoes goods.\nentity_types:\n- type: business\n  text: you must be a corporation, legal person, entity, or other organization\n\
  - type: individual\n  text: You are less than 18 years of age.\nrestricted_uses:\n- summary: Prohibited transactions\n  text: money laundering; terrorist financing\n- summary: Prohibited activities\n  text: Weapons vendors, sellers and manufacturers; Illegal/controlled substance vendors; Drugs and Drug Paraphernalia;\n    Adult Content and Escort Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to cause AUSD to be minted or redeemed directly by Agora, you must be a verified customer of Agora.\nminimum_age:\n  value: '18'\n  text: You are less than 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/agora/eligibility/agora-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Agora's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Stablecoins
- Digital Dollar
- Payments
- Cryptocurrency
- Blockchain
- AUSD
- Stablecoin Issuance
---
