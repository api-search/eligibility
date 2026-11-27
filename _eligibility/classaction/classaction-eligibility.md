---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 「一般ユーザー」とは、本サービスを利用する弁護士以外の方をいいます。
    type: individual
  - text: 「登録弁護士」とは、当社が別途定める「enjin(円陣)弁護士向け利用規約」に従い本サービスに登録している弁護士をいいます。
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Anti-social forces or illegal business
    text: 登録希望者が暴力団等反社会的勢力（第１５条にて定義します。）と関係を有し、または公序良俗に反する事業を自ら行っている場合
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 登録希望者が次に掲げる事項に該当し、または該当するおそれがあると当社が判断した場合、当社は当該登録希望者からの申込みを承諾しないことがあります。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ClassAction
provenance_date: '2026-11-09'
provider_name: ClassAction
provider_slug: classaction
slug: classaction-eligibility
source_date: '2026-11-09'
source_filename: classaction-eligibility.yml
source_heading: Eligibility
source_page: https://enjin-classaction.com/terms/user/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClassAction\naid: classaction\nurl: https://enjin-classaction.com/terms/user/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 「一般ユーザー」とは、本サービスを利用する弁護士以外の方をいいます。\n- type: other\n  text: 「登録弁護士」とは、当社が別途定める「enjin(円陣)弁護士向け利用規約」に従い本サービスに登録している弁護士をいいます。\nrestricted_uses:\n- summary: Anti-social forces or illegal business\n  text: 登録希望者が暴力団等反社会的勢力（第１５条にて定義します。）と関係を有し、または公序良俗に反する事業を自ら行っている場合\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 登録希望者が次に掲げる事項に該当し、または該当するおそれがあると当社が判断した場合、当社は当該登録希望者からの申込みを承諾しないことがあります。\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/classaction/eligibility/classaction-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from ClassAction's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Class Action
- Litigation
- Consumer Protection
- Japan
- Legal Services
---
