---
api_specs:
- filename: qobuz-albums-api-openapi.yml
  format: yaml
  label: Qobuz Albums API
  slug: qobuz-albums-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qobuz/openapi/qobuz-albums-api-openapi.yml
- filename: qobuz-artists-api-openapi.yml
  format: yaml
  label: Qobuz Artists API
  slug: qobuz-artists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qobuz/openapi/qobuz-artists-api-openapi.yml
- filename: qobuz-authentication-api-openapi.yml
  format: yaml
  label: Qobuz Authentication API
  slug: qobuz-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qobuz/openapi/qobuz-authentication-api-openapi.yml
- filename: qobuz-playlists-api-openapi.yml
  format: yaml
  label: Qobuz Playlists API
  slug: qobuz-playlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qobuz/openapi/qobuz-playlists-api-openapi.yml
- filename: qobuz-search-api-openapi.yml
  format: yaml
  label: Qobuz Search API
  slug: qobuz-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qobuz/openapi/qobuz-search-api-openapi.yml
- filename: qobuz-tracks-api-openapi.yml
  format: yaml
  label: Qobuz Tracks API
  slug: qobuz-tracks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qobuz/openapi/qobuz-tracks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the developer, herein you, that sets forth the terms and conditions governing the use of the application programming interface
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: using the API or Service for any illegal or unauthorized purpose
  - summary: Defamatory, obscene or discriminatory content
    text: using the API in a way that could be considered defamatory, obscene, or discriminatory
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must have a valid Application Key issued by Qobuz in order to access the API
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Qobuz
provenance_date: '2026-11-10'
provider_name: Qobuz
provider_slug: qobuz
slug: qobuz-eligibility
source_date: '2026-11-10'
source_filename: qobuz-eligibility.yml
source_heading: Eligibility
source_page: http://static.qobuz.com/apps/api/QobuzAPI-TermsofUse.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qobuz\naid: qobuz\nurl: http://static.qobuz.com/apps/api/QobuzAPI-TermsofUse.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: the developer, herein you, that sets forth the terms and conditions governing the use of the application\n    programming interface\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: using the API or Service for any illegal or unauthorized purpose\n- summary: Defamatory, obscene or discriminatory content\n  text: using the API in a way that could be considered defamatory, obscene, or discriminatory\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must have a valid Application Key issued by Qobuz in order to access the API\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/qobuz/eligibility/qobuz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Qobuz's own page on 2026-11-10.
synthetic: false
tags:
- Music Streaming
- Hi-Res Audio
- FLAC
- Lossless Audio
- Music Downloads
- Catalog Search
- Streaming URLs
- Music Metadata
- Audiophile
- France
- Music
---
