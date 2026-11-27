---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 「ユー ザー」 と は 本 サー ビ ス の 利 用 の た め に 必 要 な 手 続 き を 行 っ た 個 人 又 は 法 人 の こ と を い い ま す。
    type: individual
  - text: 「ユー ザー」 と は 本 サー ビ ス の 利 用 の た め に 必 要 な 手 続 き を 行 っ た 個 人 又 は 法 人 の こ と を い い ま す。
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Anti-social forces excluded
    text: ユー ザー は、 現 在 か つ 将 来 に わ た り、 反 社 会 的 勢 力 に 該 当 し な い こ と
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 当 社 は、 前 項 の ユー ザー 登 録 希 望 者 の 申 請 を 受 付 け
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zehitomo
provenance_date: '2026-11-10'
provider_name: Zehitomo
provider_slug: zehitomo
slug: zehitomo-eligibility
source_date: '2026-11-10'
source_filename: zehitomo-eligibility.yml
source_heading: Eligibility
source_page: https://www.zehitomo.com/static/pdf/terms-of-use-clients-20250303.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zehitomo\naid: zehitomo\nurl: https://www.zehitomo.com/static/pdf/terms-of-use-clients-20250303.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 「ユー ザー」 と は 本 サー ビ ス の 利 用 の た め に 必 要 な 手 続 き を 行 っ た 個 人 又 は 法 人 の こ と を い い ま す。\n- type: business\n  text: 「ユー ザー」 と は 本 サー ビ ス の 利 用 の た め に 必 要 な 手 続 き を 行 っ た 個 人 又 は 法 人 の こ と を い い ま す。\nrestricted_uses:\n- summary: Anti-social forces excluded\n  text: ユー ザー は、 現 在 か つ 将 来 に わ た り、 反 社 会 的 勢 力 に 該 当 し な い こ と\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n\
  \  text: 当 社 は、 前 項 の ユー ザー 登 録 希 望 者 の 申 請 を 受 付 け\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zehitomo/eligibility/zehitomo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Zehitomo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Local Services
- Marketplace
- Japan
- Professional Services
- Matching
- Gig Economy
- Consumer
---
