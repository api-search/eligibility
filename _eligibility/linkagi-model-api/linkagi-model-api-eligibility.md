---
api_specs:
- filename: linkagi-model-api-anthropic-style-route-api-openapi.yml
  format: yaml
  label: LinkAGI Model API Anthropic-style route API
  slug: linkagi-model-api-anthropic-style-route-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkagi-model-api/openapi/linkagi-model-api-anthropic-style-route-api-openapi.yml
- filename: linkagi-model-api-discovery-api-openapi.yml
  format: yaml
  label: LinkAGI Model API Discovery API
  slug: linkagi-model-api-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkagi-model-api/openapi/linkagi-model-api-discovery-api-openapi.yml
- filename: linkagi-model-api-gemini-style-route-api-openapi.yml
  format: yaml
  label: LinkAGI Model API Gemini-style route API
  slug: linkagi-model-api-gemini-style-route-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkagi-model-api/openapi/linkagi-model-api-gemini-style-route-api-openapi.yml
- filename: linkagi-model-api-openai-compatible-api-openapi.yml
  format: yaml
  label: LinkAGI Model API OpenAI compatible API
  slug: linkagi-model-api-openai-compatible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkagi-model-api/openapi/linkagi-model-api-openai-compatible-api-openapi.yml
- filename: linkagi-model-api-public-metadata-api-openapi.yml
  format: yaml
  label: LinkAGI Model API Public metadata API
  slug: linkagi-model-api-public-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkagi-model-api/openapi/linkagi-model-api-public-metadata-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 用户应具备与其使用行为相适应的民事行为能力，并使用可正常接收通知的邮箱注册。
    type: individual
  minimum_age:
    text: 用户应具备与其使用行为相适应的民事行为能力
    value: null
  restricted_uses:
  - summary: High-risk scenarios require user verification
    text: 用户应在生产、医疗、法律、金融、安全及其他高风险场景自行验证结果并承担使用判断。
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 用户应保证注册信息真实、合法、有效，不得转让、出租账号，不得批量注册、冒用他人身份或规避安全限制。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LinkAGI Model API
provenance_date: '2026-11-09'
provider_name: LinkAGI Model API
provider_slug: linkagi-model-api
slug: linkagi-model-api-eligibility
source_date: '2026-11-09'
source_filename: linkagi-model-api-eligibility.yml
source_heading: Eligibility
source_page: https://api.linktoagi.com/user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LinkAGI Model API\naid: linkagi-model-api\nurl: https://api.linktoagi.com/user-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 用户应具备与其使用行为相适应的民事行为能力，并使用可正常接收通知的邮箱注册。\nrestricted_uses:\n- summary: High-risk scenarios require user verification\n  text: 用户应在生产、医疗、法律、金融、安全及其他高风险场景自行验证结果并承担使用判断。\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 用户应保证注册信息真实、合法、有效，不得转让、出租账号，不得批量注册、冒用他人身份或规避安全限制。\nminimum_age:\n  value: null\n  text: 用户应具备与其使用行为相适应的民事行为能力\n"
source_yaml_url: https://artifacts.apis.io/linkagi-model-api/eligibility/linkagi-model-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from LinkAGI Model API's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- AI API Gateway
- Relay
- OpenAI-Compatible
- Anthropic Compatible
- Gemini-compatible
- Developer Tools
- CLI coding agents
- Model Routing
- China
---
