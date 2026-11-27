---
api_specs:
- filename: cuddler-ai-platform-api-api-openapi.yml
  format: yaml
  label: Cuddler Platform API
  slug: cuddler-ai-platform-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cuddler-ai/openapi/cuddler-ai-platform-api-api-openapi.yml
- filename: cuddler-ai-platform-ark-api-openapi.yml
  format: yaml
  label: Cuddler Platform Ark API
  slug: cuddler-ai-platform-ark-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cuddler-ai/openapi/cuddler-ai-platform-ark-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use the Service. If you are under 18, you must have parental consent.
    type: individual
  - source: https://platform.cuddler.ai/legal/api-terms
    text: The API is offered to businesses and other organizations only, not to consumers.
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Harmful or misleading AI content
    text: You may not use AI-generated content for illegal purposes, harassment, or to create misleading information.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    source: https://platform.cuddler.ai/legal/api-terms
    text: You may register a standard organization through the console without an application or manual approval. We may request additional information to verify account details or investigate misuse.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cuddler
provenance_date: '2026-11-09'
provider_name: Cuddler
provider_slug: cuddler-ai
slug: cuddler-ai-eligibility
source_date: '2026-11-09'
source_filename: cuddler-ai-eligibility.yml
source_heading: Eligibility
source_page: https://cuddler.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cuddler\naid: cuddler-ai\nurl: https://cuddler.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://cuddler.ai/terms\n  - https://platform.cuddler.ai/legal/api-terms\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service. If you are under 18, you must have parental consent.\n- type: business\n  text: The API is offered to businesses and other organizations only, not to consumers.\n  source: https://platform.cuddler.ai/legal/api-terms\nrestricted_uses:\n- summary: Harmful or misleading AI content\n  text:\
  \ You may not use AI-generated content for illegal purposes, harassment, or to create misleading information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: You may register a standard organization through the console without an application or manual approval.\n    We may request additional information to verify account details or investigate misuse.\n  source: https://platform.cuddler.ai/legal/api-terms\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cuddler-ai/eligibility/cuddler-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Cuddler's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video Generation
- Image Generation
- Interactive Storytelling
- Generative Media
- MCP
---
