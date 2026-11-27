---
api_specs:
- filename: serper-autocomplete-api-openapi.yml
  format: yaml
  label: Serper Autocomplete API
  slug: serper-autocomplete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-autocomplete-api-openapi.yml
- filename: serper-images-api-openapi.yml
  format: yaml
  label: Serper Images API
  slug: serper-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-images-api-openapi.yml
- filename: serper-lens-api-openapi.yml
  format: yaml
  label: Serper Lens API
  slug: serper-lens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-lens-api-openapi.yml
- filename: serper-locations-api-openapi.yml
  format: yaml
  label: Serper Locations API
  slug: serper-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-locations-api-openapi.yml
- filename: serper-maps-api-openapi.yml
  format: yaml
  label: Serper Maps API
  slug: serper-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-maps-api-openapi.yml
- filename: serper-news-api-openapi.yml
  format: yaml
  label: Serper News API
  slug: serper-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-news-api-openapi.yml
- filename: serper-patents-api-openapi.yml
  format: yaml
  label: Serper Patents API
  slug: serper-patents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-patents-api-openapi.yml
- filename: serper-places-api-openapi.yml
  format: yaml
  label: Serper Places API
  slug: serper-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-places-api-openapi.yml
- filename: serper-reviews-api-openapi.yml
  format: yaml
  label: Serper Reviews API
  slug: serper-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-reviews-api-openapi.yml
- filename: serper-scholar-api-openapi.yml
  format: yaml
  label: Serper Scholar API
  slug: serper-scholar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-scholar-api-openapi.yml
- filename: serper-search-api-openapi.yml
  format: yaml
  label: Serper Search API
  slug: serper-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-search-api-openapi.yml
- filename: serper-shopping-api-openapi.yml
  format: yaml
  label: Serper Shopping API
  slug: serper-shopping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-shopping-api-openapi.yml
- filename: serper-videos-api-openapi.yml
  format: yaml
  label: Serper Videos API
  slug: serper-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-videos-api-openapi.yml
- filename: serper-scrape-api-openapi.yml
  format: yaml
  label: Serper Scrape API
  slug: serper-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serper/openapi/serper-scrape-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Serper is a business-to-business service and does not provide end-user (consumer) services.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Serper
provenance_date: '2026-11-10'
provider_name: Serper
provider_slug: serper
slug: serper-eligibility
source_date: '2026-11-10'
source_filename: serper-eligibility.yml
source_heading: Eligibility
source_page: https://serper.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Serper\naid: serper\nurl: https://serper.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Serper is a business-to-business service and does not provide end-user (consumer) services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/serper/eligibility/serper-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Serper's own page on 2026-11-10.
synthetic: false
tags:
- Search
- SERP
- Google Search
- Artificial Intelligence
- LLM
- SEO
- Image
- News
- Maps
- Shopping
- Reviews
- Lens
- Web Scraping
- Web Search
- Agents
- Patents
- Scholar
- Autocomplete
- Places
- Video
---
