---
api_specs:
- filename: ioconnex-dev-affiliate-api-openapi.yml
  format: yaml
  label: ioconnex-dev Affiliate API
  slug: ioconnex-dev-affiliate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-affiliate-api-openapi.yml
- filename: ioconnex-dev-billing-api-openapi.yml
  format: yaml
  label: ioconnex-dev Billing API
  slug: ioconnex-dev-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-billing-api-openapi.yml
- filename: ioconnex-dev-convert-api-openapi.yml
  format: yaml
  label: ioconnex-dev Convert API
  slug: ioconnex-dev-convert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-convert-api-openapi.yml
- filename: ioconnex-dev-fetch-api-openapi.yml
  format: yaml
  label: ioconnex-dev Fetch API
  slug: ioconnex-dev-fetch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-fetch-api-openapi.yml
- filename: ioconnex-dev-health-api-openapi.yml
  format: yaml
  label: ioconnex-dev Health API
  slug: ioconnex-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-health-api-openapi.yml
- filename: ioconnex-dev-paid-api-openapi.yml
  format: yaml
  label: ioconnex-dev Paid API
  slug: ioconnex-dev-paid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-paid-api-openapi.yml
- filename: ioconnex-dev-price-api-openapi.yml
  format: yaml
  label: ioconnex-dev Price API
  slug: ioconnex-dev-price-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-price-api-openapi.yml
- filename: ioconnex-dev-search-api-openapi.yml
  format: yaml
  label: ioconnex-dev Search API
  slug: ioconnex-dev-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-search-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you access the Services on behalf of a company, organization, or other entity, you represent and warrant that you have full authority to bind that entity, and "you" means that entity.
    type: business
  - text: You must be at least 18 years old and capable of forming a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract.
    value: '18'
  restricted_uses:
  - summary: Sanctions and export-control compliance
    text: Use the Services in violation of any applicable law or regulation, including sanctions administered by OFAC and applicable export-control laws;
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
name: ioconnex-dev
provenance_date: '2026-11-09'
provider_name: ioconnex-dev
provider_slug: ioconnex-dev
slug: ioconnex-dev-eligibility
source_date: '2026-11-09'
source_filename: ioconnex-dev-eligibility.yml
source_heading: Eligibility
source_page: https://search.ioconnex.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ioconnex-dev\naid: ioconnex-dev\nurl: https://search.ioconnex.dev/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you access the Services on behalf of a company, organization, or other entity, you represent and warrant\n    that you have full authority to bind that entity, and \"you\" means that entity.\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract.\nrestricted_uses:\n- summary: Sanctions and export-control compliance\n  text: Use the Services in violation of any\
  \ applicable law or regulation, including sanctions administered by OFAC\n    and applicable export-control laws;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/ioconnex-dev/eligibility/ioconnex-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ioconnex-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- Search
- Document Conversion
- Price-Tracking
---
