---
api_specs:
- filename: aihot-news-agent-api-openapi.yml
  format: yaml
  label: AIHOT Agent API
  slug: aihot-news-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-agent-api-openapi.yml
- filename: aihot-news-dailies-api-openapi.yml
  format: yaml
  label: AIHOT Dailies API
  slug: aihot-news-dailies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-dailies-api-openapi.yml
- filename: aihot-news-hot-topics-api-openapi.yml
  format: yaml
  label: AIHOT Hot Topics API
  slug: aihot-news-hot-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-hot-topics-api-openapi.yml
- filename: aihot-news-items-api-openapi.yml
  format: yaml
  label: AIHOT Items API
  slug: aihot-news-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-items-api-openapi.yml
- filename: aihot-news-monthlies-api-openapi.yml
  format: yaml
  label: AIHOT Monthlies API
  slug: aihot-news-monthlies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-monthlies-api-openapi.yml
- filename: aihot-news-selected-api-openapi.yml
  format: yaml
  label: AIHOT Selected API
  slug: aihot-news-selected-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-selected-api-openapi.yml
- filename: aihot-news-stories-api-openapi.yml
  format: yaml
  label: AIHOT Stories API
  slug: aihot-news-stories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-stories-api-openapi.yml
- filename: aihot-news-weeklies-api-openapi.yml
  format: yaml
  label: AIHOT Weeklies API
  slug: aihot-news-weeklies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-weeklies-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 学校、研究机构、公益组织或开源社区开展不收费、不接受商业赞助、不向客户交付的公益非商业项目。
    type: nonprofit
  - text: 企业、机关、学校或其他组织仅供本组织成员内部研究、内部情报、内部知识库或内部决策使用
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: commercial uses need prior written authorisation
    text: 任何面向客户、会员、公众或外部合作方的商业产品、收费功能、广告或赞助业务、咨询或客户交付、研究报告、数据库、榜单、插件、机器人、模型应用或其他营利场景。
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 只有把 AIHOT 用于对外商业产品、收费服务、客户交付、公开镜像或转售时，才需要提前联系我们取得书面授权。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AIHOT
provenance_date: '2026-11-09'
provider_name: AIHOT
provider_slug: aihot-news
slug: aihot-news-eligibility
source_date: '2026-11-09'
source_filename: aihot-news-eligibility.yml
source_heading: Eligibility
source_page: https://aihot.news/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIHOT\naid: aihot-news\nurl: https://aihot.news/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: nonprofit\n  text: 学校、研究机构、公益组织或开源社区开展不收费、不接受商业赞助、不向客户交付的公益非商业项目。\n- type: business\n  text: 企业、机关、学校或其他组织仅供本组织成员内部研究、内部情报、内部知识库或内部决策使用\nrestricted_uses:\n- summary: commercial uses need prior written authorisation\n  text: 任何面向客户、会员、公众或外部合作方的商业产品、收费功能、广告或赞助业务、咨询或客户交付、研究报告、数据库、榜单、插件、机器人、模型应用或其他营利场景。\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 只有把 AIHOT 用于对外商业产品、收费服务、客户交付、公开镜像或转售时，才需要提前联系我们取得书面授权。\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aihot-news/eligibility/aihot-news-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from AIHOT's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
