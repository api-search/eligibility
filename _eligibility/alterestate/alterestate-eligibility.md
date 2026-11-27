---
api_specs:
- filename: alterestate-agents-api-openapi.yml
  format: yaml
  label: AlterEstate Agents API
  slug: alterestate-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alterestate/openapi/alterestate-agents-api-openapi.yml
- filename: alterestate-developments-api-openapi.yml
  format: yaml
  label: AlterEstate Developments API
  slug: alterestate-developments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alterestate/openapi/alterestate-developments-api-openapi.yml
- filename: alterestate-leads-api-openapi.yml
  format: yaml
  label: AlterEstate Leads API
  slug: alterestate-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alterestate/openapi/alterestate-leads-api-openapi.yml
- filename: alterestate-locations-api-openapi.yml
  format: yaml
  label: AlterEstate Locations API
  slug: alterestate-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alterestate/openapi/alterestate-locations-api-openapi.yml
- filename: alterestate-properties-api-openapi.yml
  format: yaml
  label: AlterEstate Properties API
  slug: alterestate-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alterestate/openapi/alterestate-properties-api-openapi.yml
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
  - summary: Unauthorized extraction of platform data
    text: Queda estrictamente prohibido
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
name: AlterEstate
provenance_date: '2026-11-09'
provider_name: AlterEstate
provider_slug: alterestate
slug: alterestate-eligibility
source_date: '2026-11-09'
source_filename: alterestate-eligibility.yml
source_heading: Eligibility
source_page: https://alterestate.com/do/terminos-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AlterEstate\naid: alterestate\nurl: https://alterestate.com/do/terminos-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized extraction of platform data\n  text: Queda estrictamente prohibido\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alterestate/eligibility/alterestate-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AlterEstate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- CRM
- Property Management
- Lead Management
- Latin America
- Software-as-a-Service
- Artificial Intelligence
- MCP
---
