---
api_specs:
- filename: timeswap-fastapi-api-openapi.yml
  format: yaml
  label: Timeswap FastAPI API
  slug: timeswap-fastapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/timeswap/openapi/timeswap-fastapi-api-openapi.yml
- filename: timeswap-paulygon-api-openapi.yml
  format: yaml
  label: Timeswap Paulygon API
  slug: timeswap-paulygon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/timeswap/openapi/timeswap-paulygon-api-openapi.yml
- filename: timeswap-pools-api-openapi.yml
  format: yaml
  label: Timeswap Pools API
  slug: timeswap-pools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/timeswap/openapi/timeswap-pools-api-openapi.yml
- filename: timeswap-taskon-api-openapi.yml
  format: yaml
  label: Timeswap TaskON API
  slug: timeswap-taskon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/timeswap/openapi/timeswap-taskon-api-openapi.yml
- filename: timeswap-token-api-openapi.yml
  format: yaml
  label: Timeswap Token API
  slug: timeswap-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/timeswap/openapi/timeswap-token-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The App is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Illegal activity including money laundering
    text: (f) engage in, promote, or encourage illegal activity (including, without limitation, money laundering)
  - summary: No unauthorized commercial purpose
    text: (h) exploit the App for any unauthorized commercial purpose
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We reserve the right to conduct "Know Your Customer" and "Anti-Money Laundering" checks on you if deemed necessary by us (at our sole discretion)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Timeswap
provenance_date: '2026-11-10'
provider_name: Timeswap
provider_slug: timeswap
slug: timeswap-eligibility
source_date: '2026-11-10'
source_filename: timeswap-eligibility.yml
source_heading: Eligibility
source_page: https://timeswap.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Timeswap\naid: timeswap\nurl: https://timeswap.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal activity including money laundering\n  text: (f) engage in, promote, or encourage illegal activity (including, without limitation, money laundering)\n- summary: No unauthorized commercial purpose\n  text: (h) exploit the App for any unauthorized commercial purpose\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We reserve the right to conduct \"Know Your Customer\" and\
  \ \"Anti-Money Laundering\" checks on you if deemed\n    necessary by us (at our sole discretion)\nminimum_age:\n  value: '18'\n  text: The App is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/timeswap/eligibility/timeswap-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Timeswap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web3
- DeFi
- Lending
- Borrowing
- Liquidity Pools
- Fixed Income
- Blockchain
- Cryptocurrency
---
