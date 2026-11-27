---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “用户”指所有直接或间接获取和使用丁香园及相关服务的使用者，包括自然人、法人和其他组织等。
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content categories
    text: 用户不得利用丁香园服务制作、上载、复制、发布、传播或者转载如下内容
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
name: DXY
provenance_date: '2026-11-09'
provider_name: DXY
provider_slug: dxy
slug: dxy-eligibility
source_date: '2026-11-09'
source_filename: dxy-eligibility.yml
source_heading: Eligibility
source_page: https://3g.dxy.cn/newh5/view/rule/userAgreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DXY\naid: dxy\nurl: https://3g.dxy.cn/newh5/view/rule/userAgreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “用户”指所有直接或间接获取和使用丁香园及相关服务的使用者，包括自然人、法人和其他组织等。\nrestricted_uses:\n- summary: Prohibited content categories\n  text: 用户不得利用丁香园服务制作、上载、复制、发布、传播或者转载如下内容\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dxy/eligibility/dxy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from DXY's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Healthcare
- Medical
- Pharmaceuticals
- Life Sciences
- Data
- China
- Drug Data
- Open Platform
---
