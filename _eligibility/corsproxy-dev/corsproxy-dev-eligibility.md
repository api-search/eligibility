---
api_specs:
- filename: corsproxy-dev-health-api-openapi.yml
  format: yaml
  label: corsproxy-dev Health API
  slug: corsproxy-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corsproxy-dev/openapi/corsproxy-dev-health-api-openapi.yml
- filename: corsproxy-dev-mcp-api-openapi.yml
  format: yaml
  label: corsproxy-dev MCP API
  slug: corsproxy-dev-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corsproxy-dev/openapi/corsproxy-dev-mcp-api-openapi.yml
- filename: corsproxy-dev-proxy-api-openapi.yml
  format: yaml
  label: corsproxy-dev Proxy API
  slug: corsproxy-dev-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corsproxy-dev/openapi/corsproxy-dev-proxy-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old to use this Service
    value: '13'
  restricted_uses:
  - summary: Illegal or harmful purposes
    text: You may not use the Service for illegal or harmful purposes
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
name: corsproxy-dev
provenance_date: '2026-11-09'
provider_name: corsproxy-dev
provider_slug: corsproxy-dev
slug: corsproxy-dev-eligibility
source_date: '2026-11-09'
source_filename: corsproxy-dev-eligibility.yml
source_heading: Eligibility
source_page: https://corsproxy.dev/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: corsproxy-dev\naid: corsproxy-dev\nurl: https://corsproxy.dev/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or harmful purposes\n  text: You may not use the Service for illegal or harmful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use this Service\n"
source_yaml_url: https://artifacts.apis.io/corsproxy-dev/eligibility/corsproxy-dev-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from corsproxy-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CORS
- Proxy
- Developer Tools
- Open Source
---
