---
api_specs:
- filename: google-gemini-auth-tokens-api-openapi.yml
  format: yaml
  label: Google Gemini Gemini Auth Tokens API
  slug: google-gemini-auth-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gemini/openapi/google-gemini-auth-tokens-api-openapi.yml
- filename: google-gemini-batches-api-openapi.yml
  format: yaml
  label: Google Gemini Gemini Batches API
  slug: google-gemini-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gemini/openapi/google-gemini-batches-api-openapi.yml
- filename: google-gemini-corpora-api-openapi.yml
  format: yaml
  label: Google Gemini Gemini Corpora API
  slug: google-gemini-corpora-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gemini/openapi/google-gemini-corpora-api-openapi.yml
- filename: google-gemini-dynamic-api-openapi.yml
  format: yaml
  label: Google Gemini Gemini Dynamic API
  slug: google-gemini-dynamic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gemini/openapi/google-gemini-dynamic-api-openapi.yml
- filename: google-gemini-environments-api-openapi.yml
  format: yaml
  label: Google Gemini Gemini Environments API
  slug: google-gemini-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gemini/openapi/google-gemini-environments-api-openapi.yml
- filename: google-gemini-files-api-openapi.yml
  format: yaml
  label: Google Gemini Gemini Files API
  slug: google-gemini-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gemini/openapi/google-gemini-files-api-openapi.yml
- filename: google-gemini-media-api-openapi.yml
  format: yaml
  label: Google Gemini Gemini Media API
  slug: google-gemini-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gemini/openapi/google-gemini-media-api-openapi.yml
- filename: google-gemini-models-api-openapi.yml
  format: yaml
  label: Google Gemini Gemini Models API
  slug: google-gemini-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gemini/openapi/google-gemini-models-api-openapi.yml
- filename: google-gemini-cachedcontents-api-openapi.yml
  format: yaml
  label: Google Gemini Cached Contents API
  slug: google-gemini-cachedcontents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gemini/openapi/google-gemini-cachedcontents-api-openapi.yml
- filename: google-gemini-filesearchstores-api-openapi.yml
  format: yaml
  label: Google Gemini File Search Stores API
  slug: google-gemini-filesearchstores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gemini/openapi/google-gemini-filesearchstores-api-openapi.yml
- filename: google-gemini-generatedfiles-api-openapi.yml
  format: yaml
  label: Google Gemini Generated Files API
  slug: google-gemini-generatedfiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gemini/openapi/google-gemini-generatedfiles-api-openapi.yml
- filename: google-gemini-tunedmodels-api-openapi.yml
  format: yaml
  label: Google Gemini Tuned Models API
  slug: google-gemini-tunedmodels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gemini/openapi/google-gemini-tunedmodels-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may only access the Services (or make API Clients available to users) within an available region.
  entity_types:
  - text: Use of Google AI Studio and Gemini API is for developers building with Google AI models for professional or business purposes, not for consumer use.
    type: developer
  minimum_age:
    text: You must be 18 years of age or older to use the APIs.
    value: '18'
  restricted_uses:
  - summary: Medical and clinical use
    text: You may not use the Services in clinical practice, to provide medical advice, or in any manner that is overseen by or requires clearance or approval from a medical device regulatory agency.
  - summary: Safety-critical robotics use
    text: 'to not use the Robotics Models for safety-critical applications or work, such as in the following settings: (i) healthcare, (ii) transportation, or (iii) other areas where safety protocols are vital'
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
name: Google Gemini
provenance_date: '2026-11-09'
provider_name: Google Gemini
provider_slug: google-gemini
slug: google-gemini-eligibility
source_date: '2026-11-09'
source_filename: google-gemini-eligibility.yml
source_heading: Eligibility
source_page: https://aistudio.google.com/docs/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Gemini\naid: google-gemini\nurl: https://aistudio.google.com/docs/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may only access the Services (or make API Clients available to users) within an available region.\nentity_types:\n- type: developer\n  text: Use of Google AI Studio and Gemini API is for developers building with Google AI models for professional\n    or business purposes, not for consumer use.\nrestricted_uses:\n- summary: Medical and clinical use\n  text: You may not use the Services in clinical practice, to provide medical advice, or in any manner that\
  \ is overseen\n    by or requires clearance or approval from a medical device regulatory agency.\n- summary: Safety-critical robotics use\n  text: 'to not use the Robotics Models for safety-critical applications or work, such as in the following settings:\n    (i) healthcare, (ii) transportation, or (iii) other areas where safety protocols are vital'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use the APIs.\n"
source_yaml_url: https://artifacts.apis.io/google-gemini/eligibility/google-gemini-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Google Gemini's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Artificial Intelligence
- Code Generation
- Embeddings
- Generative AI
- Image Generation
- LLM
- Machine Learning
- Multi-Modal
- Real-Time
- Foundation Models
- Agents
- Audio Understanding
- Batch Processing
- Deep Research
- Document Understanding
- Function Calling
- Structured Output
- Text-to-Speech
- Video Generation
- Video Understanding
---
