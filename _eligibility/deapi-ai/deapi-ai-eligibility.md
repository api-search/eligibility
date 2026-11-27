---
api_specs:
- filename: deapi-ai-client-api-api-openapi.yml
  format: yaml
  label: deapi-ai Client API
  slug: deapi-ai-client-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deapi-ai/openapi/deapi-ai-client-api-api-openapi.yml
- filename: deapi-ai-client-api-v2-api-openapi.yml
  format: yaml
  label: deapi-ai Client API v2 API
  slug: deapi-ai-client-api-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deapi-ai/openapi/deapi-ai-client-api-v2-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Each individual is permitted to maintain only one (1) account on the Service.
    type: individual
  - text: Where you use the Service in a business, professional, or organisational capacity, those limitations, exclusions, and disclaimers apply in full.
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction, whichever is higher) to use the Service.
    value: '18'
  restricted_uses:
  - summary: Sexually explicit and prohibited content
    text: The Service may not be used to generate, request, or distribute pornographic or sexually explicit content
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use our Service, you must create an account using one of our supported authentication methods
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: deapi-ai
provenance_date: '2026-11-09'
provider_name: deapi-ai
provider_slug: deapi-ai
slug: deapi-ai-eligibility
source_date: '2026-11-09'
source_filename: deapi-ai-eligibility.yml
source_heading: Eligibility
source_page: https://deapi.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: deapi-ai\naid: deapi-ai\nurl: https://deapi.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Each individual is permitted to maintain only one (1) account on the Service.\n- type: business\n  text: Where you use the Service in a business, professional, or organisational capacity, those limitations, exclusions,\n    and disclaimers apply in full.\nrestricted_uses:\n- summary: Sexually explicit and prohibited content\n  text: The Service may not be used to generate, request, or distribute pornographic or sexually explicit\
  \ content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use our Service, you must create an account using one of our supported authentication methods\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction, whichever is higher) to\n    use the Service.\n"
source_yaml_url: https://artifacts.apis.io/deapi-ai/eligibility/deapi-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from deapi-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Generative AI
- Open Source
- Image Generation
- Text-to-Speech
- Video Transcription
---
