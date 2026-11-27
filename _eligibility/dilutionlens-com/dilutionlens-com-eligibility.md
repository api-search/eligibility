---
api_specs:
- filename: dilutionlens-com-company-api-openapi.yml
  format: yaml
  label: DilutionLens Company API
  slug: dilutionlens-com-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dilutionlens-com/openapi/dilutionlens-com-company-api-openapi.yml
- filename: dilutionlens-com-screen-api-openapi.yml
  format: yaml
  label: DilutionLens Screen API
  slug: dilutionlens-com-screen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dilutionlens-com/openapi/dilutionlens-com-screen-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An account is personal to you. Do not share it, sell access to it, or run it on behalf of several people.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No account sharing or resale
    text: Do not share it, sell access to it, or run it on behalf of several people.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You create it by giving an email address and clicking the link we send; there is no password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DilutionLens
provenance_date: '2026-11-09'
provider_name: DilutionLens
provider_slug: dilutionlens-com
slug: dilutionlens-com-eligibility
source_date: '2026-11-09'
source_filename: dilutionlens-com-eligibility.yml
source_heading: Eligibility
source_page: https://dilutionlens.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DilutionLens\naid: dilutionlens-com\nurl: https://dilutionlens.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An account is personal to you. Do not share it, sell access to it, or run it on behalf of several people.\nrestricted_uses:\n- summary: No account sharing or resale\n  text: Do not share it, sell access to it, or run it on behalf of several people.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You create it by giving an email address and clicking the link we send; there is no password.\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dilutionlens-com/eligibility/dilutionlens-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from DilutionLens's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Data
- Capital Markets
- ASX
- Equity Dilution
- Market Data
- MCP
- Investing
---
