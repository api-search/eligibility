---
api_specs:
- filename: cipherowl-onchain-service-api-openapi.yml
  format: yaml
  label: CipherOwl Onchain Service API
  slug: cipherowl-onchain-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cipherowl/openapi/cipherowl-onchain-service-api-openapi.yml
- filename: cipherowl-private-data-api-api-openapi.yml
  format: yaml
  label: CipherOwl Private Data API
  slug: cipherowl-private-data-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cipherowl/openapi/cipherowl-private-data-api-api-openapi.yml
- filename: cipherowl-srr-api-api-openapi.yml
  format: yaml
  label: CipherOwl SRR API
  slug: cipherowl-srr-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cipherowl/openapi/cipherowl-srr-api-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are located in, organized under the laws of, or ordinarily resident in a sanctioned or embargoed jurisdiction, or if you are identified on a restricted party list.
  entity_types:
  - text: If you are using the Services on behalf of an organization, you represent that you have authority to bind that organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and export restrictions
    text: You may not use the Services in violation of U.S. export control, sanctions, anti-money laundering, anti-bribery, anti-corruption, or other applicable laws.
  - summary: Sanctioned party activity
    text: You may not use the Services to facilitate transactions, activity, or evasion involving sanctioned persons, sanctioned jurisdictions, or prohibited activity.
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
name: CipherOwl
provenance_date: '2026-11-09'
provider_name: CipherOwl
provider_slug: cipherowl
slug: cipherowl-eligibility
source_date: '2026-11-09'
source_filename: cipherowl-eligibility.yml
source_heading: Eligibility
source_page: https://cipherowl.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CipherOwl\naid: cipherowl\nurl: https://cipherowl.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are located in, organized under the laws of, or ordinarily resident\n    in a sanctioned or embargoed jurisdiction, or if you are identified on a restricted party list.\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent that you have authority to bind\n    that organization\nrestricted_uses:\n- summary: Sanctions and export restrictions\n  text: You may not use the Services\
  \ in violation of U.S. export control, sanctions, anti-money laundering, anti-bribery,\n    anti-corruption, or other applicable laws.\n- summary: Sanctioned party activity\n  text: You may not use the Services to facilitate transactions, activity, or evasion involving sanctioned persons,\n    sanctioned jurisdictions, or prohibited activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cipherowl/eligibility/cipherowl-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from CipherOwl's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Compliance
- Cryptocurrency
- Security
- Risk Management
- Sanctions Screening
- AML
- Digital Assets
- Stablecoins
- Web3
---
