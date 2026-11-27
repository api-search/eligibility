---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 纷享销客服务仅面向企业组织（含其创建的最终用户）提供数字化在线移动办公、沟通与协同服务
    type: business
  minimum_age:
    text: 您应当是具备完全民事权利能力和与所从事的民事行为相适应的行为能力的自然人
    value: null
  restricted_uses:
  - summary: Illegal activities
    text: 您承诺不会利用本服务进行任何违法或不当的活动
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
name: Fxiaoke
provenance_date: '2026-11-09'
provider_name: Fxiaoke
provider_slug: fxiaoke
slug: fxiaoke-eligibility
source_date: '2026-11-09'
source_filename: fxiaoke-eligibility.yml
source_heading: Eligibility
source_page: https://www.fxiaoke.com/protocols/index.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fxiaoke\naid: fxiaoke\nurl: https://www.fxiaoke.com/protocols/index.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 纷享销客服务仅面向企业组织（含其创建的最终用户）提供数字化在线移动办公、沟通与协同服务\nrestricted_uses:\n- summary: Illegal activities\n  text: 您承诺不会利用本服务进行任何违法或不当的活动\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: 您应当是具备完全民事权利能力和与所从事的民事行为相适应的行为能力的自然人\n"
source_yaml_url: https://artifacts.apis.io/fxiaoke/eligibility/fxiaoke-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fxiaoke's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- CRM
- Sales
- Marketing
- Customer Service
- Software-as-a-Service
- China
- Platform-as-a-Service
---
