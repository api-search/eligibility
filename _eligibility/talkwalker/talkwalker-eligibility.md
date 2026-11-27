---
api_specs:
- filename: talkwalker-image-api-api-openapi.yml
  format: yaml
  label: Talkwalker Image API
  slug: talkwalker-image-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkwalker/openapi/talkwalker-image-api-api-openapi.yml
- filename: talkwalker-modify-documents-api-api-openapi.yml
  format: yaml
  label: Talkwalker Modify documents API
  slug: talkwalker-modify-documents-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkwalker/openapi/talkwalker-modify-documents-api-api-openapi.yml
- filename: talkwalker-resources-api-api-openapi.yml
  format: yaml
  label: Talkwalker Resources API
  slug: talkwalker-resources-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkwalker/openapi/talkwalker-resources-api-api-openapi.yml
- filename: talkwalker-search-api-api-openapi.yml
  format: yaml
  label: Talkwalker Search API
  slug: talkwalker-search-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkwalker/openapi/talkwalker-search-api-api-openapi.yml
- filename: talkwalker-search-api-histogram-api-api-openapi.yml
  format: yaml
  label: Talkwalker Search API > Histogram API
  slug: talkwalker-search-api-histogram-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkwalker/openapi/talkwalker-search-api-histogram-api-api-openapi.yml
- filename: talkwalker-source-panels-api-api-openapi.yml
  format: yaml
  label: Talkwalker Source panels API
  slug: talkwalker-source-panels-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkwalker/openapi/talkwalker-source-panels-api-api-openapi.yml
- filename: talkwalker-status-api-api-openapi.yml
  format: yaml
  label: Talkwalker Status API
  slug: talkwalker-status-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkwalker/openapi/talkwalker-status-api-api-openapi.yml
- filename: talkwalker-streaming-api-api-openapi.yml
  format: yaml
  label: Talkwalker Streaming API
  slug: talkwalker-streaming-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkwalker/openapi/talkwalker-streaming-api-api-openapi.yml
- filename: talkwalker-streaming-api-collector-api-api-openapi.yml
  format: yaml
  label: Talkwalker Streaming API > Collector API
  slug: talkwalker-streaming-api-collector-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkwalker/openapi/talkwalker-streaming-api-collector-api-api-openapi.yml
- filename: talkwalker-streaming-api-task-api-api-openapi.yml
  format: yaml
  label: Talkwalker Streaming API > Task API
  slug: talkwalker-streaming-api-task-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkwalker/openapi/talkwalker-streaming-api-task-api-api-openapi.yml
- filename: talkwalker-summary-api-api-openapi.yml
  format: yaml
  label: Talkwalker Summary API
  slug: talkwalker-summary-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkwalker/openapi/talkwalker-summary-api-api-openapi.yml
- filename: talkwalker-topic-api-api-openapi.yml
  format: yaml
  label: Talkwalker Topic API
  slug: talkwalker-topic-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkwalker/openapi/talkwalker-topic-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Governing-law provisions refer to customers located in North and South America, the Asia-Pacific region and other territories; no list of served countries is given.
  entity_types:
  - text: the Enterprise Services are not for use by consumers and may only be used for business and professional purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Law enforcement, surveillance, tracking
    text: prohibiting use of the Enterprise Services for law enforcement, surveillance, tracking, etc.
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
name: Talkwalker
provenance_date: '2026-11-10'
provider_name: Talkwalker
provider_slug: talkwalker
slug: talkwalker-eligibility
source_date: '2026-11-10'
source_filename: talkwalker-eligibility.yml
source_heading: Eligibility
source_page: https://www.talkwalker.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Talkwalker\naid: talkwalker\nurl: https://www.talkwalker.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Governing-law provisions refer to customers located in North and South America, the Asia-Pacific region\n    and other territories; no list of served countries is given.\nentity_types:\n- type: business\n  text: the Enterprise Services are not for use by consumers and may only be used for business and professional\n    purposes\nrestricted_uses:\n- summary: Law enforcement, surveillance, tracking\n  text: prohibiting use of the Enterprise Services for law\
  \ enforcement, surveillance, tracking, etc.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/talkwalker/eligibility/talkwalker-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Talkwalker's own page on 2026-11-10.
synthetic: false
tags:
- Social Media Analytics
- Social Listening
- Brand Monitoring
- Sentiment Analysis
- Media Monitoring
- Campaign Analytics
---
