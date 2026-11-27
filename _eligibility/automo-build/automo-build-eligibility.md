---
api_specs:
- filename: automo-build-agent-api-openapi.yml
  format: yaml
  label: Automo Agent API
  slug: automo-build-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/automo-build/openapi/automo-build-agent-api-openapi.yml
- filename: automo-build-mcp-api-openapi.yml
  format: yaml
  label: Automo MCP API
  slug: automo-build-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/automo-build/openapi/automo-build-mcp-api-openapi.yml
- filename: automo-build-oauth-api-openapi.yml
  format: yaml
  label: Automo OAuth API
  slug: automo-build-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/automo-build/openapi/automo-build-oauth-api-openapi.yml
- filename: automo-build-openapi-json-api-openapi.yml
  format: yaml
  label: Automo Openapi.json API
  slug: automo-build-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/automo-build/openapi/automo-build-openapi-json-api-openapi.yml
- filename: automo-build-well-known-api-openapi.yml
  format: yaml
  label: Automo .well Known API
  slug: automo-build-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/automo-build/openapi/automo-build-well-known-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of an organisation, you represent that you have the authority to bind that organisation to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Misleading or harmful AI content
    text: You must not use AI features to generate content that is misleading, harmful, illegal, or in violation of our Acceptable Use Policy.
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
name: Automo
provenance_date: '2026-11-09'
provider_name: Automo
provider_slug: automo-build
slug: automo-build-eligibility
source_date: '2026-11-09'
source_filename: automo-build-eligibility.yml
source_heading: Eligibility
source_page: https://automo.build/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Automo\naid: automo-build\nurl: https://automo.build/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organisation, you represent that you have the authority to\n    bind that organisation to these Terms.\nrestricted_uses:\n- summary: Misleading or harmful AI content\n  text: You must not use AI features to generate content that is misleading, harmful, illegal, or in violation of\n    our Acceptable Use Policy.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/automo-build/eligibility/automo-build-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Automo's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Platform
- Low-Code
- Automation
- Software Development
---
