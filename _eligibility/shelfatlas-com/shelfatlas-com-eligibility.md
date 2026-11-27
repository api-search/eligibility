---
api_specs:
- filename: shelfatlas-com-chains-api-openapi.yml
  format: yaml
  label: shelfatlas-com Chains API
  slug: shelfatlas-com-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-chains-api-openapi.yml
- filename: shelfatlas-com-mcp-api-openapi.yml
  format: yaml
  label: shelfatlas-com MCP API
  slug: shelfatlas-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-mcp-api-openapi.yml
- filename: shelfatlas-com-observations-api-openapi.yml
  format: yaml
  label: shelfatlas-com Observations API
  slug: shelfatlas-com-observations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-observations-api-openapi.yml
- filename: shelfatlas-com-observedprices-api-openapi.yml
  format: yaml
  label: shelfatlas-com Observed Prices API
  slug: shelfatlas-com-observedprices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-observedprices-api-openapi.yml
- filename: shelfatlas-com-offers-api-openapi.yml
  format: yaml
  label: shelfatlas-com Offers API
  slug: shelfatlas-com-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-offers-api-openapi.yml
- filename: shelfatlas-com-price-history-api-openapi.yml
  format: yaml
  label: shelfatlas-com Price history API
  slug: shelfatlas-com-price-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-price-history-api-openapi.yml
- filename: shelfatlas-com-products-api-openapi.yml
  format: yaml
  label: shelfatlas-com Products API
  slug: shelfatlas-com-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-products-api-openapi.yml
- filename: shelfatlas-com-seoterms-api-openapi.yml
  format: yaml
  label: shelfatlas-com Seo Terms API
  slug: shelfatlas-com-seoterms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-seoterms-api-openapi.yml
- filename: shelfatlas-com-stats-api-openapi.yml
  format: yaml
  label: shelfatlas-com Stats API
  slug: shelfatlas-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-stats-api-openapi.yml
- filename: shelfatlas-com-stores-api-openapi.yml
  format: yaml
  label: shelfatlas-com Stores API
  slug: shelfatlas-com-stores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-stores-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Free and Hobby plans are for personal, non-commercial use by an individual
    type: individual
  - text: Use by or on behalf of a company or organisation, and use inside a product or service you sell, requires the Standard plan or higher.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Company or resale use needs Standard plan
    text: Use by or on behalf of a company or organisation, and use inside a product or service you sell, requires the Standard plan or higher.
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
name: shelfatlas-com
provenance_date: '2026-11-10'
provider_name: shelfatlas-com
provider_slug: shelfatlas-com
slug: shelfatlas-com-eligibility
source_date: '2026-11-10'
source_filename: shelfatlas-com-eligibility.yml
source_heading: Eligibility
source_page: https://shelfatlas.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: shelfatlas-com\naid: shelfatlas-com\nurl: https://shelfatlas.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Free and Hobby plans are for personal, non-commercial use by an individual\n- type: business\n  text: Use by or on behalf of a company or organisation, and use inside a product or service you sell, requires\n    the Standard plan or higher.\nrestricted_uses:\n- summary: Company or resale use needs Standard plan\n  text: Use by or on behalf of a company or organisation, and use inside a product or service\
  \ you sell, requires\n    the Standard plan or higher.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shelfatlas-com/eligibility/shelfatlas-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from shelfatlas-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Grocery
- Denmark
- Retail
---
