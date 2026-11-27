---
api_specs:
- filename: lm-studio-anthropic-compatibility-api-openapi.yml
  format: yaml
  label: LM Studio Anthropic Compatibility API
  slug: lm-studio-anthropic-compatibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lm-studio/openapi/lm-studio-anthropic-compatibility-api-openapi.yml
- filename: lm-studio-chat-api-openapi.yml
  format: yaml
  label: LM Studio Chat API
  slug: lm-studio-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lm-studio/openapi/lm-studio-chat-api-openapi.yml
- filename: lm-studio-models-api-openapi.yml
  format: yaml
  label: LM Studio Models API
  slug: lm-studio-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lm-studio/openapi/lm-studio-models-api-openapi.yml
- filename: lm-studio-openai-compatibility-api-openapi.yml
  format: yaml
  label: LM Studio OpenAI Compatibility API
  slug: lm-studio-openai-compatibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lm-studio/openapi/lm-studio-openai-compatibility-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Sanctioned Country restrictions: You represent that You are not located in, organized under the laws of, or ordinarily resident in any country or territory subject to territorial sanctions'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You agree not to, directly or indirectly, use, sell, supply, export, reexport, transfer, divert, release, or otherwise dispose of any products, software, or technology
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
name: LM Studio
provenance_date: '2026-11-09'
provider_name: LM Studio
provider_slug: lm-studio
slug: lm-studio-eligibility
source_date: '2026-11-09'
source_filename: lm-studio-eligibility.yml
source_heading: Eligibility
source_page: https://lmstudio.ai/app-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LM Studio\naid: lm-studio\nurl: https://lmstudio.ai/app-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Sanctioned Country restrictions: You represent that You are not located in, organized under the laws of,\n    or ordinarily resident in any country or territory subject to territorial sanctions'\nentity_types: []\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: You agree not to, directly or indirectly, use, sell, supply, export, reexport, transfer, divert, release,\n    or otherwise dispose of any products, software, or technology\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lm-studio/eligibility/lm-studio-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from LM Studio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Local LLM
- Machine Learning
- Inference
- Developer Tools
- LLM
- MCP
- SDK
- Desktop Application
---
