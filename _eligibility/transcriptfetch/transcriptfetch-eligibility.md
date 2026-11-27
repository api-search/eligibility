---
api_specs:
- filename: transcriptfetch-system-api-openapi.yml
  format: yaml
  label: TranscriptFetch System API
  slug: transcriptfetch-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptfetch/openapi/transcriptfetch-system-api-openapi.yml
- filename: transcriptfetch-transcripts-api-openapi.yml
  format: yaml
  label: TranscriptFetch Transcripts API
  slug: transcriptfetch-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptfetch/openapi/transcriptfetch-transcripts-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Service is not directed to children under 13 (or the minimum age in your jurisdiction)
    value: '13'
  restricted_uses:
  - summary: Private or authenticated content
    text: The Service is intended solely for publicly available content.
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
name: TranscriptFetch
provenance_date: '2026-11-10'
provider_name: TranscriptFetch
provider_slug: transcriptfetch
slug: transcriptfetch-eligibility
source_date: '2026-11-10'
source_filename: transcriptfetch-eligibility.yml
source_heading: Eligibility
source_page: https://transcriptfetch.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TranscriptFetch\naid: transcriptfetch\nurl: https://transcriptfetch.com/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Private or authenticated content\n  text: The Service is intended solely for publicly available content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Service is not directed to children under 13 (or the minimum age in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/transcriptfetch/eligibility/transcriptfetch-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from TranscriptFetch's own page on 2026-11-10.
synthetic: false
tags:
- Transcripts
- Speech-to-Text
- Captions
- YouTube
- TikTok
- Instagram
- Podcasts
- MCP
- Llms.txt
- OpenAPI
- Transcription
- Video
- AI/LLM
- RAG
- Agents
- Developer Tools
- Media
- Content
- Spotify
- Apple Podcasts
---
