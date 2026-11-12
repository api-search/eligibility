---
api_specs:
- filename: compatlab-me-packages-api-openapi.yml
  format: yaml
  label: CompatLab Packages API
  slug: compatlab-me-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compatlab-me/openapi/compatlab-me-packages-api-openapi.yml
- filename: compatlab-me-reports-api-openapi.yml
  format: yaml
  label: CompatLab Reports API
  slug: compatlab-me-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compatlab-me/openapi/compatlab-me-reports-api-openapi.yml
- filename: compatlab-me-scans-api-openapi.yml
  format: yaml
  label: CompatLab Scans API
  slug: compatlab-me-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compatlab-me/openapi/compatlab-me-scans-api-openapi.yml
- filename: compatlab-me-search-api-openapi.yml
  format: yaml
  label: CompatLab Search API
  slug: compatlab-me-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compatlab-me/openapi/compatlab-me-search-api-openapi.yml
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
  - summary: No anonymous custom code or private uploads
    text: Anonymous custom code and private package uploads are not supported.
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
name: CompatLab
provenance_date: '2026-11-09'
provider_name: CompatLab
provider_slug: compatlab-me
slug: compatlab-me-eligibility
source_date: '2026-11-09'
source_filename: compatlab-me-eligibility.yml
source_heading: Eligibility
source_page: https://compatlab.me/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CompatLab\naid: compatlab-me\nurl: https://compatlab.me/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No anonymous custom code or private uploads\n  text: Anonymous custom code and private package uploads are not supported.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/compatlab-me/eligibility/compatlab-me-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from CompatLab's own page on 2026-11-09.
synthetic: false
tags:
- Company
- npm
- JavaScript
- Node.js
- Bun
- Deno
- Compatibility Testing
- Developer Tools
- Open Source
- MCP
---
