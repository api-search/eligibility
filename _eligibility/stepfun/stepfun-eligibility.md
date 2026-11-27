---
api_specs:
- filename: stepfun-realtime-asyncapi.yml
  format: yaml
  label: StepFun Realtime API
  slug: realtime-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/stepfun/asyncapi/stepfun-realtime-asyncapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 成年人个人用户
    type: individual
  - text: 本平台主要面向企业客户和成年人个人用户
    type: business
  minimum_age:
    text: 本平台主要面向企业客户和成年人个人用户
    value: null
  restricted_uses:
  - summary: Financial-institution data analysis/investment services
    text: 您不应将本服务用于金融数据相关大模型技术合作（如将服务应用于向银行、证券公司、保险公司、信托投资公司和基金管理公司等金融机构提供数据分析、投资研究、投资顾问或投资者教育等服务）。
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
name: StepFun
provenance_date: '2026-11-10'
provider_name: StepFun
provider_slug: stepfun
slug: stepfun-eligibility
source_date: '2026-11-10'
source_filename: stepfun-eligibility.yml
source_heading: Eligibility
source_page: https://platform.stepfun.com/docs/zh/agreement/userservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StepFun\naid: stepfun\nurl: https://platform.stepfun.com/docs/zh/agreement/userservice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 成年人个人用户\n- type: business\n  text: 本平台主要面向企业客户和成年人个人用户\nrestricted_uses:\n- summary: Financial-institution data analysis/investment services\n  text: 您不应将本服务用于金融数据相关大模型技术合作（如将服务应用于向银行、证券公司、保险公司、信托投资公司和基金管理公司等金融机构提供数据分析、投资研究、投资顾问或投资者教育等服务）。\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: 本平台主要面向企业客户和成年人个人用户\n"
source_yaml_url: https://artifacts.apis.io/stepfun/eligibility/stepfun-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from StepFun's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Multi-Modal
- Chat Completions
- Audio
- Speech
- Text-to-Speech
- Speech Recognition
- Image
- Real-Time
- Vector Stores
- China
---
