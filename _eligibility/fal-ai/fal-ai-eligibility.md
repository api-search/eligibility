---
api_specs:
- filename: fal-ai-asyncapi.yml
  format: yaml
  label: fal Realtime API
  slug: fal-realtime-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/fal-ai/asyncapi/fal-ai-asyncapi.yml
- filename: fal-ai-asyncapi.yml
  format: yaml
  label: fal Streaming API
  slug: fal-streaming-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/fal-ai/asyncapi/fal-ai-asyncapi.yml
- filename: fal-ai-apps-api-openapi.yml
  format: yaml
  label: fal Apps API
  slug: fal-ai-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fal-ai/openapi/fal-ai-apps-api-openapi.yml
- filename: fal-ai-files-api-openapi.yml
  format: yaml
  label: fal Files API
  slug: fal-ai-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fal-ai/openapi/fal-ai-files-api-openapi.yml
- filename: fal-ai-queue-api-openapi.yml
  format: yaml
  label: fal Queue API
  slug: fal-ai-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fal-ai/openapi/fal-ai-queue-api-openapi.yml
- filename: fal-ai-secrets-api-openapi.yml
  format: yaml
  label: fal Secrets API
  slug: fal-ai-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fal-ai/openapi/fal-ai-secrets-api-openapi.yml
- filename: fal-ai-storage-api-openapi.yml
  format: yaml
  label: fal Storage API
  slug: fal-ai-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fal-ai/openapi/fal-ai-storage-api-openapi.yml
- filename: fal-ai-streaming-api-openapi.yml
  format: yaml
  label: fal Streaming API
  slug: fal-ai-streaming-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fal-ai/openapi/fal-ai-streaming-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In order to use ourServices, you must be 18 years of age (or the age of legal majority where you live).
    type: individual
  - text: Company may allow you to create a “Team Organization” account to which you can invite team members
    type: business
  minimum_age:
    text: you must be 18 years of age (or the age of legal majority where you live)
    value: '18'
  restricted_uses:
  - summary: Export-restricted parties
    text: You represent, warrant and covenant that you are not (a) located in, or a resident or a national of, any country subject to a U.S. government embargo or other restriction
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
name: fal
provenance_date: '2026-11-09'
provider_name: fal
provider_slug: fal-ai
slug: fal-ai-eligibility
source_date: '2026-11-09'
source_filename: fal-ai-eligibility.yml
source_heading: Eligibility
source_page: https://fal.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fal\naid: fal-ai\nurl: https://fal.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: In order to use ourServices, you must be 18 years of age (or the age of legal majority where you live).\n- type: business\n  text: Company may allow you to create a “Team Organization” account to which you can invite team members\nrestricted_uses:\n- summary: Export-restricted parties\n  text: You represent, warrant and covenant that you are not (a) located in, or a resident or a national of, any\n    country subject to a U.S.\
  \ government embargo or other restriction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be 18 years of age (or the age of legal majority where you live)\n"
source_yaml_url: https://artifacts.apis.io/fal-ai/eligibility/fal-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from fal's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Generative AI
- Generative Media
- Image Generation
- Video Generation
- Audio Generation
- Inference
- Serverless
- GPU
- MCP
- Real-Time
---
