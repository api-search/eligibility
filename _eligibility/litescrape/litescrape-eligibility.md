---
api_specs:
- filename: litescrape-apple-api-openapi.yml
  format: yaml
  label: Litescrape Apple API
  slug: litescrape-apple-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/litescrape/openapi/litescrape-apple-api-openapi.yml
- filename: litescrape-bing-api-openapi.yml
  format: yaml
  label: Litescrape Bing API
  slug: litescrape-bing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/litescrape/openapi/litescrape-bing-api-openapi.yml
- filename: litescrape-duckduckgo-api-openapi.yml
  format: yaml
  label: Litescrape Duckduckgo API
  slug: litescrape-duckduckgo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/litescrape/openapi/litescrape-duckduckgo-api-openapi.yml
- filename: litescrape-google-api-openapi.yml
  format: yaml
  label: Litescrape Google API
  slug: litescrape-google-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/litescrape/openapi/litescrape-google-api-openapi.yml
- filename: litescrape-tripadvisor-api-openapi.yml
  format: yaml
  label: Litescrape Tripadvisor API
  slug: litescrape-tripadvisor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/litescrape/openapi/litescrape-tripadvisor-api-openapi.yml
- filename: litescrape-yelp-api-openapi.yml
  format: yaml
  label: Litescrape Yelp API
  slug: litescrape-yelp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/litescrape/openapi/litescrape-yelp-api-openapi.yml
- filename: litescrape-zeroclick-api-openapi.yml
  format: yaml
  label: Litescrape Zeroclick API
  slug: litescrape-zeroclick-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/litescrape/openapi/litescrape-zeroclick-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter into a binding contract to use the Service.
    type: individual
  - text: The Service is intended for business use.
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
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
name: Litescrape
provenance_date: '2026-11-09'
provider_name: Litescrape
provider_slug: litescrape
slug: litescrape-eligibility
source_date: '2026-11-09'
source_filename: litescrape-eligibility.yml
source_heading: Eligibility
source_page: https://litescrape.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Litescrape\naid: litescrape\nurl: https://litescrape.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into a binding contract to use the Service.\n- type: business\n  text: The Service is intended for business use.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/litescrape/eligibility/litescrape-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Litescrape's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SERP
- Web Scraping
- Search
- Google Maps
- Reviews
- Web Data
- MCP
---
