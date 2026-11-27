---
api_specs:
- filename: soldfetch-com-bulk-search-api-openapi.yml
  format: yaml
  label: soldfetch-com Bulk Search API
  slug: soldfetch-com-bulk-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-bulk-search-api-openapi.yml
- filename: soldfetch-com-capabilities-api-openapi.yml
  format: yaml
  label: soldfetch-com Capabilities API
  slug: soldfetch-com-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-capabilities-api-openapi.yml
- filename: soldfetch-com-item-api-openapi.yml
  format: yaml
  label: soldfetch-com Item API
  slug: soldfetch-com-item-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-item-api-openapi.yml
- filename: soldfetch-com-public-api-openapi.yml
  format: yaml
  label: soldfetch-com Public API
  slug: soldfetch-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-public-api-openapi.yml
- filename: soldfetch-com-rapidapi-api-openapi.yml
  format: yaml
  label: soldfetch-com Rapidapi API
  slug: soldfetch-com-rapidapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-rapidapi-api-openapi.yml
- filename: soldfetch-com-requests-api-openapi.yml
  format: yaml
  label: soldfetch-com Requests API
  slug: soldfetch-com-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-requests-api-openapi.yml
- filename: soldfetch-com-scrape-api-openapi.yml
  format: yaml
  label: soldfetch-com Scrape API
  slug: soldfetch-com-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-scrape-api-openapi.yml
- filename: soldfetch-com-usage-api-openapi.yml
  format: yaml
  label: soldfetch-com Usage API
  slug: soldfetch-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-usage-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended primarily for business and professional use.
    type: business
  - text: You must be at least 18 years old and legally capable of entering into a binding agreement.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering into a binding agreement.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful uses
    text: use the Service for unlawful surveillance, discrimination, harassment, deception, fraud, or harmful automated decision-making
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
name: soldfetch-com
provenance_date: '2026-11-10'
provider_name: soldfetch-com
provider_slug: soldfetch-com
slug: soldfetch-com-eligibility
source_date: '2026-11-10'
source_filename: soldfetch-com-eligibility.yml
source_heading: Eligibility
source_page: https://soldfetch.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: soldfetch-com\naid: soldfetch-com\nurl: https://soldfetch.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended primarily for business and professional use.\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering into a binding agreement.\nrestricted_uses:\n- summary: Unlawful or harmful uses\n  text: use the Service for unlawful surveillance, discrimination, harassment, deception, fraud, or harmful automated\n    decision-making\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering into a binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/soldfetch-com/eligibility/soldfetch-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from soldfetch-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- eBay
- Listings
- Pricing
- Reseller
---
