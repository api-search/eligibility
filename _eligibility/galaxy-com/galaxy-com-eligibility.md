---
api_specs:
- filename: galaxy-com-ethereum-api-openapi.yml
  format: yaml
  label: Galaxy Ethereum API
  slug: galaxy-com-ethereum-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/galaxy-com/openapi/galaxy-com-ethereum-api-openapi.yml
- filename: galaxy-com-solana-api-openapi.yml
  format: yaml
  label: Galaxy Solana API
  slug: galaxy-com-solana-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/galaxy-com/openapi/galaxy-com-solana-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Galaxy Digital reserves the right to limit access to the Site to any person, geographic region or jurisdiction.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Investment-plan restriction on shares
    text: Shares may not be purchased by an “employee benefit plan” within the meaning of the U.S. Employee Retirement Income Security Act of 1974
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
name: Galaxy
provenance_date: '2026-11-09'
provider_name: Galaxy
provider_slug: galaxy-com
slug: galaxy-com-eligibility
source_date: '2026-11-09'
source_filename: galaxy-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.galaxy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Galaxy\naid: galaxy-com\nurl: https://www.galaxy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Galaxy Digital reserves the right to limit access to the Site to any person, geographic region or jurisdiction.\nentity_types: []\nrestricted_uses:\n- summary: Investment-plan restriction on shares\n  text: Shares may not be purchased by an “employee benefit plan” within the meaning of the U.S. Employee Retirement\n    Income Security Act of 1974\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/galaxy-com/eligibility/galaxy-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Galaxy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Digital Assets
- Staking
- Ethereum
- Solana
- Trading
- Custody
- Financial Services
---
