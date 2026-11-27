---
api_specs:
- filename: gauntlet-prices-api-openapi.yml
  format: yaml
  label: Gauntlet Prices API
  slug: gauntlet-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gauntlet/openapi/gauntlet-prices-api-openapi.yml
- filename: gauntlet-system-api-openapi.yml
  format: yaml
  label: Gauntlet System API
  slug: gauntlet-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gauntlet/openapi/gauntlet-system-api-openapi.yml
- filename: gauntlet-tvl-api-openapi.yml
  format: yaml
  label: Gauntlet TVL API
  slug: gauntlet-tvl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gauntlet/openapi/gauntlet-tvl-api-openapi.yml
- filename: gauntlet-users-api-openapi.yml
  format: yaml
  label: Gauntlet Users API
  slug: gauntlet-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gauntlet/openapi/gauntlet-users-api-openapi.yml
- filename: gauntlet-vaults-api-openapi.yml
  format: yaml
  label: Gauntlet Vaults API
  slug: gauntlet-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gauntlet/openapi/gauntlet-vaults-api-openapi.yml
- filename: gauntlet-strategies-api-openapi.yml
  format: yaml
  label: Gauntlet Strategies API
  slug: gauntlet-strategies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gauntlet/openapi/gauntlet-strategies-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not ... a citizen, resident, or entity organized in a jurisdiction or territory that is the subject of comprehensive sanctions by the United States of America.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Securities and derivatives violations
    text: Activity that violates any applicable law, rule, or regulation concerning the issuance or trading of securities or derivatives
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
name: Gauntlet
provenance_date: '2026-11-09'
provider_name: Gauntlet
provider_slug: gauntlet
slug: gauntlet-eligibility
source_date: '2026-11-09'
source_filename: gauntlet-eligibility.yml
source_heading: Eligibility
source_page: https://www.gauntlet.xyz/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gauntlet\naid: gauntlet\nurl: https://www.gauntlet.xyz/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not ... a citizen, resident, or entity organized in a jurisdiction or territory that is the subject\n    of comprehensive sanctions by the United States of America.\nentity_types: []\nrestricted_uses:\n- summary: Securities and derivatives violations\n  text: Activity that violates any applicable law, rule, or regulation concerning the issuance or trading of securities\n    or derivatives\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gauntlet/eligibility/gauntlet-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Gauntlet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Crypto Data
- DeFi
- Risk Management
- Yield
- Vault
- Blockchain
- Web3
- Financial Modeling
---
