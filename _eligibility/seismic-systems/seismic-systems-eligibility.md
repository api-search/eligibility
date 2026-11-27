---
api_specs:
- filename: seismic-systems-tokens-api-openapi.yml
  format: yaml
  label: Seismic Systems Tokens API
  slug: seismic-systems-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic-systems/openapi/seismic-systems-tokens-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users represent they are not located in, organized under the laws of, or ordinarily resident in a Restricted Jurisdiction; Restricted Jurisdiction is not defined in the visible text.
  entity_types:
  - text: The Seismic Platform is designed for use by business entities and their authorized representatives.
    type: business
  - text: Individual users may also interact directly with the Seismic Network (as defined below) for limited purposes such as paying gas fees.
    type: individual
  minimum_age:
    text: You are (i) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Money laundering, sanctions evasion, financial crime
    text: Use the Services for any purpose prohibited by applicable law, including money laundering, terrorist financing, proliferation financing, sanctions evasion, tax evasion, or any other financial crime
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
name: Seismic Systems
provenance_date: '2026-11-10'
provider_name: Seismic Systems
provider_slug: seismic-systems
slug: seismic-systems-eligibility
source_date: '2026-11-10'
source_filename: seismic-systems-eligibility.yml
source_heading: Eligibility
source_page: https://docs.seismic.systems/reference/terms-of-service.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Seismic Systems\naid: seismic-systems\nurl: https://docs.seismic.systems/reference/terms-of-service.md\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Users represent they are not located in, organized under the laws of, or ordinarily resident in a Restricted\n    Jurisdiction; Restricted Jurisdiction is not defined in the visible text.\nentity_types:\n- type: business\n  text: The Seismic Platform is designed for use by business entities and their authorized representatives.\n- type: individual\n  text: Individual users may also interact directly with the Seismic\
  \ Network (as defined below) for limited purposes\n    such as paying gas fees.\nrestricted_uses:\n- summary: Money laundering, sanctions evasion, financial crime\n  text: Use the Services for any purpose prohibited by applicable law, including money laundering, terrorist financing,\n    proliferation financing, sanctions evasion, tax evasion, or any other financial crime\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are (i) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/seismic-systems/eligibility/seismic-systems-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Seismic Systems's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Blockchain
- Privacy
- Encryption
- Stablecoins
- Fintech
- Web3
- Smart Contracts
- EVM
- Cryptography
- Developer Tools
---
