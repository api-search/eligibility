---
api_specs:
- filename: monitly-charts-api-openapi.yml
  format: yaml
  label: Monitly Charts API
  slug: monitly-charts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monitly/openapi/monitly-charts-api-openapi.yml
- filename: monitly-datasets-api-openapi.yml
  format: yaml
  label: Monitly Datasets API
  slug: monitly-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monitly/openapi/monitly-datasets-api-openapi.yml
- filename: monitly-mcp-api-openapi.yml
  format: yaml
  label: Monitly MCP API
  slug: monitly-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monitly/openapi/monitly-mcp-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users must be at least 18 years old or have parental consent to use the service.
    type: individual
  minimum_age:
    text: Users must be at least 18 years old or have parental consent to use the service.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: Use the service for any illegal or unauthorized purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access certain features of Monitly, users must create an account by providing accurate and complete information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Monitly
provenance_date: '2026-11-10'
provider_name: Monitly
provider_slug: monitly
slug: monitly-eligibility
source_date: '2026-11-10'
source_filename: monitly-eligibility.yml
source_heading: Eligibility
source_page: https://monit.ly/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Monitly\naid: monitly\nurl: https://monit.ly/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users must be at least 18 years old or have parental consent to use the service.\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: Use the service for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access certain features of Monitly, users must create an account by providing accurate and complete information.\nminimum_age:\n  value: '18'\n  text: Users\
  \ must be at least 18 years old or have parental consent to use the service.\n"
source_yaml_url: https://artifacts.apis.io/monitly/eligibility/monitly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Monitly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Statistics
- Dashboards
---
