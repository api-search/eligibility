---
api_specs:
- filename: openapi.json
  format: json
  label: MediaRuntime Media API
  slug: media-api
  spec_type: OpenAPI
  url: https://mediaruntime.com/openapi.json
- filename: openapi.json
  format: json
  label: MediaRuntime Stickers API
  slug: stickers-api
  spec_type: OpenAPI
  url: https://mediaruntime.com/openapi.json
- filename: mediaruntime-discovery-api-openapi.yml
  format: yaml
  label: MediaRuntime Discovery API
  slug: mediaruntime-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-discovery-api-openapi.yml
- filename: mediaruntime-job-results-api-openapi.yml
  format: yaml
  label: MediaRuntime Job Results API
  slug: mediaruntime-job-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-job-results-api-openapi.yml
- filename: mediaruntime-jobs-api-openapi.yml
  format: yaml
  label: MediaRuntime Jobs API
  slug: mediaruntime-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-jobs-api-openapi.yml
- filename: mediaruntime-media-analysis-api-openapi.yml
  format: yaml
  label: MediaRuntime Media Analysis API
  slug: mediaruntime-media-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-media-analysis-api-openapi.yml
- filename: mediaruntime-mediaruntime-api-api-openapi.yml
  format: yaml
  label: MediaRuntime API
  slug: mediaruntime-mediaruntime-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-mediaruntime-api-api-openapi.yml
- filename: mediaruntime-moderation-api-openapi.yml
  format: yaml
  label: MediaRuntime Moderation API
  slug: mediaruntime-moderation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-moderation-api-openapi.yml
- filename: mediaruntime-recipes-api-openapi.yml
  format: yaml
  label: MediaRuntime Recipes API
  slug: mediaruntime-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-recipes-api-openapi.yml
- filename: mediaruntime-sandbox-api-openapi.yml
  format: yaml
  label: MediaRuntime Sandbox API
  slug: mediaruntime-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-sandbox-api-openapi.yml
- filename: mediaruntime-uploads-api-openapi.yml
  format: yaml
  label: MediaRuntime Uploads API
  slug: mediaruntime-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-uploads-api-openapi.yml
- filename: mediaruntime-watermarks-api-openapi.yml
  format: yaml
  label: MediaRuntime Watermarks API
  slug: mediaruntime-watermarks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-watermarks-api-openapi.yml
- filename: mediaruntime-webhooks-api-openapi.yml
  format: yaml
  label: MediaRuntime Webhooks API
  slug: mediaruntime-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-webhooks-api-openapi.yml
- filename: mediaruntime-marketplace-api-openapi.yml
  format: yaml
  label: MediaRuntime Marketplace API
  slug: mediaruntime-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-marketplace-api-openapi.yml
- filename: mediaruntime-sticker-collections-api-openapi.yml
  format: yaml
  label: MediaRuntime Sticker Collections API
  slug: mediaruntime-sticker-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-sticker-collections-api-openapi.yml
- filename: mediaruntime-sticker-runtime-api-openapi.yml
  format: yaml
  label: MediaRuntime Sticker Runtime API
  slug: mediaruntime-sticker-runtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediaruntime/openapi/mediaruntime-sticker-runtime-api-openapi.yml
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
  - summary: Unlawful or unauthorized processing
    text: process content you are not authorized to use
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
name: MediaRuntime
provenance_date: '2026-11-10'
provider_name: MediaRuntime
provider_slug: mediaruntime
slug: mediaruntime-eligibility
source_date: '2026-11-10'
source_filename: mediaruntime-eligibility.yml
source_heading: Eligibility
source_page: https://mediaruntime.com/legal#terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MediaRuntime\naid: mediaruntime\nurl: https://mediaruntime.com/legal#terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or unauthorized processing\n  text: process content you are not authorized to use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mediaruntime/eligibility/mediaruntime-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from MediaRuntime's own page on 2026-11-10.
synthetic: false
tags:
- Media Processing
- Video
- Audio
- Runtime
- Video Encoding
- Audio Processing
- Image Processing
- Content Moderation
- Media API
- Asynchronous Processing
---
