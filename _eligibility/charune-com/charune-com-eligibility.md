---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 契语只面向年满 18 周岁的用户。
    type: individual
  minimum_age:
    text: 契语只面向年满 18 周岁的用户。
    value: '18'
  restricted_uses:
  - summary: minors
    text: AI 角色聊天可能不适合部分未成年人。
  - summary: impersonation and illegal characters
    text: 请不要创建冒充真实人物、侵犯他人权利或违法的角色
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 注册可以验证邮箱并设置密码，也可以用通行密钥；
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Charune
provenance_date: '2026-11-09'
provider_name: Charune
provider_slug: charune-com
slug: charune-com-eligibility
source_date: '2026-11-09'
source_filename: charune-com-eligibility.yml
source_heading: Eligibility
source_page: https://charune.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Charune\naid: charune-com\nurl: https://charune.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 契语只面向年满 18 周岁的用户。\nrestricted_uses:\n- summary: minors\n  text: AI 角色聊天可能不适合部分未成年人。\n- summary: impersonation and illegal characters\n  text: 请不要创建冒充真实人物、侵犯他人权利或违法的角色\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 注册可以验证邮箱并设置密码，也可以用通行密钥；\nminimum_age:\n  value: '18'\n  text: 契语只面向年满 18 周岁的用户。\n"
source_yaml_url: https://artifacts.apis.io/charune-com/eligibility/charune-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Charune's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
