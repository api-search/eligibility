---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 「登録会員」とは、第5条に基づき本サービスの利用者としての登録がなされた法人・機関・団体・事業主を意味します。
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Registration refused for anti-social forces or false information
    text: 当社は、前項に基づき登録を申請した者が、以下の各号のいずれかの事由に該当する場合は、登録を拒否することがあります。
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 当社は、前項その他当社の基準に従って、登録希望者の登録の可否を判断し、当社が登録を認める場合にはその旨を登録希望者に通知します。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Stockmark
provenance_date: '2026-11-10'
provider_name: Stockmark
provider_slug: stockmark-co-jp
slug: stockmark-co-jp-eligibility
source_date: '2026-11-10'
source_filename: stockmark-co-jp-eligibility.yml
source_heading: Eligibility
source_page: https://stockmark.co.jp/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stockmark\naid: stockmark-co-jp\nurl: https://stockmark.co.jp/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 「登録会員」とは、第5条に基づき本サービスの利用者としての登録がなされた法人・機関・団体・事業主を意味します。\nrestricted_uses:\n- summary: Registration refused for anti-social forces or false information\n  text: 当社は、前項に基づき登録を申請した者が、以下の各号のいずれかの事由に該当する場合は、登録を拒否することがあります。\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 当社は、前項その他当社の基準に従って、登録希望者の登録の可否を判断し、当社が登録を認める場合にはその旨を登録希望者に通知します。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stockmark-co-jp/eligibility/stockmark-co-jp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Stockmark's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Software-as-a-Service
- Platform-as-a-Service
- Knowledge Management
- Japan
---
