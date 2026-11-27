---
api_specs:
- filename: creatica-app-backgrounds-api-openapi.yml
  format: yaml
  label: Creatica Backgrounds API
  slug: creatica-app-backgrounds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/creatica-app/openapi/creatica-app-backgrounds-api-openapi.yml
- filename: creatica-app-generate-api-openapi.yml
  format: yaml
  label: Creatica Generate API
  slug: creatica-app-generate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/creatica-app/openapi/creatica-app-generate-api-openapi.yml
- filename: creatica-app-mcp-api-openapi.yml
  format: yaml
  label: Creatica MCP API
  slug: creatica-app-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/creatica-app/openapi/creatica-app-mcp-api-openapi.yml
- filename: creatica-app-palettes-api-openapi.yml
  format: yaml
  label: Creatica Palettes API
  slug: creatica-app-palettes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/creatica-app/openapi/creatica-app-palettes-api-openapi.yml
- filename: creatica-app-render-api-openapi.yml
  format: yaml
  label: Creatica Render API
  slug: creatica-app-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/creatica-app/openapi/creatica-app-render-api-openapi.yml
- filename: creatica-app-suggest-api-openapi.yml
  format: yaml
  label: Creatica Suggest API
  slug: creatica-app-suggest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/creatica-app/openapi/creatica-app-suggest-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Users must be at least 13 years old to use the app.
    value: '13'
  restricted_uses:
  - summary: Responsible and lawful use
    text: Users must use the app in a responsible and lawful manner.
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
name: Creatica
provenance_date: '2026-11-09'
provider_name: Creatica
provider_slug: creatica-app
slug: creatica-app-eligibility
source_date: '2026-11-09'
source_filename: creatica-app-eligibility.yml
source_heading: Eligibility
source_page: https://creatica.app/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Creatica\naid: creatica-app\nurl: https://creatica.app/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Responsible and lawful use\n  text: Users must use the app in a responsible and lawful manner.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Users must be at least 13 years old to use the app.\n"
source_yaml_url: https://artifacts.apis.io/creatica-app/eligibility/creatica-app-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Creatica's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SVG
- Backgrounds
- Design Tools
- Image Generation
- Generative Art
- MCP
- CLI
- Open Source
---
