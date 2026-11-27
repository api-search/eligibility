---
api_specs:
- filename: codehooks-events-asyncapi.yml
  format: yaml
  label: Codehooks Events (AsyncAPI)
  slug: codehooks-events
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/codehooks/asyncapi/codehooks-events-asyncapi.yml
- filename: codehooks-documents-api-openapi.yml
  format: yaml
  label: Codehooks Documents API
  slug: codehooks-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codehooks/openapi/codehooks-documents-api-openapi.yml
- filename: codehooks-key-value-store-api-openapi.yml
  format: yaml
  label: Codehooks Key-Value Store API
  slug: codehooks-key-value-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codehooks/openapi/codehooks-key-value-store-api-openapi.yml
- filename: codehooks-queue-api-openapi.yml
  format: yaml
  label: Codehooks Queue API
  slug: codehooks-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codehooks/openapi/codehooks-queue-api-openapi.yml
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
  - summary: Unlawful or infringing content
    text: 'You represent and warrant that: (i) the Content is yours (you own it) or you have the right to use it'
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
name: Codehooks
provenance_date: '2026-11-09'
provider_name: Codehooks
provider_slug: codehooks
slug: codehooks-eligibility
source_date: '2026-11-09'
source_filename: codehooks-eligibility.yml
source_heading: Eligibility
source_page: https://codehooks.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Codehooks\naid: codehooks\nurl: https://codehooks.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: 'You represent and warrant that: (i) the Content is yours (you own it) or you have the right to use it'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/codehooks/eligibility/codehooks-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Codehooks's own page on 2026-11-09.
synthetic: false
tags:
- Backend
- Database
- Event
- Hooks
- JavaScript
- NoSQL
- Queues
- Serverless
- Webhook
- Workers
- Workflows
---
