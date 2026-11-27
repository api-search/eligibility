---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 公司许可您一项个人的、不可转让的、非独占地和非商业的合法使用“辅布司”及相关服务的权利。
    type: individual
  minimum_age:
    text: 如您未满18周岁，请您在法定监护人陪同下仔细阅读并充分理解本协议
    value: '18'
  restricted_uses:
  - summary: malicious or bulk account registration
    text: 不得恶意注册 “ 辅布司 ” 账号（包括但不限于频繁注册、批量注册账号等行为）。
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: 为使用 “ 辅布司 ” 及相关服务的部分功能，您需要填写真实的身份信息，请您按照相关法律规定完成实名认证
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 360leiliang
provenance_date: '2026-11-09'
provider_name: 360leiliang
provider_slug: 360leiliang
slug: 360leiliang-eligibility
source_date: '2026-11-09'
source_filename: 360leiliang-eligibility.yml
source_heading: Eligibility
source_page: https://www.360leiliang.com/userAgreement.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 360leiliang\naid: 360leiliang\nurl: https://www.360leiliang.com/userAgreement.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 公司许可您一项个人的、不可转让的、非独占地和非商业的合法使用“辅布司”及相关服务的权利。\nrestricted_uses:\n- summary: malicious or bulk account registration\n  text: 不得恶意注册 “ 辅布司 ” 账号（包括但不限于频繁注册、批量注册账号等行为）。\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: 为使用 “ 辅布司 ” 及相关服务的部分功能，您需要填写真实的身份信息，请您按照相关法律规定完成实名认证\nminimum_age:\n  value: '18'\n  text: 如您未满18周岁，请您在法定监护人陪同下仔细阅读并充分理解本协议\n"
source_yaml_url: https://artifacts.apis.io/360leiliang/eligibility/360leiliang-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from 360leiliang's own page on 2026-11-09.
synthetic: false
tags:
- Textiles
- Lace
- Fabric
- Apparel
- Manufacturing
- B2B Marketplace
- E-Commerce
- Supply Chain
- China
- Company
---
