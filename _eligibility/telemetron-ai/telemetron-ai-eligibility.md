---
api_specs:
- filename: telemetron-ai-customer-api-openapi.yml
  format: yaml
  label: Telemetron Customer API
  slug: telemetron-ai-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telemetron-ai/openapi/telemetron-ai-customer-api-openapi.yml
- filename: telemetron-ai-device-api-openapi.yml
  format: yaml
  label: Telemetron Device API
  slug: telemetron-ai-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telemetron-ai/openapi/telemetron-ai-device-api-openapi.yml
- filename: telemetron-ai-device-assignment-api-openapi.yml
  format: yaml
  label: Telemetron Device Assignment API
  slug: telemetron-ai-device-assignment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telemetron-ai/openapi/telemetron-ai-device-assignment-api-openapi.yml
- filename: telemetron-ai-ticket-api-openapi.yml
  format: yaml
  label: Telemetron Ticket API
  slug: telemetron-ai-ticket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telemetron-ai/openapi/telemetron-ai-ticket-api-openapi.yml
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
  - summary: Spam or bulk messaging
    text: Send unsolicited or unauthorized communications, including spam or bulk messaging.
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
name: Telemetron
provenance_date: '2026-11-10'
provider_name: Telemetron
provider_slug: telemetron-ai
slug: telemetron-ai-eligibility
source_date: '2026-11-10'
source_filename: telemetron-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.telemetron.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Telemetron\naid: telemetron-ai\nurl: https://www.telemetron.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spam or bulk messaging\n  text: Send unsolicited or unauthorized communications, including spam or bulk messaging.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/telemetron-ai/eligibility/telemetron-ai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Telemetron's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Customer Service
- IoT
- Hardware
- Telemetry
- Support Tickets
- MCP
---
