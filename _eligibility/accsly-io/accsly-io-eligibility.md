---
api_specs:
- filename: accsly-io-accounts-api-openapi.yml
  format: yaml
  label: Accsly Accounts API
  slug: accsly-io-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accsly-io/openapi/accsly-io-accounts-api-openapi.yml
- filename: accsly-io-markdown-pages-api-openapi.yml
  format: yaml
  label: Accsly Markdown pages API
  slug: accsly-io-markdown-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accsly-io/openapi/accsly-io-markdown-pages-api-openapi.yml
- filename: accsly-io-mcp-api-openapi.yml
  format: yaml
  label: Accsly MCP API
  slug: accsly-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accsly-io/openapi/accsly-io-mcp-api-openapi.yml
- filename: accsly-io-vps-api-openapi.yml
  format: yaml
  label: Accsly VPS API
  slug: accsly-io-vps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accsly-io/openapi/accsly-io-vps-api-openapi.yml
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
  - summary: Unlawful activity
    text: Сервис не предназначен для противоправной деятельности.
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
name: Accsly
provenance_date: '2026-11-09'
provider_name: Accsly
provider_slug: accsly-io
slug: accsly-io-eligibility
source_date: '2026-11-09'
source_filename: accsly-io-eligibility.yml
source_heading: Eligibility
source_page: https://accsly.io/ru/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Accsly\naid: accsly-io\nurl: https://accsly.io/ru/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful activity\n  text: Сервис не предназначен для противоправной деятельности.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/accsly-io/eligibility/accsly-io-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Accsly's own page on 2026-11-09.
synthetic: false
tags:
- Marketplace
- Account
- Gaming
- AI Tools
- E-Commerce
---
