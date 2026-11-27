---
api_specs:
- filename: civitai-blobs-api-openapi.yml
  format: yaml
  label: Civitai Blobs API
  slug: civitai-blobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-blobs-api-openapi.yml
- filename: civitai-creators-api-openapi.yml
  format: yaml
  label: Civitai Creators API
  slug: civitai-creators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-creators-api-openapi.yml
- filename: civitai-enums-api-openapi.yml
  format: yaml
  label: Civitai Enums API
  slug: civitai-enums-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-enums-api-openapi.yml
- filename: civitai-images-api-openapi.yml
  format: yaml
  label: Civitai Images API
  slug: civitai-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-images-api-openapi.yml
- filename: civitai-models-api-openapi.yml
  format: yaml
  label: Civitai Models API
  slug: civitai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-models-api-openapi.yml
- filename: civitai-permissions-api-openapi.yml
  format: yaml
  label: Civitai Permissions API
  slug: civitai-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-permissions-api-openapi.yml
- filename: civitai-tags-api-openapi.yml
  format: yaml
  label: Civitai Tags API
  slug: civitai-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-tags-api-openapi.yml
- filename: civitai-users-api-openapi.yml
  format: yaml
  label: Civitai Users API
  slug: civitai-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-users-api-openapi.yml
- filename: civitai-vault-api-openapi.yml
  format: yaml
  label: Civitai Vault API
  slug: civitai-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-vault-api-openapi.yml
- filename: civitai-workflows-api-openapi.yml
  format: yaml
  label: Civitai Workflows API
  slug: civitai-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-workflows-api-openapi.yml
- filename: civitai-model-versions-api-openapi.yml
  format: yaml
  label: Civitai Model Versions API
  slug: civitai-model-versions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-model-versions-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are prohibited under applicable law from using the Service, then you may not use it.
  entity_types:
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Adult content
    text: Pornography and other mature audience content (including literature, imagery, and other media) depicting nudity or explicit sexual acts
  - summary: Likeness of real people
    text: Content that uses, reproduces, or is based on the likeness of real people - living or deceased - including public figures, celebrities, influencers, and private individuals, in any context.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access most features of the Service, you must register for an account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Civitai
provenance_date: '2026-11-09'
provider_name: Civitai
provider_slug: civitai
slug: civitai-eligibility
source_date: '2026-11-09'
source_filename: civitai-eligibility.yml
source_heading: Eligibility
source_page: https://civitai.com/content/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Civitai\naid: civitai\nurl: https://civitai.com/content/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: If you are prohibited under applicable law from using the Service, then you may not use it.\nentity_types:\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Adult content\n  text: Pornography and other mature audience content (including literature, imagery, and other media)\
  \ depicting\n    nudity or explicit sexual acts\n- summary: Likeness of real people\n  text: Content that uses, reproduces, or is based on the likeness of real people - living or deceased - including\n    public figures, celebrities, influencers, and private individuals, in any context.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access most features of the Service, you must register for an account\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/civitai/eligibility/civitai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Civitai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Image Generation
- Video Generation
- Stable Diffusion
- SDXL
- Flux
- LoRA
- Model Hosting
- Community
- Generative AI
---
