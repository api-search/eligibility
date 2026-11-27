---
api_specs:
- filename: apimesh-xyz-apimesh-api-openapi.yml
  format: yaml
  label: APIMesh API Mesh API
  slug: apimesh-xyz-apimesh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apimesh-xyz/openapi/apimesh-xyz-apimesh-api-openapi.yml
- filename: apimesh-xyz-health-api-openapi.yml
  format: yaml
  label: APIMesh Health API
  slug: apimesh-xyz-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apimesh-xyz/openapi/apimesh-xyz-health-api-openapi.yml
- filename: apimesh-xyz-preview-api-openapi.yml
  format: yaml
  label: APIMesh Preview API
  slug: apimesh-xyz-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apimesh-xyz/openapi/apimesh-xyz-preview-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per person; shared accounts are not permitted.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: APIMesh
provenance_date: '2026-11-09'
provider_name: APIMesh
provider_slug: apimesh-xyz
slug: apimesh-xyz-eligibility
source_date: '2026-11-09'
source_filename: apimesh-xyz-eligibility.yml
source_heading: Eligibility
source_page: https://apimesh.xyz/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: APIMesh\naid: apimesh-xyz\nurl: https://apimesh.xyz/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account per person; shared accounts are not permitted.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apimesh-xyz/eligibility/apimesh-xyz-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from APIMesh's own page on 2026-11-09.
synthetic: false
tags:
- Web Analysis
- SEO
- Web Security
- Email Verification
- Developer Tools
- Micropayments
- x402
- MCP
- Agent-Native
- Webhook
- AI Coding Agents
- Open Source
- A2A
---
