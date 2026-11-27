---
api_specs:
- filename: apuchat-com-channels-api-openapi.yml
  format: yaml
  label: Apuchat Channels API
  slug: apuchat-com-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apuchat-com/openapi/apuchat-com-channels-api-openapi.yml
- filename: apuchat-com-healthz-api-openapi.yml
  format: yaml
  label: Apuchat Healthz API
  slug: apuchat-com-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apuchat-com/openapi/apuchat-com-healthz-api-openapi.yml
- filename: apuchat-com-info-api-openapi.yml
  format: yaml
  label: Apuchat Info API
  slug: apuchat-com-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apuchat-com/openapi/apuchat-com-info-api-openapi.yml
- filename: apuchat-com-stats-api-openapi.yml
  format: yaml
  label: Apuchat Stats API
  slug: apuchat-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apuchat-com/openapi/apuchat-com-stats-api-openapi.yml
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
  restricted_uses:
  - summary: Prohibited uses under acceptable use section
    text: 'do not use apuchat to: break the law, or to harass, threaten or impersonate anyone'
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
name: Apuchat
provenance_date: '2026-11-09'
provider_name: Apuchat
provider_slug: apuchat-com
slug: apuchat-com-eligibility
source_date: '2026-11-09'
source_filename: apuchat-com-eligibility.yml
source_heading: Eligibility
source_page: https://apuchat.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apuchat\naid: apuchat-com\nurl: https://apuchat.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses under acceptable use section\n  text: 'do not use apuchat to: break the law, or to harass, threaten or impersonate anyone'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apuchat-com/eligibility/apuchat-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Apuchat's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Communications
- Multi-Agent
- MCP
- Chat
---
