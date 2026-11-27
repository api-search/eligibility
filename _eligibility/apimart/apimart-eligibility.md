---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: APIMart provides API access to third-party AI models for chat, image generation, and video generation to users worldwide.
  entity_types:
  - text: we provide developers and businesses with stable, cost-effective access to mainstream AI models
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or harmful content
    text: Use our APIs to generate inappropriate, harmful, illegal, or abusive content
  - summary: Deceptive content
    text: Use our AI models to create deceptive, misleading, or fraudulent content
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
name: APIMart
provenance_date: '2026-11-09'
provider_name: APIMart
provider_slug: apimart
slug: apimart-eligibility
source_date: '2026-11-09'
source_filename: apimart-eligibility.yml
source_heading: Eligibility
source_page: https://apimart.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: APIMart\naid: apimart\nurl: https://apimart.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: APIMart provides API access to third-party AI models for chat, image generation, and video generation to\n    users worldwide.\nentity_types:\n- type: business\n  text: we provide developers and businesses with stable, cost-effective access to mainstream AI models\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Use our APIs to generate inappropriate, harmful, illegal, or abusive content\n- summary: Deceptive content\n  text: Use our AI models to create deceptive,\
  \ misleading, or fraudulent content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apimart/eligibility/apimart-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from APIMart's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- AI Gateway
- Image Generation
- Video Generation
- OpenAI-Compatible
- Text-to-Speech
---
