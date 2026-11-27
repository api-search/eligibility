---
api_specs:
- filename: tvmaze-auth-api-openapi.yml
  format: yaml
  label: TVmaze Auth API
  slug: tvmaze-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-auth-api-openapi.yml
- filename: tvmaze-episodes-api-openapi.yml
  format: yaml
  label: TVmaze Episodes API
  slug: tvmaze-episodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-episodes-api-openapi.yml
- filename: tvmaze-followed-networks-api-openapi.yml
  format: yaml
  label: TVmaze followed networks API
  slug: tvmaze-followed-networks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-followed-networks-api-openapi.yml
- filename: tvmaze-followed-people-api-openapi.yml
  format: yaml
  label: TVmaze followed people API
  slug: tvmaze-followed-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-followed-people-api-openapi.yml
- filename: tvmaze-followed-shows-api-openapi.yml
  format: yaml
  label: TVmaze followed shows API
  slug: tvmaze-followed-shows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-followed-shows-api-openapi.yml
- filename: tvmaze-followed-webchannels-api-openapi.yml
  format: yaml
  label: TVmaze followed webchannels API
  slug: tvmaze-followed-webchannels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-followed-webchannels-api-openapi.yml
- filename: tvmaze-marked-episodes-api-openapi.yml
  format: yaml
  label: TVmaze marked episodes API
  slug: tvmaze-marked-episodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-marked-episodes-api-openapi.yml
- filename: tvmaze-people-api-openapi.yml
  format: yaml
  label: TVmaze People API
  slug: tvmaze-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-people-api-openapi.yml
- filename: tvmaze-schedule-api-openapi.yml
  format: yaml
  label: TVmaze Schedule API
  slug: tvmaze-schedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-schedule-api-openapi.yml
- filename: tvmaze-scrobbling-api-openapi.yml
  format: yaml
  label: TVmaze Scrobbling API
  slug: tvmaze-scrobbling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-scrobbling-api-openapi.yml
- filename: tvmaze-search-api-openapi.yml
  format: yaml
  label: TVmaze Search API
  slug: tvmaze-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-search-api-openapi.yml
- filename: tvmaze-seasons-api-openapi.yml
  format: yaml
  label: TVmaze Seasons API
  slug: tvmaze-seasons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-seasons-api-openapi.yml
- filename: tvmaze-shows-api-openapi.yml
  format: yaml
  label: TVmaze Shows API
  slug: tvmaze-shows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-shows-api-openapi.yml
- filename: tvmaze-tagged-shows-api-openapi.yml
  format: yaml
  label: TVmaze tagged shows API
  slug: tvmaze-tagged-shows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-tagged-shows-api-openapi.yml
- filename: tvmaze-updates-api-openapi.yml
  format: yaml
  label: TVmaze Updates API
  slug: tvmaze-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-updates-api-openapi.yml
- filename: tvmaze-voted-episodes-api-openapi.yml
  format: yaml
  label: TVmaze voted episodes API
  slug: tvmaze-voted-episodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-voted-episodes-api-openapi.yml
- filename: tvmaze-voted-shows-api-openapi.yml
  format: yaml
  label: TVmaze voted shows API
  slug: tvmaze-voted-shows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvmaze/openapi/tvmaze-voted-shows-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal acts prohibited
    text: you agree not to partake in any acts that are illegal in your own jurisdiction; the United States; or the European Union.
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
name: TVmaze
provenance_date: '2026-11-10'
provider_name: TVmaze
provider_slug: tvmaze
slug: tvmaze-eligibility
source_date: '2026-11-10'
source_filename: tvmaze-eligibility.yml
source_heading: Eligibility
source_page: https://www.tvmaze.com/site/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TVmaze\naid: tvmaze\nurl: https://www.tvmaze.com/site/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal acts prohibited\n  text: you agree not to partake in any acts that are illegal in your own jurisdiction; the United States; or the\n    European Union.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tvmaze/eligibility/tvmaze-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from TVmaze's own page on 2026-11-10.
synthetic: false
tags:
- Video
- Television
- Streaming
- Schedule
- Metadata
- Entertainment
- Public APIs
---
