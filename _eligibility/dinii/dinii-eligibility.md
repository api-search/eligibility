---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 未成年者、成年被後見人、被保佐人または被補助人のいずれかであり、法定代理人、後見人、保佐人または補助人の同意等を得ていなかった場合
    value: null
  restricted_uses:
  - summary: Anti-social forces excluded
    text: 反社会的勢力等(暴力団、暴力団員、右翼団体、反社会的勢力、その他これに準ずる者を意味します。以下同じ。)である、または資金提供その他を通じて反社会的勢力等の維持、運営もしくは経営に協力もしくは関与する等反社会的勢力等との何らかの交流もしくは関与を行っていると当社が判断した場合
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 当社は、当社の基準に従って、第1項にもとづいて登録申請を行った登録希望者(以下「登録申請者」といいます。)の登録の可否を判断し、当社が登録を認める場合にはその旨を登録申請者に通知します。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dinii
provenance_date: '2026-11-09'
provider_name: Dinii
provider_slug: dinii
slug: dinii-eligibility
source_date: '2026-11-09'
source_filename: dinii-eligibility.yml
source_heading: Eligibility
source_page: https://info.dinii.jp/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dinii\naid: dinii\nurl: https://info.dinii.jp/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Anti-social forces excluded\n  text: 反社会的勢力等(暴力団、暴力団員、右翼団体、反社会的勢力、その他これに準ずる者を意味します。以下同じ。)である、または資金提供その他を通じて反社会的勢力等の維持、運営もしくは経営に協力もしくは関与する等反社会的勢力等との何らかの交流もしくは関与を行っていると当社が判断した場合\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 当社は、当社の基準に従って、第1項にもとづいて登録申請を行った登録希望者(以下「登録申請者」といいます。)の登録の可否を判断し、当社が登録を認める場合にはその旨を登録申請者に通知します。\nminimum_age:\n  value: null\n  text: 未成年者、成年被後見人、被保佐人または被補助人のいずれかであり、法定代理人、後見人、保佐人または補助人の同意等を得ていなかった場合\n"
source_yaml_url: https://artifacts.apis.io/dinii/eligibility/dinii-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Dinii's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Restaurant
- Point-of-Sale
- Mobile Ordering
- Food Service
- Software-as-a-Service
- CRM
- Japan
---
