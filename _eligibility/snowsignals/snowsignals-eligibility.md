---
api_specs:
- filename: snowsignals-notifications-api-openapi.yml
  format: yaml
  label: SnowSignals Notifications API
  slug: snowsignals-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snowsignals/openapi/snowsignals-notifications-api-openapi.yml
- filename: snowsignals-phase-api-openapi.yml
  format: yaml
  label: SnowSignals Phase API
  slug: snowsignals-phase-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snowsignals/openapi/snowsignals-phase-api-openapi.yml
- filename: snowsignals-phases-api-openapi.yml
  format: yaml
  label: SnowSignals Phases API
  slug: snowsignals-phases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snowsignals/openapi/snowsignals-phases-api-openapi.yml
- filename: snowsignals-time-api-openapi.yml
  format: yaml
  label: SnowSignals Time API
  slug: snowsignals-time-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snowsignals/openapi/snowsignals-time-api-openapi.yml
- filename: snowsignals-user-api-openapi.yml
  format: yaml
  label: SnowSignals User API
  slug: snowsignals-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snowsignals/openapi/snowsignals-user-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Creating an account is your acceptance of these terms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SnowSignals
provenance_date: '2026-11-10'
provider_name: SnowSignals
provider_slug: snowsignals
slug: snowsignals-eligibility
source_date: '2026-11-10'
source_filename: snowsignals-eligibility.yml
source_heading: Eligibility
source_page: https://snowsignals.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SnowSignals\naid: snowsignals\nurl: https://snowsignals.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Creating an account is your acceptance of these terms.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/snowsignals/eligibility/snowsignals-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from SnowSignals's own page on 2026-11-10.
synthetic: false
tags:
- Cryptocurrency
- Market Data
- Bitcoin
- Analytics
- market-phase
- Regime
- trendvane
- DaaS
- MCP
- Agent-Native
- Financial Data
- x402
---
