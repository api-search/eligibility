---
api_specs:
- filename: transcript-yt-com-languages-api-openapi.yml
  format: yaml
  label: transcript-yt-com Languages API
  slug: transcript-yt-com-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-languages-api-openapi.yml
- filename: transcript-yt-com-playlist-api-openapi.yml
  format: yaml
  label: transcript-yt-com Playlist API
  slug: transcript-yt-com-playlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-playlist-api-openapi.yml
- filename: transcript-yt-com-search-api-openapi.yml
  format: yaml
  label: transcript-yt-com Search API
  slug: transcript-yt-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-search-api-openapi.yml
- filename: transcript-yt-com-summary-api-openapi.yml
  format: yaml
  label: transcript-yt-com Summary API
  slug: transcript-yt-com-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-summary-api-openapi.yml
- filename: transcript-yt-com-transcript-api-openapi.yml
  format: yaml
  label: transcript-yt-com Transcript API
  slug: transcript-yt-com-transcript-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-transcript-api-openapi.yml
- filename: transcript-yt-com-transcripts-api-openapi.yml
  format: yaml
  label: transcript-yt-com Transcripts API
  slug: transcript-yt-com-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-transcripts-api-openapi.yml
- filename: transcript-yt-com-usage-api-openapi.yml
  format: yaml
  label: transcript-yt-com Usage API
  slug: transcript-yt-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organization, you agree to them on its behalf.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live
    value: '18'
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
name: transcript-yt-com
provenance_date: '2026-11-10'
provider_name: transcript-yt-com
provider_slug: transcript-yt-com
slug: transcript-yt-com-eligibility
source_date: '2026-11-10'
source_filename: transcript-yt-com-eligibility.yml
source_heading: Eligibility
source_page: https://transcript-yt.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: transcript-yt-com\naid: transcript-yt-com\nurl: https://transcript-yt.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you agree to them on its behalf.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live\n"
source_yaml_url: https://artifacts.apis.io/transcript-yt-com/eligibility/transcript-yt-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from transcript-yt-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- YouTube
- Transcript
- MCP
---
