---
api_specs:
- filename: kook-bot-kook-api-openapi.yml
  format: yaml
  label: KOOK 将Bot连接到 KOOK 服务器 API
  slug: kook-bot-kook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kook/openapi/kook-bot-kook-api-openapi.yml
- filename: kook-default-api-openapi.yml
  format: yaml
  label: KOOK 事件通知介绍 API
  slug: kook-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kook/openapi/kook-default-api-openapi.yml
- filename: kook-gateway-api-openapi.yml
  format: yaml
  label: KOOK Gateway接口 API
  slug: kook-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kook/openapi/kook-gateway-api-openapi.yml
- filename: kook-kmarkdown-api-openapi.yml
  format: yaml
  label: KOOK K Markdown与卡片消息 API
  slug: kook-kmarkdown-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kook/openapi/kook-kmarkdown-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 您应是具备完全民事行为能力的自然人、法人或其他组织
    type: individual
  - text: 您应是具备完全民事行为能力的自然人、法人或其他组织
    type: business
  minimum_age:
    text: 未满 8 周岁未成年人不得注册使用本服务
    value: '8'
  restricted_uses:
  - summary: Accelerator not for illegal use
    text: 不得用于访问非法网站、从事违法犯罪活动
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
name: KOOK
provenance_date: '2026-11-09'
provider_name: KOOK
provider_slug: kook
slug: kook-eligibility
source_date: '2026-11-09'
source_filename: kook-eligibility.yml
source_heading: Eligibility
source_page: https://www.kookapp.cn/protocol.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KOOK\naid: kook\nurl: https://www.kookapp.cn/protocol.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 您应是具备完全民事行为能力的自然人、法人或其他组织\n- type: business\n  text: 您应是具备完全民事行为能力的自然人、法人或其他组织\nrestricted_uses:\n- summary: Accelerator not for illegal use\n  text: 不得用于访问非法网站、从事违法犯罪活动\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '8'\n  text: 未满 8 周岁未成年人不得注册使用本服务\n"
source_yaml_url: https://artifacts.apis.io/kook/eligibility/kook-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from KOOK's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice Communication
- Gaming
- Community
- Real-Time
---
