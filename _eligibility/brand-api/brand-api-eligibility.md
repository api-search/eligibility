---
api_specs:
- filename: brand-api-brands-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Brands API
  slug: brand-api-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-brands-api-openapi.yml
- filename: brand-api-context-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Context API
  slug: brand-api-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-context-api-openapi.yml
- filename: brand-api-search-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Search API
  slug: brand-api-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-search-api-openapi.yml
- filename: brand-api-viewer-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Viewer API
  slug: brand-api-viewer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-viewer-api-openapi.yml
- filename: brand-api-agents-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Agents API
  slug: brand-api-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-agents-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these GTC on behalf of a company, business, corporation, or other entity, you and the applicable company, business, corporation, or other entity each represent and warrant that you have the authority to bind such entity to this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal purposes
    text: use the Services for any illegal purposes
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
name: Brand API (Brandfetch)
provenance_date: '2026-11-09'
provider_name: Brand API (Brandfetch)
provider_slug: brand-api
slug: brand-api-eligibility
source_date: '2026-11-09'
source_filename: brand-api-eligibility.yml
source_heading: Eligibility
source_page: https://brandfetch.com/terms?mode=dev
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brand API (Brandfetch)\naid: brand-api\nurl: https://brandfetch.com/terms?mode=dev\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these GTC on behalf of a company, business, corporation, or other entity, you and the\n    applicable company, business, corporation, or other entity each represent and warrant that you have the authority\n    to bind such entity to this Agreement\nrestricted_uses:\n- summary: Illegal purposes\n  text: use the Services for any illegal purposes\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brand-api/eligibility/brand-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Brand API (Brandfetch)'s own page on 2026-11-09.
synthetic: false
tags:
- Brands
- Logo
- Brand Assets
- Company Data
- Firmographics
- Brand Context
- Merchant Enrichment
- Agent Tools
- A2A
---
