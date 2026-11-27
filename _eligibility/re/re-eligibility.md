---
api_specs:
- filename: re-general-api-openapi.yml
  format: yaml
  label: Re General API
  slug: re-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/re/openapi/re-general-api-openapi.yml
- filename: re-points-api-openapi.yml
  format: yaml
  label: Re Points API
  slug: re-points-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/re/openapi/re-points-api-openapi.yml
- filename: re-supply-api-openapi.yml
  format: yaml
  label: Re Supply API
  slug: re-supply-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/re/openapi/re-supply-api-openapi.yml
- filename: re-tvl-api-openapi.yml
  format: yaml
  label: Re TVL API
  slug: re-tvl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/re/openapi/re-tvl-api-openapi.yml
- filename: re-wallet-api-openapi.yml
  format: yaml
  label: Re Wallet API
  slug: re-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/re/openapi/re-wallet-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - AF
    - BY
    - CF
    - CI
    - CU
    - IR
    - IQ
    - KP
    - LB
    - LR
    - LY
    - MM
    - RU
    - SD
    - SY
    - VE
    - ZW
    served: []
    text: 'any a country or territory named on any Sanctions List which shall include (whether or not covered by the foregoing): Afghanistan, Belarus, Cote D''Ivoire (Ivory Coast), Central African Republic, Cuba'
  entity_types:
  - text: if you are an individual user, you are the greater of at least 18 years of age and the age of majority in your jurisdiction
    type: individual
  - text: if you are registering to use or using the Site on behalf of a legal entity, (i) such legal entity is duly organised and validly existing
    type: business
  minimum_age:
    text: if you are an individual user, you are the greater of at least 18 years of age and the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: U.S. Persons are Prohibited Persons
    text: 'means: any U.S. Person; the Government of Venezuela'
  - summary: Politically Exposed Persons restricted
    text: person that is or formerly was a Government Official or Politically Exposed person within the meaning of the FATF
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: The Resilience Parties insist on a comprehensive and thorough user due diligence process
excluded_countries:
- AF
- BY
- CF
- CI
- CU
- IR
- IQ
- KP
- LB
- LR
- LY
- MM
- RU
- SD
- SY
- VE
- ZW
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Re
provenance_date: '2026-11-10'
provider_name: Re
provider_slug: re
slug: re-eligibility
source_date: '2026-11-10'
source_filename: re-eligibility.yml
source_heading: Eligibility
source_page: https://re.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Re\naid: re\nurl: https://re.xyz/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - AF\n  - BY\n  - CF\n  - CI\n  - CU\n  - IR\n  - IQ\n  - KP\n  - LB\n  - LR\n  - LY\n  - MM\n  - RU\n  - SD\n  - SY\n  - VE\n  - ZW\n  text: 'any a country or territory named on any Sanctions List which shall include (whether or not covered by the\n    foregoing): Afghanistan, Belarus, Cote D''Ivoire (Ivory Coast), Central African Republic, Cuba'\nentity_types:\n- type: individual\n  text: if you are an individual user, you are the greater of at least 18 years of age and the age of majority\
  \ in\n    your jurisdiction\n- type: business\n  text: if you are registering to use or using the Site on behalf of a legal entity, (i) such legal entity is duly\n    organised and validly existing\nrestricted_uses:\n- summary: U.S. Persons are Prohibited Persons\n  text: 'means: any U.S. Person; the Government of Venezuela'\n- summary: Politically Exposed Persons restricted\n  text: person that is or formerly was a Government Official or Politically Exposed person within the meaning of\n    the FATF\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: The Resilience Parties insist on a comprehensive and thorough user due diligence process\nminimum_age:\n  value: '18'\n  text: if you are an individual user, you are the greater of at least 18 years of age and the age of majority in\n    your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/re/eligibility/re-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Re's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Reinsurance
- Insurance
- DeFi
- Blockchain
- Real World Assets
- Stablecoins
- Yield
- Onchain
---
