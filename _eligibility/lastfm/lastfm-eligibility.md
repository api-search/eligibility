---
api_specs:
- filename: lastfm-album-api-openapi.yml
  format: yaml
  label: Last.fm Album API
  slug: lastfm-album-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-album-api-openapi.yml
- filename: lastfm-artist-api-openapi.yml
  format: yaml
  label: Last.fm Artist API
  slug: lastfm-artist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-artist-api-openapi.yml
- filename: lastfm-auth-api-openapi.yml
  format: yaml
  label: Last.fm Auth API
  slug: lastfm-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-auth-api-openapi.yml
- filename: lastfm-chart-api-openapi.yml
  format: yaml
  label: Last.fm Chart API
  slug: lastfm-chart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-chart-api-openapi.yml
- filename: lastfm-geo-api-openapi.yml
  format: yaml
  label: Last.fm Geo API
  slug: lastfm-geo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-geo-api-openapi.yml
- filename: lastfm-library-api-openapi.yml
  format: yaml
  label: Last.fm Library API
  slug: lastfm-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-library-api-openapi.yml
- filename: lastfm-tag-api-openapi.yml
  format: yaml
  label: Last.fm Tag API
  slug: lastfm-tag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-tag-api-openapi.yml
- filename: lastfm-track-api-openapi.yml
  format: yaml
  label: Last.fm Track API
  slug: lastfm-track-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-track-api-openapi.yml
- filename: lastfm-user-api-openapi.yml
  format: yaml
  label: Last.fm User API
  slug: lastfm-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-user-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You have the authority to enter into this Agreement on Your own behalf or on behalf of any company or other legal entity by which You are employed
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No identifying users
    text: You will not use the Last.fm Data for any purpose to enable You to personally identify or contact any User
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: If at any time you wish to use the Last.fm Data for commercial purposes, you must apply for a commercial use agreement.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Last.fm
provenance_date: '2026-11-09'
provider_name: Last.fm
provider_slug: lastfm
slug: lastfm-eligibility
source_date: '2026-11-09'
source_filename: lastfm-eligibility.yml
source_heading: Eligibility
source_page: https://www.last.fm/api/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Last.fm\naid: lastfm\nurl: https://www.last.fm/api/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You have the authority to enter into this Agreement on Your own behalf or on behalf of any company or other\n    legal entity by which You are employed\nrestricted_uses:\n- summary: No identifying users\n  text: You will not use the Last.fm Data for any purpose to enable You to personally identify or contact any User\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: If at any time you wish to use the Last.fm\
  \ Data for commercial purposes, you must apply for a commercial\n    use agreement.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lastfm/eligibility/lastfm-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Last.fm's own page on 2026-11-09.
synthetic: false
tags:
- Music
- Audio
- Scrobbling
- Recommendations
- Charts
- Public APIs
- AudioScrobbler
---
