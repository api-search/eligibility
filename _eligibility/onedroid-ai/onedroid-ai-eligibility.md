---
api_specs:
- filename: onedroid-ai-api-openapi.json
  format: json
  label: Trilix MCP Assistant Api API
  slug: trilix-mcp-assistant-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onedroid-ai/openapi/_original/onedroid-ai-api-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you can bind that organization.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Export-control and sanctions
    text: You may not use the Service in violation of export-control or sanctions laws.
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
name: onedroid-ai
provenance_date: '2026-11-10'
provider_name: onedroid-ai
provider_slug: onedroid-ai
slug: onedroid-ai-eligibility
source_date: '2026-11-10'
source_filename: onedroid-ai-eligibility.yml
source_heading: Eligibility
source_page: https://onedroid.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: onedroid-ai\naid: onedroid-ai\nurl: https://onedroid.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you can bind that organization.\nrestricted_uses:\n- summary: Export-control and sanctions\n  text: You may not use the Service in violation of export-control or sanctions laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/onedroid-ai/eligibility/onedroid-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from onedroid-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Testing
- Automation
- End-to-End
---
