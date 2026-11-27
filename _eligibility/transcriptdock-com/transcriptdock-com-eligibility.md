---
api_specs:
- filename: transcriptdock-com-app-api-openapi.yml
  format: yaml
  label: transcriptdock-com App API
  slug: transcriptdock-com-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-app-api-openapi.yml
- filename: transcriptdock-com-batches-api-openapi.yml
  format: yaml
  label: transcriptdock-com Batches API
  slug: transcriptdock-com-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-batches-api-openapi.yml
- filename: transcriptdock-com-capabilities-api-openapi.yml
  format: yaml
  label: transcriptdock-com Capabilities API
  slug: transcriptdock-com-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-capabilities-api-openapi.yml
- filename: transcriptdock-com-jobs-api-openapi.yml
  format: yaml
  label: transcriptdock-com Jobs API
  slug: transcriptdock-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-jobs-api-openapi.yml
- filename: transcriptdock-com-language-discoveries-api-openapi.yml
  format: yaml
  label: transcriptdock-com Language Discoveries API
  slug: transcriptdock-com-language-discoveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-language-discoveries-api-openapi.yml
- filename: transcriptdock-com-llms-api-openapi.yml
  format: yaml
  label: transcriptdock-com Llms API
  slug: transcriptdock-com-llms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-llms-api-openapi.yml
- filename: transcriptdock-com-llms-full-api-openapi.yml
  format: yaml
  label: transcriptdock-com Llms Full API
  slug: transcriptdock-com-llms-full-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-llms-full-api-openapi.yml
- filename: transcriptdock-com-transcripts-api-openapi.yml
  format: yaml
  label: transcriptdock-com Transcripts API
  slug: transcriptdock-com-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-transcripts-api-openapi.yml
- filename: transcriptdock-com-uploads-api-openapi.yml
  format: yaml
  label: transcriptdock-com Uploads API
  slug: transcriptdock-com-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-uploads-api-openapi.yml
- filename: transcriptdock-com-usage-api-openapi.yml
  format: yaml
  label: transcriptdock-com Usage API
  slug: transcriptdock-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-usage-api-openapi.yml
- filename: transcriptdock-com-video-discoveries-api-openapi.yml
  format: yaml
  label: transcriptdock-com Video Discoveries API
  slug: transcriptdock-com-video-discoveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-video-discoveries-api-openapi.yml
- filename: transcriptdock-com-webhook-endpoints-api-openapi.yml
  format: yaml
  label: transcriptdock-com Webhook Endpoints API
  slug: transcriptdock-com-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-webhook-endpoints-api-openapi.yml
- filename: transcriptdock-com-webhooks-api-openapi.yml
  format: yaml
  label: transcriptdock-com Webhooks API
  slug: transcriptdock-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One person or organisation per workspace.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harassment and access circumvention
    text: Do not use the Service to build datasets for training models on content you do not have rights to, to harass people, or to circumvent access controls.
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
name: transcriptdock-com
provenance_date: '2026-11-10'
provider_name: transcriptdock-com
provider_slug: transcriptdock-com
slug: transcriptdock-com-eligibility
source_date: '2026-11-10'
source_filename: transcriptdock-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.transcriptdock.com/docs/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: transcriptdock-com\naid: transcriptdock-com\nurl: https://www.transcriptdock.com/docs/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: One person or organisation per workspace.\nrestricted_uses:\n- summary: Harassment and access circumvention\n  text: Do not use the Service to build datasets for training models on content you do not have rights to, to harass\n    people, or to circumvent access controls.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/transcriptdock-com/eligibility/transcriptdock-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from transcriptdock-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Transcript
- YouTube
- TikTok
---
