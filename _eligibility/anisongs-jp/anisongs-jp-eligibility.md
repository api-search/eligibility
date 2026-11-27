---
api_specs:
- filename: anisongs-jp-check-purity-api-openapi.yml
  format: yaml
  label: Anisongs Check Purity API
  slug: anisongs-jp-check-purity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anisongs-jp/openapi/anisongs-jp-check-purity-api-openapi.yml
- filename: anisongs-jp-create-playlist-api-openapi.yml
  format: yaml
  label: Anisongs Create Playlist API
  slug: anisongs-jp-create-playlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anisongs-jp/openapi/anisongs-jp-create-playlist-api-openapi.yml
- filename: anisongs-jp-get-artist-api-openapi.yml
  format: yaml
  label: Anisongs Get Artist API
  slug: anisongs-jp-get-artist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anisongs-jp/openapi/anisongs-jp-get-artist-api-openapi.yml
- filename: anisongs-jp-get-program-api-openapi.yml
  format: yaml
  label: Anisongs Get Program API
  slug: anisongs-jp-get-program-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anisongs-jp/openapi/anisongs-jp-get-program-api-openapi.yml
- filename: anisongs-jp-search-tracks-api-openapi.yml
  format: yaml
  label: Anisongs Search Tracks API
  slug: anisongs-jp-search-tracks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anisongs-jp/openapi/anisongs-jp-search-tracks-api-openapi.yml
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
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Service is designed for anonymous use and does not require registration of personal information such as name or email.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Anisongs
provenance_date: '2026-11-09'
provider_name: Anisongs
provider_slug: anisongs-jp
slug: anisongs-jp-eligibility
source_date: '2026-11-09'
source_filename: anisongs-jp-eligibility.yml
source_heading: Eligibility
source_page: https://anisongs.jp/terms.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anisongs\naid: anisongs-jp\nurl: https://anisongs.jp/terms.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Service is designed for anonymous use and does not require registration of personal information such\n    as name or email.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anisongs-jp/eligibility/anisongs-jp-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Anisongs's own page on 2026-11-09.
synthetic: false
tags:
- Anime
- Music
- Database
- Japanese
- Entertainment
---
