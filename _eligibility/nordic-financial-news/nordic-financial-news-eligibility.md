---
api_specs:
- filename: nordic-financial-news-articles-api-openapi.yml
  format: yaml
  label: Nordic Financial News Articles API
  slug: nordic-financial-news-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-articles-api-openapi.yml
- filename: nordic-financial-news-calendar-events-api-openapi.yml
  format: yaml
  label: Nordic Financial News Calendar Events API
  slug: nordic-financial-news-calendar-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-calendar-events-api-openapi.yml
- filename: nordic-financial-news-categories-api-openapi.yml
  format: yaml
  label: Nordic Financial News Categories API
  slug: nordic-financial-news-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-categories-api-openapi.yml
- filename: nordic-financial-news-companies-api-openapi.yml
  format: yaml
  label: Nordic Financial News Companies API
  slug: nordic-financial-news-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-companies-api-openapi.yml
- filename: nordic-financial-news-countries-api-openapi.yml
  format: yaml
  label: Nordic Financial News Countries API
  slug: nordic-financial-news-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-countries-api-openapi.yml
- filename: nordic-financial-news-event-types-api-openapi.yml
  format: yaml
  label: Nordic Financial News Event Types API
  slug: nordic-financial-news-event-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-event-types-api-openapi.yml
- filename: nordic-financial-news-events-api-openapi.yml
  format: yaml
  label: Nordic Financial News Events API
  slug: nordic-financial-news-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-events-api-openapi.yml
- filename: nordic-financial-news-exchanges-api-openapi.yml
  format: yaml
  label: Nordic Financial News Exchanges API
  slug: nordic-financial-news-exchanges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-exchanges-api-openapi.yml
- filename: nordic-financial-news-health-api-openapi.yml
  format: yaml
  label: Nordic Financial News Health API
  slug: nordic-financial-news-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-health-api-openapi.yml
- filename: nordic-financial-news-indices-api-openapi.yml
  format: yaml
  label: Nordic Financial News Indices API
  slug: nordic-financial-news-indices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-indices-api-openapi.yml
- filename: nordic-financial-news-meta-api-openapi.yml
  format: yaml
  label: Nordic Financial News Meta API
  slug: nordic-financial-news-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-meta-api-openapi.yml
- filename: nordic-financial-news-search-api-openapi.yml
  format: yaml
  label: Nordic Financial News Search API
  slug: nordic-financial-news-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-search-api-openapi.yml
- filename: nordic-financial-news-sources-api-openapi.yml
  format: yaml
  label: Nordic Financial News Sources API
  slug: nordic-financial-news-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-sources-api-openapi.yml
- filename: nordic-financial-news-stories-api-openapi.yml
  format: yaml
  label: Nordic Financial News Stories API
  slug: nordic-financial-news-stories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-stories-api-openapi.yml
- filename: nordic-financial-news-watchlists-api-openapi.yml
  format: yaml
  label: Nordic Financial News Watchlists API
  slug: nordic-financial-news-watchlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordic-financial-news/openapi/nordic-financial-news-watchlists-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: your organisation's internal business purposes
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Unlawful purpose
    text: Use the Service for any unlawful purpose.
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
name: Nordic Financial News
provenance_date: '2026-11-10'
provider_name: Nordic Financial News
provider_slug: nordic-financial-news
slug: nordic-financial-news-eligibility
source_date: '2026-11-10'
source_filename: nordic-financial-news-eligibility.yml
source_heading: Eligibility
source_page: https://nordicfinancialnews.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nordic Financial News\naid: nordic-financial-news\nurl: https://nordicfinancialnews.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: your organisation's internal business purposes\nrestricted_uses:\n- summary: Unlawful purpose\n  text: Use the Service for any unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/nordic-financial-news/eligibility/nordic-financial-news-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Nordic Financial News's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial News
- Nordic
- Market Data
- Financial Calendar
- MCP
- News API
---
