---
api_specs:
- filename: rocksolid-allocations-api-openapi.yml
  format: yaml
  label: RockSolid Allocations API
  slug: rocksolid-allocations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocksolid/openapi/rocksolid-allocations-api-openapi.yml
- filename: rocksolid-performance-api-openapi.yml
  format: yaml
  label: RockSolid Performance API
  slug: rocksolid-performance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocksolid/openapi/rocksolid-performance-api-openapi.yml
- filename: rocksolid-vaults-api-openapi.yml
  format: yaml
  label: RockSolid Vaults API
  slug: rocksolid-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocksolid/openapi/rocksolid-vaults-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - AU
    - CA
    - SG
    - US
    - GB
    - BY
    - BI
    - CU
    - CD
    - IR
    - IQ
    - LY
    - MM
    - KP
    - SO
    - SD
    - SY
    - VE
    - ZW
    served: []
    text: 'You represent that you are not a resident of, located in, or accessing the Services from any of the following jurisdictions: Australia, Canada, Singapore, United States (and its territories), United Kingdom, Belarus, Burundi, Crimea & Sevastopol, Cuba, Democratic Republic of Congo, Iran, Iraq, Libya, Myanmar, North Korea, Somalia, Sudan, Syria, Venezuela, and Zimbabwe.'
  minimum_age:
    text: You are at least 18 years of age or the age of legal majority in your jurisdiction, whichever is greater
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons
    text: You are not, and are not acting on behalf of, any person or entity that is a specially designated national, blocked person, or otherwise subject to any sanctions or embargoes administered by any applicable governmental authority
  - summary: Illegal, fraudulent or malicious purposes
    text: You will not use the Services for any illegal, fraudulent, or malicious purpose, including but not limited to money laundering, terrorist financing, or violating any applicable anti-corruption laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In specific circumstances, such as for institutional onboarding, participation in certain community programs, or where required by applicable law, we may need to collect identity verification information.
excluded_countries:
- AU
- CA
- SG
- US
- GB
- BY
- BI
- CU
- CD
- IR
- IQ
- LY
- MM
- KP
- SO
- SD
- SY
- VE
- ZW
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RockSolid
provenance_date: '2026-11-10'
provider_name: RockSolid
provider_slug: rocksolid
slug: rocksolid-eligibility
source_date: '2026-11-10'
source_filename: rocksolid-eligibility.yml
source_heading: Eligibility
source_page: https://rocksolid.network/terms#tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RockSolid\naid: rocksolid\nurl: https://rocksolid.network/terms#tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - AU\n  - CA\n  - SG\n  - US\n  - GB\n  - BY\n  - BI\n  - CU\n  - CD\n  - IR\n  - IQ\n  - LY\n  - MM\n  - KP\n  - SO\n  - SD\n  - SY\n  - VE\n  - ZW\n  text: 'You represent that you are not a resident of, located in, or accessing the Services from any of the following\n    jurisdictions: Australia, Canada, Singapore, United States (and its territories), United Kingdom, Belarus, Burundi,\n    Crimea & Sevastopol, Cuba, Democratic Republic of Congo, Iran, Iraq,\
  \ Libya, Myanmar, North Korea, Somalia, Sudan,\n    Syria, Venezuela, and Zimbabwe.'\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned persons\n  text: You are not, and are not acting on behalf of, any person or entity that is a specially designated national,\n    blocked person, or otherwise subject to any sanctions or embargoes administered by any applicable governmental\n    authority\n- summary: Illegal, fraudulent or malicious purposes\n  text: You will not use the Services for any illegal, fraudulent, or malicious purpose, including but not limited\n    to money laundering, terrorist financing, or violating any applicable anti-corruption laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In specific circumstances, such as for institutional onboarding, participation in certain community programs,\n    or where required by applicable law, we may need to collect identity verification information.\nminimum_age:\n  value: '18'\n  text: You are\
  \ at least 18 years of age or the age of legal majority in your jurisdiction, whichever is greater\n"
source_yaml_url: https://artifacts.apis.io/rocksolid/eligibility/rocksolid-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from RockSolid's own page on 2026-11-10.
synthetic: false
tags:
- Company
- DeFi
- Decentralized Finance
- Liquid Vaults
- Yield
- Staking
- Web3
- Blockchain
---
