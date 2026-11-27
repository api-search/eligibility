---
api_specs:
- filename: tracebit-alerts-api-openapi.yml
  format: yaml
  label: Tracebit Alerts API
  slug: tracebit-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracebit/openapi/tracebit-alerts-api-openapi.yml
- filename: tracebit-canary-credentials-api-openapi.yml
  format: yaml
  label: Tracebit Canary Credentials API
  slug: tracebit-canary-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracebit/openapi/tracebit-canary-credentials-api-openapi.yml
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
  - summary: Use to build a competing product
    text: (c) use the Tracebit Platform or Tracebit Confidential Information to develop a product or service that competes with Tracebit’s
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
name: Tracebit
provenance_date: '2026-11-10'
provider_name: Tracebit
provider_slug: tracebit
slug: tracebit-eligibility
source_date: '2026-11-10'
source_filename: tracebit-eligibility.yml
source_heading: Eligibility
source_page: https://tracebit.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tracebit\naid: tracebit\nurl: https://tracebit.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use to build a competing product\n  text: (c) use the Tracebit Platform or Tracebit Confidential Information to develop a product or service that\n    competes with Tracebit’s\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tracebit/eligibility/tracebit-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Tracebit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Security
- Deception
- Canary Tokens
- Threat Detection
- Cloud Security
- Incident Response
---
