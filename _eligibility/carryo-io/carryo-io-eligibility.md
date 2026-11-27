---
api_specs:
- filename: carryo-io-health-api-openapi.yml
  format: yaml
  label: Carryo Health API
  slug: carryo-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carryo-io/openapi/carryo-io-health-api-openapi.yml
- filename: carryo-io-mcp-api-openapi.yml
  format: yaml
  label: Carryo MCP API
  slug: carryo-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carryo-io/openapi/carryo-io-mcp-api-openapi.yml
- filename: carryo-io-well-known-api-openapi.yml
  format: yaml
  label: Carryo .well Known API
  slug: carryo-io-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carryo-io/openapi/carryo-io-well-known-api-openapi.yml
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
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may use Carryo only through supported authentication methods and only if you are authorized to use the service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Carryo
provenance_date: '2026-11-09'
provider_name: Carryo
provider_slug: carryo-io
slug: carryo-io-eligibility
source_date: '2026-11-09'
source_filename: carryo-io-eligibility.yml
source_heading: Eligibility
source_page: https://carryo.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carryo\naid: carryo-io\nurl: https://carryo.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may use Carryo only through supported authentication methods and only if you are authorized to use the\n    service.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/carryo-io/eligibility/carryo-io-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Carryo's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Website Publishing
- Content Generation
- Software-as-a-Service
- Low-Code
---
