---
api_specs:
- filename: spotify-albums-api-openapi.yml
  format: yaml
  label: Spotify Albums API
  slug: spotify-albums-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-albums-api-openapi.yml
- filename: spotify-artists-api-openapi.yml
  format: yaml
  label: Spotify Artists API
  slug: spotify-artists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-artists-api-openapi.yml
- filename: spotify-audiobooks-api-openapi.yml
  format: yaml
  label: Spotify Audiobooks API
  slug: spotify-audiobooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-audiobooks-api-openapi.yml
- filename: spotify-categories-api-openapi.yml
  format: yaml
  label: Spotify Categories API
  slug: spotify-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-categories-api-openapi.yml
- filename: spotify-chapters-api-openapi.yml
  format: yaml
  label: Spotify Chapters API
  slug: spotify-chapters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-chapters-api-openapi.yml
- filename: spotify-episodes-api-openapi.yml
  format: yaml
  label: Spotify Episodes API
  slug: spotify-episodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-episodes-api-openapi.yml
- filename: spotify-genres-api-openapi.yml
  format: yaml
  label: Spotify Genres API
  slug: spotify-genres-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-genres-api-openapi.yml
- filename: spotify-library-api-openapi.yml
  format: yaml
  label: Spotify Library API
  slug: spotify-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-library-api-openapi.yml
- filename: spotify-markets-api-openapi.yml
  format: yaml
  label: Spotify Markets API
  slug: spotify-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-markets-api-openapi.yml
- filename: spotify-player-api-openapi.yml
  format: yaml
  label: Spotify Player API
  slug: spotify-player-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-player-api-openapi.yml
- filename: spotify-playlists-api-openapi.yml
  format: yaml
  label: Spotify Playlists API
  slug: spotify-playlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-playlists-api-openapi.yml
- filename: spotify-search-api-openapi.yml
  format: yaml
  label: Spotify Search API
  slug: spotify-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-search-api-openapi.yml
- filename: spotify-shows-api-openapi.yml
  format: yaml
  label: Spotify Shows API
  slug: spotify-shows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-shows-api-openapi.yml
- filename: spotify-tracks-api-openapi.yml
  format: yaml
  label: Spotify Tracks API
  slug: spotify-tracks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-tracks-api-openapi.yml
- filename: spotify-users-api-openapi.yml
  format: yaml
  label: Spotify Users API
  slug: spotify-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spotify/openapi/spotify-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are developing on behalf of an organization, you agree to the terms of the Developer Agreement for that organization
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted promotion categories
    text: (d) the sale or advertisement of tobacco products, ammunition, firearms, and/or pornography
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
name: Spotify
provenance_date: '2026-11-10'
provider_name: Spotify
provider_slug: spotify
slug: spotify-eligibility
source_date: '2026-11-10'
source_filename: spotify-eligibility.yml
source_heading: Eligibility
source_page: https://developer.spotify.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spotify\naid: spotify\nurl: https://developer.spotify.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: If you are developing on behalf of an organization, you agree to the terms of the Developer Agreement for\n    that organization\nrestricted_uses:\n- summary: Restricted promotion categories\n  text: (d) the sale or advertisement of tobacco products, ammunition, firearms, and/or pornography\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/spotify/eligibility/spotify-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Spotify's own page on 2026-11-10.
synthetic: false
tags:
- Music
- Audio
- Streaming
- Podcasts
- Playlists
- Spotify
---
