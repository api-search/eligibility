---
api_specs:
- filename: pyannoteai-media-api-openapi.yml
  format: yaml
  label: PyannoteAI Media API
  slug: pyannoteai-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyannoteai/openapi/pyannoteai-media-api-openapi.yml
- filename: pyannoteai-streaming-api-openapi.yml
  format: yaml
  label: PyannoteAI Streaming API
  slug: pyannoteai-streaming-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyannoteai/openapi/pyannoteai-streaming-api-openapi.yml
- filename: pyannoteai-jobs-api-openapi.yml
  format: yaml
  label: PyannoteAI Jobs API
  slug: pyannoteai-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyannoteai/openapi/pyannoteai-jobs-api-openapi.yml
- filename: pyannoteai-operations-api-openapi.yml
  format: yaml
  label: PyannoteAI Operations API
  slug: pyannoteai-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyannoteai/openapi/pyannoteai-operations-api-openapi.yml
- filename: pyannoteai-test-api-openapi.yml
  format: yaml
  label: PyannoteAI Test API
  slug: pyannoteai-test-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyannoteai/openapi/pyannoteai-test-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any professional, understood as any natural person or legal entity acting for purposes within the scope of their commercial, industrial, artisanal, liberal or agricultural activity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Professional use only; not for consumers
    text: The Services are exclusively reserved for professional use.
  - summary: Professional email address required
    text: By registering on the Platform, the Customer undertakes to use a professional email address only.
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
name: PyannoteAI
provenance_date: '2026-11-10'
provider_name: PyannoteAI
provider_slug: pyannoteai
slug: pyannoteai-eligibility
source_date: '2026-11-10'
source_filename: pyannoteai-eligibility.yml
source_heading: Eligibility
source_page: https://www.pyannote.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PyannoteAI\naid: pyannoteai\nurl: https://www.pyannote.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Any professional, understood as any natural person or legal entity acting for purposes within the scope\n    of their commercial, industrial, artisanal, liberal or agricultural activity\nrestricted_uses:\n- summary: Professional use only; not for consumers\n  text: The Services are exclusively reserved for professional use.\n- summary: Professional email address required\n  text: By registering on\
  \ the Platform, the Customer undertakes to use a professional email address only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pyannoteai/eligibility/pyannoteai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from PyannoteAI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Data
- Speech Recognition
- Speaker Diarization
- Audio
- Voice AI
- Machine Learning
- Transcription
- Streaming
- Webhook
- Real-Time
- A2A
---
