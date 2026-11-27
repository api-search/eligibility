---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - CN
    - TW
    text: 好運器目前只提供中國大陸（深圳集運倉）寄台灣的集運服務，不提供其他國家或地區寄台灣的集運。
  entity_types:
  - text: 指註冊並使用本平台服務的個人或法人實體。
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Legally prohibited goods
    text: 毒品及管制藥物
  - summary: Cash and securities
    text: 現金及有價證券
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 以下物品需事先申報並經本平台核准後方可運送
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HowBridge Logistics
provenance_date: '2026-11-09'
provider_name: HowBridge Logistics
provider_slug: 0523-tw
slug: 0523-tw-eligibility
source_date: '2026-11-09'
source_filename: 0523-tw-eligibility.yml
source_heading: Eligibility
source_page: https://0523.tw/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HowBridge Logistics\naid: 0523-tw\nurl: https://0523.tw/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CN\n  - TW\n  excluded: []\n  text: 好運器目前只提供中國大陸（深圳集運倉）寄台灣的集運服務，不提供其他國家或地區寄台灣的集運。\nentity_types:\n- type: individual\n  text: 指註冊並使用本平台服務的個人或法人實體。\nrestricted_uses:\n- summary: Legally prohibited goods\n  text: 毒品及管制藥物\n- summary: Cash and securities\n  text: 現金及有價證券\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 以下物品需事先申報並經本平台核准後方可運送\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/0523-tw/eligibility/0523-tw-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from HowBridge Logistics's own page on 2026-11-09.
synthetic: false
tags:
- Logistics
- Shipping
- Freight
- Taiwan
- E-Commerce
---
