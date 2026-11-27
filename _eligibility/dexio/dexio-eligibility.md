---
api_specs:
- filename: dexio-dexio-api-api-openapi.yml
  format: yaml
  label: Dexio Dexio API
  slug: dexio-dexio-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexio/openapi/dexio-dexio-api-api-openapi.yml
- filename: dexio-install-api-openapi.yml
  format: yaml
  label: Dexio Install API
  slug: dexio-install-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexio/openapi/dexio-install-api-openapi.yml
- filename: dexio-mcp-api-openapi.yml
  format: yaml
  label: Dexio MCP API
  slug: dexio-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexio/openapi/dexio-mcp-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use it for an organization, you agree on its behalf and confirm you are allowed to.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Prohibited uses
    text: 'Do not use the Service to: break the law or infringe anyone''s rights; store or share malware, or content that exploits or harms children'
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
name: Dexio
provenance_date: '2026-11-09'
provider_name: Dexio
provider_slug: dexio
slug: dexio-eligibility
source_date: '2026-11-09'
source_filename: dexio-eligibility.yml
source_heading: Eligibility
source_page: https://dexio.wiki/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dexio\naid: dexio\nurl: https://dexio.wiki/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use it for an organization, you agree on its behalf and confirm you are allowed to.\nrestricted_uses:\n- summary: Prohibited uses\n  text: 'Do not use the Service to: break the law or infringe anyone''s rights; store or share malware, or content\n    that exploits or harms children'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years\
  \ old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/dexio/eligibility/dexio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Dexio's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Wiki
- Knowledge Management
- Agent Integration
- Open Source
---
