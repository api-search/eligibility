---
api_specs:
- filename: dedaluslabs-dedalus-api-api-openapi.yml
  format: yaml
  label: Dedalus Labs Dedalus API
  slug: dedaluslabs-dedalus-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dedaluslabs/openapi/dedaluslabs-dedalus-api-api-openapi.yml
- filename: dedaluslabs-health-api-openapi.yml
  format: yaml
  label: Dedalus Labs Health API
  slug: dedaluslabs-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dedaluslabs/openapi/dedaluslabs-health-api-openapi.yml
- filename: dedaluslabs-machine-lifecycle-api-openapi.yml
  format: yaml
  label: Dedalus Labs Machine Lifecycle API
  slug: dedaluslabs-machine-lifecycle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dedaluslabs/openapi/dedaluslabs-machine-lifecycle-api-openapi.yml
- filename: dedaluslabs-marketplace-api-openapi.yml
  format: yaml
  label: Dedalus Labs Marketplace API
  slug: dedaluslabs-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dedaluslabs/openapi/dedaluslabs-marketplace-api-openapi.yml
- filename: dedaluslabs-private-api-openapi.yml
  format: yaml
  label: Dedalus Labs Private API
  slug: dedaluslabs-private-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dedaluslabs/openapi/dedaluslabs-private-api-openapi.yml
- filename: dedaluslabs-webhooks-api-openapi.yml
  format: yaml
  label: Dedalus Labs Webhooks API
  slug: dedaluslabs-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dedaluslabs/openapi/dedaluslabs-webhooks-api-openapi.yml
- filename: dedaluslabs-audio-api-openapi.yml
  format: yaml
  label: Dedalus Labs Audio API
  slug: dedaluslabs-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dedaluslabs/openapi/dedaluslabs-audio-api-openapi.yml
- filename: dedaluslabs-embeddings-api-openapi.yml
  format: yaml
  label: Dedalus Labs Embeddings API
  slug: dedaluslabs-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dedaluslabs/openapi/dedaluslabs-embeddings-api-openapi.yml
- filename: dedaluslabs-images-api-openapi.yml
  format: yaml
  label: Dedalus Labs Images API
  slug: dedaluslabs-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dedaluslabs/openapi/dedaluslabs-images-api-openapi.yml
- filename: dedaluslabs-models-api-openapi.yml
  format: yaml
  label: Dedalus Labs Models API
  slug: dedaluslabs-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dedaluslabs/openapi/dedaluslabs-models-api-openapi.yml
- filename: dedaluslabs-ocr-api-openapi.yml
  format: yaml
  label: Dedalus Labs OCR API
  slug: dedaluslabs-ocr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dedaluslabs/openapi/dedaluslabs-ocr-api-openapi.yml
- filename: dedaluslabs-responses-api-openapi.yml
  format: yaml
  label: Dedalus Labs Responses API
  slug: dedaluslabs-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dedaluslabs/openapi/dedaluslabs-responses-api-openapi.yml
- filename: dedaluslabs-chat-completions-api-openapi.yml
  format: yaml
  label: Dedalus Labs Chat Completions API
  slug: dedaluslabs-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dedaluslabs/openapi/dedaluslabs-chat-completions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of majority in your jurisdiction, to enter into these Terms on your own behalf.
    type: individual
  - text: If you are accessing the Service on behalf of an organization, you must be authorized to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority in your jurisdiction, to enter into these Terms on your own behalf.
    value: '18'
  restricted_uses:
  - summary: Export control and sanctions
    text: You will not use the Service in violation of any applicable export control or sanctions law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require additional verification before provisioning Cloud Services to new accounts
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dedalus Labs
provenance_date: '2026-11-09'
provider_name: Dedalus Labs
provider_slug: dedaluslabs
slug: dedaluslabs-eligibility
source_date: '2026-11-09'
source_filename: dedaluslabs-eligibility.yml
source_heading: Eligibility
source_page: https://www.dedaluslabs.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dedalus Labs\naid: dedaluslabs\nurl: https://www.dedaluslabs.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction, to enter into these Terms\n    on your own behalf.\n- type: business\n  text: If you are accessing the Service on behalf of an organization, you must be authorized to bind that organization.\nrestricted_uses:\n- summary: Export control and sanctions\n  text: You will not use the Service in violation of any applicable export control or sanctions\
  \ law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require additional verification before provisioning Cloud Services to new accounts\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction, to enter into these Terms\n    on your own behalf.\n"
source_yaml_url: https://artifacts.apis.io/dedaluslabs/eligibility/dedaluslabs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Dedalus Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- MCP
- LLM
- Inference
- Gateways
- Compute
- Sandbox
- Developer Tools
---
