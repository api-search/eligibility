---
api_specs:
- filename: paidsync-ai-billing-api-openapi.yml
  format: yaml
  label: paidsync-ai Billing API
  slug: paidsync-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidsync-ai/openapi/paidsync-ai-billing-api-openapi.yml
- filename: paidsync-ai-mcp-api-openapi.yml
  format: yaml
  label: paidsync-ai MCP API
  slug: paidsync-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidsync-ai/openapi/paidsync-ai-mcp-api-openapi.yml
- filename: paidsync-ai-paidsync-api-api-openapi.yml
  format: yaml
  label: paidsync-ai PaidSync API
  slug: paidsync-ai-paidsync-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidsync-ai/openapi/paidsync-ai-paidsync-api-api-openapi.yml
- filename: paidsync-ai-payment-api-openapi.yml
  format: yaml
  label: paidsync-ai Payment API
  slug: paidsync-ai-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidsync-ai/openapi/paidsync-ai-payment-api-openapi.yml
- filename: paidsync-ai-subscribe-api-openapi.yml
  format: yaml
  label: paidsync-ai Subscribe API
  slug: paidsync-ai-subscribe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidsync-ai/openapi/paidsync-ai-subscribe-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use PaidSync.ai.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use PaidSync.ai.
    value: '18'
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
name: paidsync-ai
provenance_date: '2026-11-10'
provider_name: paidsync-ai
provider_slug: paidsync-ai
slug: paidsync-ai-eligibility
source_date: '2026-11-10'
source_filename: paidsync-ai-eligibility.yml
source_heading: Eligibility
source_page: https://paidsync.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: paidsync-ai\naid: paidsync-ai\nurl: https://paidsync.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use PaidSync.ai.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use PaidSync.ai.\n"
source_yaml_url: https://artifacts.apis.io/paidsync-ai/eligibility/paidsync-ai-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from paidsync-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Advertising
- Automation
- Marketing
---
