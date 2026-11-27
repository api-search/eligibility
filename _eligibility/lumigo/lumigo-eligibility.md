---
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
  - summary: No sensitive data
    text: Customer shall not provide Dash0, or input or upload to the Service or use the Service to collect, any Sensitive Data (defined below)
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
name: Lumigo
provenance_date: '2026-11-10'
provider_name: Lumigo
provider_slug: lumigo
slug: lumigo-eligibility
source_date: '2026-11-10'
source_filename: lumigo-eligibility.yml
source_heading: Eligibility
source_page: https://lumigo.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lumigo\naid: lumigo\nurl: https://lumigo.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No sensitive data\n  text: Customer shall not provide Dash0, or input or upload to the Service or use the Service to collect, any Sensitive\n    Data (defined below)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lumigo/eligibility/lumigo-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Lumigo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Observability
- Monitoring
- Serverless
- Distributed Tracing
- OpenTelemetry
- AWS Lambda
- Microservices
- Logs
---
