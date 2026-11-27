---
api_specs:
- filename: listennotes-insights-api-api-openapi.yml
  format: yaml
  label: Listen Notes Insights API
  slug: insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/listennotes/openapi/listennotes-insights-api-api-openapi.yml
- filename: listennotes-playlist-api-api-openapi.yml
  format: yaml
  label: Listen Notes Playlist API
  slug: playlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/listennotes/openapi/listennotes-playlist-api-api-openapi.yml
- filename: listennotes-podcaster-api-api-openapi.yml
  format: yaml
  label: Listen Notes Podcaster API
  slug: listennotes-podcaster-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/listennotes/openapi/listennotes-podcaster-api-api-openapi.yml
- filename: listennotes-search-api-api-openapi.yml
  format: yaml
  label: Listen Notes Search API
  slug: listennotes-search-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/listennotes/openapi/listennotes-search-api-api-openapi.yml
- filename: listennotes-directory-api-api-openapi.yml
  format: yaml
  label: Listen Notes Directory API
  slug: listennotes-directory-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/listennotes/openapi/listennotes-directory-api-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using our Services on behalf of a business, that business accepts these terms.
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
name: Listen Notes
provenance_date: '2026-11-09'
provider_name: Listen Notes
provider_slug: listennotes
slug: listennotes-eligibility
source_date: '2026-11-09'
source_filename: listennotes-eligibility.yml
source_heading: Eligibility
source_page: https://www.listennotes.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Listen Notes\naid: listennotes\nurl: https://www.listennotes.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using our Services on behalf of a business, that business accepts these terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/listennotes/eligibility/listennotes-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Listen Notes's own page on 2026-11-09.
synthetic: false
tags:
- Podcasts
- Podcast Search
- Podcast Directory
- Search
- Audio
- Media
- Podcast Insights
---
