---
api_specs:
- filename: the-open-movie-database-movies-api-openapi.yml
  format: yaml
  label: The Open Movie Database Movies API
  slug: the-open-movie-database-movies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/the-open-movie-database/openapi/the-open-movie-database-movies-api-openapi.yml
- filename: the-open-movie-database-search-api-openapi.yml
  format: yaml
  label: The Open Movie Database Search API
  slug: the-open-movie-database-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/the-open-movie-database/openapi/the-open-movie-database-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are 13 years of age or older
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: you may not use the Site or any Contributions or Materials in connection with any commercial endeavors.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to use the interactive features on this Site, you must first register with us through email
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: The Open Movie Database
provenance_date: '2026-11-10'
provider_name: The Open Movie Database
provider_slug: the-open-movie-database
slug: the-open-movie-database-eligibility
source_date: '2026-11-10'
source_filename: the-open-movie-database-eligibility.yml
source_heading: Eligibility
source_page: https://www.omdbapi.com/legal.htm
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Open Movie Database\naid: the-open-movie-database\nurl: https://www.omdbapi.com/legal.htm\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use only\n  text: you may not use the Site or any Contributions or Materials in connection with any commercial endeavors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to use the interactive features on this Site, you must first register with us through email\nminimum_age:\n  value: '13'\n  text: you are 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/the-open-movie-database/eligibility/the-open-movie-database-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from The Open Movie Database's own page on 2026-11-10.
synthetic: false
tags:
- Entertainment
- Movies
- Television
- IMDb
- Metadata
- Video
- Public APIs
---
