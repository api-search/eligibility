---
api_specs:
- filename: transcriptapi-com-youtube-channel-api-openapi.yml
  format: yaml
  label: transcriptapi-com YouTube channel API
  slug: transcriptapi-com-youtube-channel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptapi-com/openapi/transcriptapi-com-youtube-channel-api-openapi.yml
- filename: transcriptapi-com-youtube-playlist-api-openapi.yml
  format: yaml
  label: transcriptapi-com YouTube playlist API
  slug: transcriptapi-com-youtube-playlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptapi-com/openapi/transcriptapi-com-youtube-playlist-api-openapi.yml
- filename: transcriptapi-com-youtube-search-api-openapi.yml
  format: yaml
  label: transcriptapi-com YouTube search API
  slug: transcriptapi-com-youtube-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptapi-com/openapi/transcriptapi-com-youtube-search-api-openapi.yml
- filename: transcriptapi-com-youtube-transcript-api-openapi.yml
  format: yaml
  label: transcriptapi-com YouTube transcript API
  slug: transcriptapi-com-youtube-transcript-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptapi-com/openapi/transcriptapi-com-youtube-transcript-api-openapi.yml
- filename: transcriptapi-com-youtube-video-api-openapi.yml
  format: yaml
  label: transcriptapi-com YouTube video API
  slug: transcriptapi-com-youtube-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptapi-com/openapi/transcriptapi-com-youtube-video-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Collecting personal information
    text: Use the Service to collect personal information without consent
  - summary: Unlawful use
    text: Use the Service for any illegal or unauthorized purpose
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
name: transcriptapi-com
provenance_date: '2026-11-10'
provider_name: transcriptapi-com
provider_slug: transcriptapi-com
slug: transcriptapi-com-eligibility
source_date: '2026-11-10'
source_filename: transcriptapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://transcriptapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: transcriptapi-com\naid: transcriptapi-com\nurl: https://transcriptapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Collecting personal information\n  text: Use the Service to collect personal information without consent\n- summary: Unlawful use\n  text: Use the Service for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/transcriptapi-com/eligibility/transcriptapi-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from transcriptapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Transcripts
- YouTube API
- Search
- Content Extraction
---
