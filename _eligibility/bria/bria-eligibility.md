---
api_specs:
- filename: bria-automotive-endpoints-api-openapi.yml
  format: yaml
  label: Bria Automotive Endpoints API
  slug: bria-automotive-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-automotive-endpoints-api-openapi.yml
- filename: bria-dataset-api-openapi.yml
  format: yaml
  label: Bria Dataset API
  slug: bria-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-dataset-api-openapi.yml
- filename: bria-editing-endpoints-api-openapi.yml
  format: yaml
  label: Bria Editing Endpoints API
  slug: bria-editing-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-editing-endpoints-api-openapi.yml
- filename: bria-endpoints-api-openapi.yml
  format: yaml
  label: Bria Endpoints API
  slug: bria-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-endpoints-api-openapi.yml
- filename: bria-image-attribution-api-openapi.yml
  format: yaml
  label: Bria Image Attribution API
  slug: bria-image-attribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-image-attribution-api-openapi.yml
- filename: bria-image-generation-api-openapi.yml
  format: yaml
  label: Bria Image Generation API
  slug: bria-image-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-image-generation-api-openapi.yml
- filename: bria-masking-endpoints-api-openapi.yml
  format: yaml
  label: Bria Masking Endpoints API
  slug: bria-masking-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-masking-endpoints-api-openapi.yml
- filename: bria-model-api-openapi.yml
  format: yaml
  label: Bria Model API
  slug: bria-model-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-model-api-openapi.yml
- filename: bria-product-endpoints-api-openapi.yml
  format: yaml
  label: Bria Product Endpoints API
  slug: bria-product-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-product-endpoints-api-openapi.yml
- filename: bria-project-api-openapi.yml
  format: yaml
  label: Bria Project API
  slug: bria-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-project-api-openapi.yml
- filename: bria-v2-endpoints-api-openapi.yml
  format: yaml
  label: Bria v2 endpoints API
  slug: bria-v2-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-v2-endpoints-api-openapi.yml
- filename: bria-video-attribution-api-openapi.yml
  format: yaml
  label: Bria Video Attribution API
  slug: bria-video-attribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-video-attribution-api-openapi.yml
- filename: bria-video-generation-api-openapi.yml
  format: yaml
  label: Bria Video Generation API
  slug: bria-video-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-video-generation-api-openapi.yml
- filename: bria-fastapi-api-openapi.yml
  format: yaml
  label: Bria Fast API
  slug: bria-fastapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-fastapi-api-openapi.yml
- filename: bria-health-api-openapi.yml
  format: yaml
  label: Bria Health API
  slug: bria-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bria/openapi/bria-health-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, organized under the laws of, or ordinarily resident in any country or territory subject to comprehensive U.S. economic sanctions.
  entity_types:
  - text: The Services are only intended for individuals aged eighteen (18) years or older.
    type: individual
  - text: If you are entering into these Terms on behalf of a company or another legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: The Services are only intended for individuals aged eighteen (18) years or older.
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
name: Bria
provenance_date: '2026-11-09'
provider_name: Bria
provider_slug: bria
slug: bria-eligibility
source_date: '2026-11-09'
source_filename: bria-eligibility.yml
source_heading: Eligibility
source_page: https://bria.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bria\naid: bria\nurl: https://bria.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, organized under the laws of, or ordinarily resident in any country\n    or territory subject to comprehensive U.S. economic sanctions.\nentity_types:\n- type: individual\n  text: The Services are only intended for individuals aged eighteen (18) years or older.\n- type: business\n  text: If you are entering into these Terms on behalf of a company or another legal entity, you represent that\n    you have the authority to bind such entity\nrestricted_uses:\
  \ []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are only intended for individuals aged eighteen (18) years or older.\n"
source_yaml_url: https://artifacts.apis.io/bria/eligibility/bria-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Bria's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Generative AI
- Image
- Image Generation
- Image Editing
- Video
- Machine Learning
- Media
- Content
- Agents
- MCP
---
