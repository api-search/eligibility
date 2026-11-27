---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “用户”是指注册、登录、使用本服务的个人。
    type: individual
  minimum_age:
    text: 未成年人应在法定监护人的陪同下阅读本协议。
    value: null
  restricted_uses:
  - summary: false information or impersonation
    text: 提交、发布虚假信息，或盗用他人资料，冒充、利用他人名义
  - summary: illegal activity via account
    text: 利用“ 合思 ”账号或本服务从事任何违法犯罪活动
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 用户提交的信息不完整或不符合法律法规的规定，则用户可能无法使用本服务或在使用本服务的过程中受到限制。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ekuaibao
provenance_date: '2026-11-09'
provider_name: Ekuaibao
provider_slug: ekuaibao
slug: ekuaibao-eligibility
source_date: '2026-11-09'
source_filename: ekuaibao-eligibility.yml
source_heading: Eligibility
source_page: https://www.ekuaibao.com/website-static/user-agreement.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ekuaibao\naid: ekuaibao\nurl: https://www.ekuaibao.com/website-static/user-agreement.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “用户”是指注册、登录、使用本服务的个人。\nrestricted_uses:\n- summary: false information or impersonation\n  text: 提交、发布虚假信息，或盗用他人资料，冒充、利用他人名义\n- summary: illegal activity via account\n  text: 利用“ 合思 ”账号或本服务从事任何违法犯罪活动\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 用户提交的信息不完整或不符合法律法规的规定，则用户可能无法使用本服务或在使用本服务的过程中受到限制。\nminimum_age:\n  value: null\n  text: 未成年人应在法定监护人的陪同下阅读本协议。\n"
source_yaml_url: https://artifacts.apis.io/ekuaibao/eligibility/ekuaibao-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Ekuaibao's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Expense Management
- Spend Management
- Travel And Expense
- Reimbursement
- Finance
- Accounting
- Invoicing
- Software-as-a-Service
- China
---
