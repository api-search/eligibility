---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 具备民事行为能力的个人、法人或其他组织
    type: individual
  - text: 具备民事行为能力的个人、法人或其他组织
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or prohibited content
    text: 您不得从事任何包括但不限于以下的违反法规的行为
  - summary: Advertising and spam
    text: 发布、传送、传播广告信息及垃圾信息；
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 开发者，指经有效申请并经过上海喜马拉雅科技有限公司同意，将喜马拉雅开放平台服务接入其开发的各种应用
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ximalaya
provenance_date: '2026-11-10'
provider_name: Ximalaya
provider_slug: ximalaya
slug: ximalaya-eligibility
source_date: '2026-11-10'
source_filename: ximalaya-eligibility.yml
source_heading: Eligibility
source_page: https://open.ximalaya.com/doc/detailQuickStart?categoryId=18&articleId=35
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ximalaya\naid: ximalaya\nurl: https://open.ximalaya.com/doc/detailQuickStart?categoryId=18&articleId=35\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 具备民事行为能力的个人、法人或其他组织\n- type: business\n  text: 具备民事行为能力的个人、法人或其他组织\nrestricted_uses:\n- summary: Illegal or prohibited content\n  text: 您不得从事任何包括但不限于以下的违反法规的行为\n- summary: Advertising and spam\n  text: 发布、传送、传播广告信息及垃圾信息；\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 开发者，指经有效申请并经过上海喜马拉雅科技有限公司同意，将喜马拉雅开放平台服务接入其开发的各种应用\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/ximalaya/eligibility/ximalaya-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Ximalaya's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Audio
- Podcasts
- Audiobooks
- Media
- Content Distribution
- Streaming
- China
- Entertainment
---
