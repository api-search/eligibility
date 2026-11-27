---
api_specs:
- filename: betterstack-heartbeats-api-openapi.yml
  format: yaml
  label: Better Stack Heartbeats API
  slug: betterstack-heartbeats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterstack/openapi/betterstack-heartbeats-api-openapi.yml
- filename: betterstack-incidents-api-openapi.yml
  format: yaml
  label: Better Stack Incidents API
  slug: betterstack-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterstack/openapi/betterstack-incidents-api-openapi.yml
- filename: betterstack-monitors-api-openapi.yml
  format: yaml
  label: Better Stack Monitors API
  slug: betterstack-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterstack/openapi/betterstack-monitors-api-openapi.yml
- filename: betterstack-status-pages-api-openapi.yml
  format: yaml
  label: Better Stack Status Pages API
  slug: betterstack-status-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterstack/openapi/betterstack-status-pages-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is available only to individuals who are at least 13 years old.
    type: individual
  minimum_age:
    text: The Website is available only to individuals who are at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Special categories of personal data
    text: use the Website to collect, store, process, or transmit any special categories of personal data or similarly protected information.
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
name: Better Stack
provenance_date: '2026-11-09'
provider_name: Better Stack
provider_slug: betterstack
slug: betterstack-eligibility
source_date: '2026-11-09'
source_filename: betterstack-eligibility.yml
source_heading: Eligibility
source_page: https://betterstack.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Better Stack\naid: betterstack\nurl: https://betterstack.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is available only to individuals who are at least 13 years old.\nrestricted_uses:\n- summary: Special categories of personal data\n  text: use the Website to collect, store, process, or transmit any special categories of personal data or similarly\n    protected information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Website is\
  \ available only to individuals who are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/betterstack/eligibility/betterstack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Better Stack's own page on 2026-11-09.
synthetic: false
tags:
- Observability
- Uptime Monitoring
- Incidents
- Logs
- Monitoring
- Status Pages
- On-Call
- Error Tracking
- OpenTelemetry
- MCP
---
