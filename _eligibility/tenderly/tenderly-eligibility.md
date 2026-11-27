---
api_specs:
- filename: api
  format: yaml
  label: Tenderly REST API
  slug: tenderly-rest-api
  spec_type: OpenAPI
  url: https://docs.tenderly.co/reference/api
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In order to access and use the Tenderly Platform, You must be 18 years of age or older.
    type: individual
  minimum_age:
    text: You must be 18 years of age or older.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Tenderly reserves the absolute and unrestricted right to reject or terminate Your registration for any reason in Tenderly's sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tenderly
provenance_date: '2026-11-10'
provider_name: Tenderly
provider_slug: tenderly
slug: tenderly-eligibility
source_date: '2026-11-10'
source_filename: tenderly-eligibility.yml
source_heading: Eligibility
source_page: https://tenderly.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tenderly\naid: tenderly\nurl: https://tenderly.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: In order to access and use the Tenderly Platform, You must be 18 years of age or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Tenderly reserves the absolute and unrestricted right to reject or terminate Your registration for any reason\n    in Tenderly's sole discretion.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/tenderly/eligibility/tenderly-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Tenderly's own page on 2026-11-10.
synthetic: false
tags:
- Web3
- Blockchain
- Smart Contracts
- Ethereum
- EVM
- Debugging
- Simulation
- Developer Tools
---
