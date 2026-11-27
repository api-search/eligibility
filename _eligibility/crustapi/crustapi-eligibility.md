---
api_specs:
- filename: crustapi-demo-api-openapi.yml
  format: yaml
  label: CrustAPI Demo API
  slug: crustapi-demo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-demo-api-openapi.yml
- filename: crustapi-search-api-openapi.yml
  format: yaml
  label: CrustAPI Search API
  slug: crustapi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-search-api-openapi.yml
- filename: crustapi-account-api-openapi.yml
  format: yaml
  label: CrustAPI Account API
  slug: crustapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-account-api-openapi.yml
- filename: crustapi-linked-in-api-openapi.yml
  format: yaml
  label: CrustAPI Linked In API
  slug: crustapi-linked-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-linked-in-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is for business and professional use only. It is a business-to-business product.
    type: business
  - text: To use the Service you must be at least 18 years old and must use CrustAPI for business or professional purposes.
    type: individual
  minimum_age:
    text: you must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No personal or consumer use
    text: you may not use it for personal, household, or consumer purposes.
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
name: CrustAPI
provenance_date: '2026-11-09'
provider_name: CrustAPI
provider_slug: crustapi
slug: crustapi-eligibility
source_date: '2026-11-09'
source_filename: crustapi-eligibility.yml
source_heading: Eligibility
source_page: https://crustapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CrustAPI\naid: crustapi\nurl: https://crustapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is for business and professional use only. It is a business-to-business product.\n- type: individual\n  text: To use the Service you must be at least 18 years old and must use CrustAPI for business or professional\n    purposes.\nrestricted_uses:\n- summary: No personal or consumer use\n  text: you may not use it for personal, household, or consumer purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/crustapi/eligibility/crustapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CrustAPI's own page on 2026-11-09.
synthetic: false
tags:
- Search
- Google Maps
- LinkedIn
- SERP / Web Scraping
- Business & Lead Data
- People / Recruiting Data
- Data Enrichment
- AI Agents / MCP
- RAG
- Data
---
