---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraud, identity misuse, illegal activity
    text: 不正決済、なりすまし、盗用カードの使用、チャージバックの不正利用その他の不正行為
  - summary: Anti-social forces
    text: ユーザーは、自らが反社会的勢力に該当しないこと、また反社会的勢力に関与していな いことを表明し保証します。
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
name: Bloomy eSIM
provenance_date: '2026-11-09'
provider_name: Bloomy eSIM
provider_slug: bloomyesim-com
slug: bloomyesim-com-eligibility
source_date: '2026-11-09'
source_filename: bloomyesim-com-eligibility.yml
source_heading: Eligibility
source_page: https://bloomyesim.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomy eSIM\naid: bloomyesim-com\nurl: https://bloomyesim.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fraud, identity misuse, illegal activity\n  text: 不正決済、なりすまし、盗用カードの使用、チャージバックの不正利用その他の不正行為\n- summary: Anti-social forces\n  text: ユーザーは、自らが反社会的勢力に該当しないこと、また反社会的勢力に関与していな いことを表明し保証します。\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bloomyesim-com/eligibility/bloomyesim-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Bloomy eSIM's own page on 2026-11-09.
synthetic: false
tags:
- Company
- eSIM
- Travel
- Telecommunications
- Japan
- Comparison
---
