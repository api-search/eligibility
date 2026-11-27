---
api_specs:
- filename: brofindai-com-agents-api-openapi.yml
  format: yaml
  label: Bro Find AI Agents API
  slug: brofindai-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-agents-api-openapi.yml
- filename: brofindai-com-badge-api-openapi.yml
  format: yaml
  label: Bro Find AI Badge API
  slug: brofindai-com-badge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-badge-api-openapi.yml
- filename: brofindai-com-comments-api-openapi.yml
  format: yaml
  label: Bro Find AI Comments API
  slug: brofindai-com-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-comments-api-openapi.yml
- filename: brofindai-com-feedback-api-openapi.yml
  format: yaml
  label: Bro Find AI Feedback API
  slug: brofindai-com-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-feedback-api-openapi.yml
- filename: brofindai-com-mcp-servers-api-openapi.yml
  format: yaml
  label: Bro Find AI MCP Servers API
  slug: brofindai-com-mcp-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-mcp-servers-api-openapi.yml
- filename: brofindai-com-reviews-api-openapi.yml
  format: yaml
  label: Bro Find AI Reviews API
  slug: brofindai-com-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-reviews-api-openapi.yml
- filename: brofindai-com-search-api-openapi.yml
  format: yaml
  label: Bro Find AI Search API
  slug: brofindai-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-search-api-openapi.yml
- filename: brofindai-com-tools-api-openapi.yml
  format: yaml
  label: Bro Find AI Tools API
  slug: brofindai-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-tools-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must provide accurate information and be at least 13 years old to create an account.
    type: individual
  minimum_age:
    text: be at least 13 years old to create an account
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: Use the site for any unlawful purpose or to post misleading or harmful content.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Some features require signing in with Google.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bro Find AI
provenance_date: '2026-11-09'
provider_name: Bro Find AI
provider_slug: brofindai-com
slug: brofindai-com-eligibility
source_date: '2026-11-09'
source_filename: brofindai-com-eligibility.yml
source_heading: Eligibility
source_page: https://brofindai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bro Find AI\naid: brofindai-com\nurl: https://brofindai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must provide accurate information and be at least 13 years old to create an account.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: Use the site for any unlawful purpose or to post misleading or harmful content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Some features require signing in with Google.\nminimum_age:\n  value: '13'\n  text: be at least 13 years old to\
  \ create an account\n"
source_yaml_url: https://artifacts.apis.io/brofindai-com/eligibility/brofindai-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bro Find AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Directory
- Tools
- Marketplace
- Company
---
