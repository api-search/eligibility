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
  - summary: Prohibited conduct
    text: 不正アクセス、過度な負荷をかける行為、法令に違反する行為、第三者の権利を侵害する行為、その他運営者が不適切と判断する行為
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 第2条（アカウント） jp-corporate のプロプランの利用にはアカウント登録が必要です。登録にはメールアドレス、または Google アカウント連携（email アドレスを取得します）を用います。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: plugrail-dev
provenance_date: '2026-11-10'
provider_name: plugrail-dev
provider_slug: plugrail-dev
slug: plugrail-dev-eligibility
source_date: '2026-11-10'
source_filename: plugrail-dev-eligibility.yml
source_heading: Eligibility
source_page: https://plugrail.dev/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: plugrail-dev\naid: plugrail-dev\nurl: https://plugrail.dev/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited conduct\n  text: 不正アクセス、過度な負荷をかける行為、法令に違反する行為、第三者の権利を侵害する行為、その他運営者が不適切と判断する行為\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 第2条（アカウント） jp-corporate のプロプランの利用にはアカウント登録が必要です。登録にはメールアドレス、または Google アカウント連携（email アドレスを取得します）を用います。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/plugrail-dev/eligibility/plugrail-dev-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from plugrail-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- Public Data
- Japan
- AI Integration
---
