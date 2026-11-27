---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 具有法律规定的完全民事权利能力和民事行为能力、能够独立承担民事责任的自然人、法人或其他组织
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 你应按照页面提示提供真实、有效、合法、完整的信息
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aiguang
provenance_date: '2026-11-09'
provider_name: Aiguang
provider_slug: aiguang
slug: aiguang-eligibility
source_date: '2026-11-09'
source_filename: aiguang-eligibility.yml
source_heading: Eligibility
source_page: https://bbs.guang.com/d/964
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aiguang\naid: aiguang\nurl: https://bbs.guang.com/d/964\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 具有法律规定的完全民事权利能力和民事行为能力、能够独立承担民事责任的自然人、法人或其他组织\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 你应按照页面提示提供真实、有效、合法、完整的信息\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aiguang/eligibility/aiguang-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Aiguang's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Live Commerce
- Live Streaming
- Social Commerce
- Retail
- Video
- WeChat
- China
- Marketplace
---
