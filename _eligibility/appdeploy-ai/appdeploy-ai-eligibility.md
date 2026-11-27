---
api_specs:
- filename: appdeploy-ai-mcp-api-openapi.yml
  format: yaml
  label: appdeploy-ai MCP API
  slug: appdeploy-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appdeploy-ai/openapi/appdeploy-ai-mcp-api-openapi.yml
- filename: appdeploy-ai-oauth-discovery-api-openapi.yml
  format: yaml
  label: appdeploy-ai OAuth discovery API
  slug: appdeploy-ai-oauth-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appdeploy-ai/openapi/appdeploy-ai-oauth-discovery-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Adult, gambling, weapons and similar content
    text: deploy apps containing adult or sexually explicit content, gambling or betting services, sale of weapons, controlled substances or tobacco products
  - summary: HIPAA PHI without a BAA
    text: You must not use the Service to create, receive, maintain, transmit or otherwise process "Protected Health Information"
  - summary: Government ID numbers
    text: Government identification numbers may be processed only as described below.
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
name: appdeploy-ai
provenance_date: '2026-11-09'
provider_name: appdeploy-ai
provider_slug: appdeploy-ai
slug: appdeploy-ai-eligibility
source_date: '2026-11-09'
source_filename: appdeploy-ai-eligibility.yml
source_heading: Eligibility
source_page: https://appdeploy.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: appdeploy-ai\naid: appdeploy-ai\nurl: https://appdeploy.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\nrestricted_uses:\n- summary: Adult, gambling, weapons and similar content\n  text: deploy apps containing adult or sexually explicit content, gambling or betting services, sale of weapons,\n    controlled substances or tobacco products\n- summary: HIPAA PHI without a BAA\n  text: You must not use the Service to create, receive, maintain, transmit or otherwise process\
  \ \"Protected Health\n    Information\"\n- summary: Government ID numbers\n  text: Government identification numbers may be processed only as described below.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/appdeploy-ai/eligibility/appdeploy-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from appdeploy-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Deployment
- Platform
- Low-Code
- Automation
---
