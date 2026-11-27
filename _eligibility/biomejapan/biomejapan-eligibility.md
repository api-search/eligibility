---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 本サービスの利用者としての登録がなされた個人、法人又は任意の団体
    type: individual
  - text: 本サービスの利用者としての登録がなされた個人、法人又は任意の団体
    type: business
  - text: 任意の団体
    type: other
  minimum_age:
    text: 未成年者、成年被後見人、被保佐人又は被補助人のいずれかであり、法定代理人、後見人､保佐人又は補助人の同意等を得ていなかった場合
    value: null
  restricted_uses:
  - summary: Anti-social forces / illegal dealers barred from registering
    text: 反社会的勢力等（暴力団、暴力団員、右翼団体、反社会的勢力その他これに準ずる者を意味します。）である
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 当社は、当社の基準に則って、登録の可否を判断し、当社が登録を認める場合に、利用希望者の本サービスへの登録が完了したものとします。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Biomejapan
provenance_date: '2026-11-09'
provider_name: Biomejapan
provider_slug: biomejapan
slug: biomejapan-eligibility
source_date: '2026-11-09'
source_filename: biomejapan-eligibility.yml
source_heading: Eligibility
source_page: https://biome.co.jp/appmessage/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Biomejapan\naid: biomejapan\nurl: https://biome.co.jp/appmessage/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 本サービスの利用者としての登録がなされた個人、法人又は任意の団体\n- type: business\n  text: 本サービスの利用者としての登録がなされた個人、法人又は任意の団体\n- type: other\n  text: 任意の団体\nrestricted_uses:\n- summary: Anti-social forces / illegal dealers barred from registering\n  text: 反社会的勢力等（暴力団、暴力団員、右翼団体、反社会的勢力その他これに準ずる者を意味します。）である\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 当社は、当社の基準に則って、登録の可否を判断し、当社が登録を認める場合に、利用希望者の本サービスへの登録が完了したものとします。\n\
  minimum_age:\n  value: null\n  text: 未成年者、成年被後見人、被保佐人又は被補助人のいずれかであり、法定代理人、後見人､保佐人又は補助人の同意等を得ていなかった場合\n"
source_yaml_url: https://artifacts.apis.io/biomejapan/eligibility/biomejapan-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Biomejapan's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Ecology
- Sustainability
- Japan
---
