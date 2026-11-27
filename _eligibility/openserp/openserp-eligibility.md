---
api_specs:
- filename: openserp-docs-api-openapi.yml
  format: yaml
  label: OpenSERP Docs API
  slug: openserp-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openserp/openapi/openserp-docs-api-openapi.yml
- filename: openserp-health-api-openapi.yml
  format: yaml
  label: OpenSERP Health API
  slug: openserp-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openserp/openapi/openserp-health-api-openapi.yml
- filename: openserp-mega-api-openapi.yml
  format: yaml
  label: OpenSERP Mega API
  slug: openserp-mega-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openserp/openapi/openserp-mega-api-openapi.yml
- filename: openserp-search-api-openapi.yml
  format: yaml
  label: OpenSERP Search API
  slug: openserp-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openserp/openapi/openserp-search-api-openapi.yml
- filename: openserp-stats-api-openapi.yml
  format: yaml
  label: OpenSERP Stats API
  slug: openserp-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openserp/openapi/openserp-stats-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service for business purposes, the courts of England and Wales have exclusive jurisdiction.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purpose
    text: Use the Service for any unlawful purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email address and a secure password (minimum 10 characters)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OpenSERP
provenance_date: '2026-11-10'
provider_name: OpenSERP
provider_slug: openserp
slug: openserp-eligibility
source_date: '2026-11-10'
source_filename: openserp-eligibility.yml
source_heading: Eligibility
source_page: https://openserp.org/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenSERP\naid: openserp\nurl: https://openserp.org/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for business purposes, the courts of England and Wales have exclusive jurisdiction.\nrestricted_uses:\n- summary: Unlawful purpose\n  text: Use the Service for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email address and a secure password (minimum 10 characters)\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openserp/eligibility/openserp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from OpenSERP's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Search
- SERP
- Web Scraping
- Content Extraction
- AI Grounding
- Rank Tracking
- Open Source
- Developer Tools
---
