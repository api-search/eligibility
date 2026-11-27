---
api_specs:
- filename: datalikers-com-comment-api-openapi.yml
  format: yaml
  label: datalikers-com Comment API
  slug: datalikers-com-comment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-comment-api-openapi.yml
- filename: datalikers-com-hashtag-api-openapi.yml
  format: yaml
  label: datalikers-com Hashtag API
  slug: datalikers-com-hashtag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-hashtag-api-openapi.yml
- filename: datalikers-com-highlight-api-openapi.yml
  format: yaml
  label: datalikers-com Highlight API
  slug: datalikers-com-highlight-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-highlight-api-openapi.yml
- filename: datalikers-com-location-api-openapi.yml
  format: yaml
  label: datalikers-com Location API
  slug: datalikers-com-location-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-location-api-openapi.yml
- filename: datalikers-com-media-api-openapi.yml
  format: yaml
  label: datalikers-com Media API
  slug: datalikers-com-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-media-api-openapi.yml
- filename: datalikers-com-story-api-openapi.yml
  format: yaml
  label: datalikers-com Story API
  slug: datalikers-com-story-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-story-api-openapi.yml
- filename: datalikers-com-system-api-openapi.yml
  format: yaml
  label: datalikers-com System API
  slug: datalikers-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-system-api-openapi.yml
- filename: datalikers-com-tiktok-comment-api-openapi.yml
  format: yaml
  label: datalikers-com TikTok Comment API
  slug: datalikers-com-tiktok-comment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-tiktok-comment-api-openapi.yml
- filename: datalikers-com-tiktok-hashtag-api-openapi.yml
  format: yaml
  label: datalikers-com TikTok Hashtag API
  slug: datalikers-com-tiktok-hashtag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-tiktok-hashtag-api-openapi.yml
- filename: datalikers-com-tiktok-media-api-openapi.yml
  format: yaml
  label: datalikers-com TikTok Media API
  slug: datalikers-com-tiktok-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-tiktok-media-api-openapi.yml
- filename: datalikers-com-tiktok-playlist-api-openapi.yml
  format: yaml
  label: datalikers-com TikTok Playlist API
  slug: datalikers-com-tiktok-playlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-tiktok-playlist-api-openapi.yml
- filename: datalikers-com-tiktok-user-api-openapi.yml
  format: yaml
  label: datalikers-com TikTok User API
  slug: datalikers-com-tiktok-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-tiktok-user-api-openapi.yml
- filename: datalikers-com-track-api-openapi.yml
  format: yaml
  label: datalikers-com Track API
  slug: datalikers-com-track-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-track-api-openapi.yml
- filename: datalikers-com-user-api-openapi.yml
  format: yaml
  label: datalikers-com User API
  slug: datalikers-com-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-user-api-openapi.yml
- filename: datalikers-com-user-v2-api-openapi.yml
  format: yaml
  label: datalikers-com User v2 API
  slug: datalikers-com-user-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datalikers-com/openapi/datalikers-com-user-v2-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users, who create an account on the Site, agree to the following terms
    type: individual
  minimum_age:
    text: Not to use the Site or Services if You are less than 18 years of age without the consent of Your parent or guardian
    value: '18'
  restricted_uses:
  - summary: Opt-in marketing only
    text: All marketing conducted using DataLikers Services must be permission (opt-in) based.
  - summary: No soliciting minors' personal information
    text: Solicit personal information from anyone under 18 years of age.
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
name: datalikers-com
provenance_date: '2026-11-09'
provider_name: datalikers-com
provider_slug: datalikers-com
slug: datalikers-com-eligibility
source_date: '2026-11-09'
source_filename: datalikers-com-eligibility.yml
source_heading: Eligibility
source_page: https://datalikers.com/help/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: datalikers-com\naid: datalikers-com\nurl: https://datalikers.com/help/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users, who create an account on the Site, agree to the following terms\nrestricted_uses:\n- summary: Opt-in marketing only\n  text: All marketing conducted using DataLikers Services must be permission (opt-in) based.\n- summary: No soliciting minors' personal information\n  text: Solicit personal information from anyone under 18 years of age.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: Not to use the Site or Services if You are less than 18 years of age without the consent of Your parent\n    or guardian\n"
source_yaml_url: https://artifacts.apis.io/datalikers-com/eligibility/datalikers-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from datalikers-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Social Media
- Developer Platform
---
