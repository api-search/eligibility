---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “用户”是指注册、 登录、使用本服务的个人。
    type: individual
  minimum_age:
    text: 未成年人应在法定监护人的陪同下阅读本协议。
    value: null
  restricted_uses:
  - summary: Prohibited conduct on the service
    text: 用户不能利用酷划账号或酷划在线提供的服务进行如下行为：
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: “酷划”账号应当使用手机号码绑定注册
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: coohua
provenance_date: '2026-11-09'
provider_name: coohua
provider_slug: coohua
slug: coohua-eligibility
source_date: '2026-11-09'
source_filename: coohua-eligibility.yml
source_heading: Eligibility
source_page: https://www.coohua.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: coohua\naid: coohua\nurl: https://www.coohua.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “用户”是指注册、 登录、使用本服务的个人。\nrestricted_uses:\n- summary: Prohibited conduct on the service\n  text: 用户不能利用酷划账号或酷划在线提供的服务进行如下行为：\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: “酷划”账号应当使用手机号码绑定注册\nminimum_age:\n  value: null\n  text: 未成年人应在法定监护人的陪同下阅读本协议。\n"
source_yaml_url: https://artifacts.apis.io/coohua/eligibility/coohua-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from coohua's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Mobile
- AdTech
- Incentive Advertising
- China
- Consumer
---
