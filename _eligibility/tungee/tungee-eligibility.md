---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 产品使用范围仅限于您开展经营范围内的业务。
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited industries for intelligent calling product
    text: 您不得使用探迹智能呼叫产品用于以下行业类型：1）药品、保健品、替代母乳的婴儿乳制品、饮料和其他食品；2）烟草类；3）金融类：贷款、P2P、理财、股票、融资、集资、金融信托；4）房地产：房地产中介。
  verification:
    approval_required: null
    kyb: true
    kyc: null
    text: 如您未通过探迹平台企业认证，探迹有权单方解除服务合同
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tungee
provenance_date: '2026-11-10'
provider_name: Tungee
provider_slug: tungee
slug: tungee-eligibility
source_date: '2026-11-10'
source_filename: tungee-eligibility.yml
source_heading: Eligibility
source_page: https://www.tungee.com/services-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tungee\naid: tungee\nurl: https://www.tungee.com/services-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 产品使用范围仅限于您开展经营范围内的业务。\nrestricted_uses:\n- summary: Prohibited industries for intelligent calling product\n  text: 您不得使用探迹智能呼叫产品用于以下行业类型：1）药品、保健品、替代母乳的婴儿乳制品、饮料和其他食品；2）烟草类；3）金融类：贷款、P2P、理财、股票、融资、集资、金融信托；4）房地产：房地产中介。\nverification:\n  kyc: null\n  kyb: true\n  approval_required: null\n  text: 如您未通过探迹平台企业认证，探迹有权单方解除服务合同\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tungee/eligibility/tungee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Tungee's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales Intelligence
- CRM
- Lead Generation
- AI Agents
- B2B Data
- China
---
