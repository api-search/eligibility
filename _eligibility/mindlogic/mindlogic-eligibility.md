---
api_specs:
- filename: mindlogic-audio-api-openapi.yml
  format: yaml
  label: Mindlogic Audio API
  slug: mindlogic-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-audio-api-openapi.yml
- filename: mindlogic-credits-api-openapi.yml
  format: yaml
  label: Mindlogic Credits API
  slug: mindlogic-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-credits-api-openapi.yml
- filename: mindlogic-gateway-api-openapi.yml
  format: yaml
  label: Mindlogic Gateway API
  slug: mindlogic-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-gateway-api-openapi.yml
- filename: mindlogic-images-api-openapi.yml
  format: yaml
  label: Mindlogic Images API
  slug: mindlogic-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-images-api-openapi.yml
- filename: mindlogic-models-api-openapi.yml
  format: yaml
  label: Mindlogic Models API
  slug: mindlogic-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-models-api-openapi.yml
- filename: mindlogic-video-api-openapi.yml
  format: yaml
  label: Mindlogic Video API
  slug: mindlogic-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-video-api-openapi.yml
- filename: mindlogic-chat-completions-api-openapi.yml
  format: yaml
  label: Mindlogic Chat Completions API
  slug: mindlogic-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-chat-completions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 자신의 사업이나 활동 등에 서비스를 활용하기 위하여 공급자와의 사이에 서비스 이용계약을 체결한 자를 말합니다.
    type: business
  - text: 이용자 소속의 직원 등 이용자로부터 가입허가를 받아 서비스를 사용하는 자를 말합니다.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Violating law or the terms
    text: 그 밖에 법령 또는 본 약관을 위반하는 행위
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
name: Mindlogic
provenance_date: '2026-11-10'
provider_name: Mindlogic
provider_slug: mindlogic
slug: mindlogic-eligibility
source_date: '2026-11-10'
source_filename: mindlogic-eligibility.yml
source_heading: Eligibility
source_page: https://factchat-public.s3.ap-northeast-2.amazonaws.com/public/pdf/ko_terms_of_service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mindlogic\naid: mindlogic\nurl: https://factchat-public.s3.ap-northeast-2.amazonaws.com/public/pdf/ko_terms_of_service.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 자신의 사업이나 활동 등에 서비스를 활용하기 위하여 공급자와의 사이에 서비스 이용계약을 체결한 자를 말합니다.\n- type: individual\n  text: 이용자 소속의 직원 등 이용자로부터 가입허가를 받아 서비스를 사용하는 자를 말합니다.\nrestricted_uses:\n- summary: Violating law or the terms\n  text: 그 밖에 법령 또는 본 약관을 위반하는 행위\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mindlogic/eligibility/mindlogic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Mindlogic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Conversational AI
- LLM Gateway
- Chatbots
- API Gateway
- South Korea
---
