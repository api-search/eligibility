---
api_specs:
- filename: akta-pro-company-api-openapi.yml
  format: yaml
  label: akta.pro Company API
  slug: akta-pro-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akta-pro/openapi/akta-pro-company-api-openapi.yml
- filename: akta-pro-list-generation-api-openapi.yml
  format: yaml
  label: akta.pro List Generation API
  slug: akta-pro-list-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akta-pro/openapi/akta-pro-list-generation-api-openapi.yml
- filename: akta-pro-news-api-openapi.yml
  format: yaml
  label: akta.pro News API
  slug: akta-pro-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akta-pro/openapi/akta-pro-news-api-openapi.yml
- filename: akta-pro-reviews-api-openapi.yml
  format: yaml
  label: akta.pro Reviews API
  slug: akta-pro-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akta-pro/openapi/akta-pro-reviews-api-openapi.yml
- filename: akta-pro-supporting-apis-api-openapi.yml
  format: yaml
  label: akta.pro Supporting APIs API
  slug: akta-pro-supporting-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akta-pro/openapi/akta-pro-supporting-apis-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are available to individuals and businesses subject to these Terms.
    type: individual
  - text: The Services are available to individuals and businesses subject to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use our Services.
    value: '18'
  restricted_uses:
  - summary: Not for HIPAA, FISMA or GLBA regulated use
    text: If your use of the API would be subject to such laws, you may not use the API.
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
name: akta.pro
provenance_date: '2026-11-09'
provider_name: akta.pro
provider_slug: akta-pro
slug: akta-pro-eligibility
source_date: '2026-11-09'
source_filename: akta-pro-eligibility.yml
source_heading: Eligibility
source_page: https://akta.pro/legal?tab=terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: akta.pro\naid: akta-pro\nurl: https://akta.pro/legal?tab=terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are available to individuals and businesses subject to these Terms.\n- type: business\n  text: The Services are available to individuals and businesses subject to these Terms.\nrestricted_uses:\n- summary: Not for HIPAA, FISMA or GLBA regulated use\n  text: If your use of the API would be subject to such laws, you may not use the API.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/akta-pro/eligibility/akta-pro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from akta.pro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Data
- Company Intelligence
- News
- Alternative Data
- Private Companies
- Firmographics
- Data Enrichment
- Signals
- MCP
- Market Intelligence
---
