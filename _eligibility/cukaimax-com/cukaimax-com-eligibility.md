---
api_specs:
- filename: cukaimax-com-ask-api-openapi.yml
  format: yaml
  label: CukaiMax Ask API
  slug: cukaimax-com-ask-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cukaimax-com/openapi/cukaimax-com-ask-api-openapi.yml
- filename: cukaimax-com-capabilities-api-openapi.yml
  format: yaml
  label: CukaiMax Capabilities API
  slug: cukaimax-com-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cukaimax-com/openapi/cukaimax-com-capabilities-api-openapi.yml
- filename: cukaimax-com-tax-reliefs-api-openapi.yml
  format: yaml
  label: CukaiMax Tax Reliefs API
  slug: cukaimax-com-tax-reliefs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cukaimax-com/openapi/cukaimax-com-tax-reliefs-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - MY
    text: You must be at least 18 years old and a Malaysian taxpayer to use the Service.
  entity_types:
  - text: You must be at least 18 years old and a Malaysian taxpayer to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and a Malaysian taxpayer to use the Service.
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: Not use the Service for illegal purposes
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
name: CukaiMax
provenance_date: '2026-11-09'
provider_name: CukaiMax
provider_slug: cukaimax-com
slug: cukaimax-com-eligibility
source_date: '2026-11-09'
source_filename: cukaimax-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.cukaimax.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CukaiMax\naid: cukaimax-com\nurl: https://www.cukaimax.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MY\n  excluded: []\n  text: You must be at least 18 years old and a Malaysian taxpayer to use the Service.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and a Malaysian taxpayer to use the Service.\nrestricted_uses:\n- summary: Illegal purposes\n  text: Not use the Service for illegal purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and a Malaysian\
  \ taxpayer to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cukaimax-com/eligibility/cukaimax-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CukaiMax's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Tax
- Personal Finance
- Malaysia
- Receipts
- Efiling
- MCP
- AI Agents
---
