---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 本公司僅提供本服務予自然人及法人使用者。使用者清楚知悉自身應為年滿十八歲且具備完全行為能力之自然人，或合法登記之法人或團體
    type: individual
  - text: 合法登記之法人或團體
    type: business
  minimum_age:
    text: 年滿十八歲且具備完全行為能力之自然人
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing use
    text: 不得將本公司之產品或服務用於非法之目的包括但不限於侵害他人權利、財產權、隱私權、智慧財產權；違反刑事或行政法令或幫助他人犯罪等
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 對於註冊成為會員之申請，本公司保留是否同意其註冊之權利。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OEN
provenance_date: '2026-11-10'
provider_name: OEN
provider_slug: oen
slug: oen-eligibility
source_date: '2026-11-10'
source_filename: oen-eligibility.yml
source_heading: Eligibility
source_page: https://oen.tw/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OEN\naid: oen\nurl: https://oen.tw/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 本公司僅提供本服務予自然人及法人使用者。使用者清楚知悉自身應為年滿十八歲且具備完全行為能力之自然人，或合法登記之法人或團體\n- type: business\n  text: 合法登記之法人或團體\nrestricted_uses:\n- summary: Unlawful or infringing use\n  text: 不得將本公司之產品或服務用於非法之目的包括但不限於侵害他人權利、財產權、隱私權、智慧財產權；違反刑事或行政法令或幫助他人犯罪等\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 對於註冊成為會員之申請，本公司保留是否同意其註冊之權利。\nminimum_age:\n  value: '18'\n  text: 年滿十八歲且具備完全行為能力之自然人\n"
source_yaml_url: https://artifacts.apis.io/oen/eligibility/oen-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from OEN's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Fintech
- CRM
- Invoicing
- Taiwan
- Non-Profit
---
