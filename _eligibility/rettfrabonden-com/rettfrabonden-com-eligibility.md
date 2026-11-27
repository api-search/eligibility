---
api_specs:
- filename: rettfrabonden-com-a2a-api-openapi.yml
  format: yaml
  label: Rett fra Bonden A2a API
  slug: rettfrabonden-com-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rettfrabonden-com/openapi/rettfrabonden-com-a2a-api-openapi.yml
- filename: rettfrabonden-com-marketplace-api-openapi.yml
  format: yaml
  label: Rett fra Bonden Marketplace API
  slug: rettfrabonden-com-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rettfrabonden-com/openapi/rettfrabonden-com-marketplace-api-openapi.yml
- filename: rettfrabonden-com-mcp-api-openapi.yml
  format: yaml
  label: Rett fra Bonden MCP API
  slug: rettfrabonden-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rettfrabonden-com/openapi/rettfrabonden-com-mcp-api-openapi.yml
- filename: rettfrabonden-com-stats-api-openapi.yml
  format: yaml
  label: Rett fra Bonden Stats API
  slug: rettfrabonden-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rettfrabonden-com/openapi/rettfrabonden-com-stats-api-openapi.yml
- filename: rettfrabonden-com-well-known-api-openapi.yml
  format: yaml
  label: Rett fra Bonden .well Known API
  slug: rettfrabonden-com-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rettfrabonden-com/openapi/rettfrabonden-com-well-known-api-openapi.yml
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
  - summary: Unlawful or Norwegian-law-violating use
    text: Using the service for unlawful activity or activity that violates Norwegian law.
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
name: Rett fra Bonden
provenance_date: '2026-11-10'
provider_name: Rett fra Bonden
provider_slug: rettfrabonden-com
slug: rettfrabonden-com-eligibility
source_date: '2026-11-10'
source_filename: rettfrabonden-com-eligibility.yml
source_heading: Eligibility
source_page: https://rettfrabonden.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rett fra Bonden\naid: rettfrabonden-com\nurl: https://rettfrabonden.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or Norwegian-law-violating use\n  text: Using the service for unlawful activity or activity that violates Norwegian law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rettfrabonden-com/eligibility/rettfrabonden-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Rett fra Bonden's own page on 2026-11-10.
synthetic: false
tags:
- Local Food
- Agriculture
- Food
- Marketplace
- Directory
- Search
- Geolocation
- A2A
- MCP
- Norway
- Open Source
- Company
---
