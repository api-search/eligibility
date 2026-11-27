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
  - summary: Misinformation via AI
    text: AI に誤った情報を広めることを目的とした利用
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: サイトの読み込みは、トップページにタグを置くか、確認用のファイルを置く方法で持ち主の確認が取れた後にだけ行います
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: yomitasu-jp
provenance_date: '2026-11-10'
provider_name: yomitasu-jp
provider_slug: yomitasu-jp
slug: yomitasu-jp-eligibility
source_date: '2026-11-10'
source_filename: yomitasu-jp-eligibility.yml
source_heading: Eligibility
source_page: https://www.yomitasu.jp/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: yomitasu-jp\naid: yomitasu-jp\nurl: https://www.yomitasu.jp/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Misinformation via AI\n  text: AI に誤った情報を広めることを目的とした利用\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: サイトの読み込みは、トップページにタグを置くか、確認用のファイルを置く方法で持ち主の確認が取れた後にだけ行います\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yomitasu-jp/eligibility/yomitasu-jp-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from yomitasu-jp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- Website-Transformation
- Japanese
---
