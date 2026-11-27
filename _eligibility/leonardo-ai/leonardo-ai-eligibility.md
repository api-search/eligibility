---
api_specs:
- filename: leonardo-ai-3d-model-assets-api-openapi.yml
  format: yaml
  label: Leonardo.AI 3D Model Assets API
  slug: leonardo-ai-3d-model-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-3d-model-assets-api-openapi.yml
- filename: leonardo-ai-blueprints-api-openapi.yml
  format: yaml
  label: Leonardo.AI Blueprints API
  slug: leonardo-ai-blueprints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-blueprints-api-openapi.yml
- filename: leonardo-ai-dataset-api-openapi.yml
  format: yaml
  label: Leonardo.AI Dataset API
  slug: leonardo-ai-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-dataset-api-openapi.yml
- filename: leonardo-ai-elements-api-openapi.yml
  format: yaml
  label: Leonardo.AI Elements API
  slug: leonardo-ai-elements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-elements-api-openapi.yml
- filename: leonardo-ai-image-api-openapi.yml
  format: yaml
  label: Leonardo.AI Image API
  slug: leonardo-ai-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-image-api-openapi.yml
- filename: leonardo-ai-init-images-api-openapi.yml
  format: yaml
  label: Leonardo.AI Init Images API
  slug: leonardo-ai-init-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-init-images-api-openapi.yml
- filename: leonardo-ai-media-api-openapi.yml
  format: yaml
  label: Leonardo.AI Media API
  slug: leonardo-ai-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-media-api-openapi.yml
- filename: leonardo-ai-models-api-openapi.yml
  format: yaml
  label: Leonardo.AI Models API
  slug: leonardo-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-models-api-openapi.yml
- filename: leonardo-ai-motion-api-openapi.yml
  format: yaml
  label: Leonardo.AI Motion API
  slug: leonardo-ai-motion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-motion-api-openapi.yml
- filename: leonardo-ai-pricing-calculator-api-openapi.yml
  format: yaml
  label: Leonardo.AI Pricing Calculator API
  slug: leonardo-ai-pricing-calculator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-pricing-calculator-api-openapi.yml
- filename: leonardo-ai-prompt-api-openapi.yml
  format: yaml
  label: Leonardo.AI Prompt API
  slug: leonardo-ai-prompt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-prompt-api-openapi.yml
- filename: leonardo-ai-realtime-canvas-api-openapi.yml
  format: yaml
  label: Leonardo.AI Realtime Canvas API
  slug: leonardo-ai-realtime-canvas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-realtime-canvas-api-openapi.yml
- filename: leonardo-ai-user-api-openapi.yml
  format: yaml
  label: Leonardo.AI User API
  slug: leonardo-ai-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-user-api-openapi.yml
- filename: leonardo-ai-variation-api-openapi.yml
  format: yaml
  label: Leonardo.AI Variation API
  slug: leonardo-ai-variation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-variation-api-openapi.yml
- filename: leonardo-ai-generations-api-openapi.yml
  format: yaml
  label: Leonardo.AI Generations API
  slug: leonardo-ai-generations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leonardo-ai/openapi/leonardo-ai-generations-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: any entity you are authorised to represent (such as your employer)
    type: business
  minimum_age:
    text: You must be at least 13 years old (or the minimum legal age required to provide consent for processing of personal data in the country where the child is located).
    value: '13'
  restricted_uses:
  - summary: Prohibited generated content
    text: Generating content that includes impersonations of any real person or falsely portrays an individual in a misleading or defamatory way
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Leonardo.AI
provenance_date: '2026-11-09'
provider_name: Leonardo.AI
provider_slug: leonardo-ai
slug: leonardo-ai-eligibility
source_date: '2026-11-09'
source_filename: leonardo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://leonardo.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Leonardo.AI\naid: leonardo-ai\nurl: https://leonardo.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: business\n  text: any entity you are authorised to represent (such as your employer)\nrestricted_uses:\n- summary: Prohibited generated content\n  text: Generating content that includes impersonations of any real person or falsely portrays an individual in\n    a misleading\
  \ or defamatory way\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old (or the minimum legal age required to provide consent for processing of\n    personal data in the country where the child is located).\n"
source_yaml_url: https://artifacts.apis.io/leonardo-ai/eligibility/leonardo-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Leonardo.AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Image Generation
- Video Generation
- Generative AI
- Creative
- 3D
- Diffusion Models
- Canva
---
