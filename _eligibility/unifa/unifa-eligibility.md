---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - JP
    text: 本サービスによる提供物件の配送先は、日本国内に限るものとします。
  entity_types:
  - text: 「事業者」とは、保育施設の運営事業者を意味します。
    type: business
  - text: 「利用者」とは、第３条（登録）に基づいて本サービスの利用者としての登録がなされた個人又は法人を意味し
    type: individual
  minimum_age:
    text: 未成年者、成年被後見人、被保佐人又は被補助人のいずれかであり、法定代理人、後見人、保佐人又は補助人の同意等を得ていなかった場合
    value: null
  restricted_uses:
  - summary: Input of sensitive information into すくすくログ
    text: すくすくログの利用にあたり、音声又はテキストのいずれの形式かを問わず、以下に該当する情報を投稿、送信、入力又は録音する行為
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 当社は、当社の基準に従って、第１項に基づいて登録申請を行った登録希望者（以下、「登録申請者」といいます）の登録の可否を判断し
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Unifa
provenance_date: '2026-11-10'
provider_name: Unifa
provider_slug: unifa
slug: unifa-eligibility
source_date: '2026-11-10'
source_filename: unifa-eligibility.yml
source_heading: Eligibility
source_page: https://lookmee.jp/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unifa\naid: unifa\nurl: https://lookmee.jp/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - JP\n  excluded: []\n  text: 本サービスによる提供物件の配送先は、日本国内に限るものとします。\nentity_types:\n- type: business\n  text: 「事業者」とは、保育施設の運営事業者を意味します。\n- type: individual\n  text: 「利用者」とは、第３条（登録）に基づいて本サービスの利用者としての登録がなされた個人又は法人を意味し\nrestricted_uses:\n- summary: Input of sensitive information into すくすくログ\n  text: すくすくログの利用にあたり、音声又はテキストのいずれの形式かを問わず、以下に該当する情報を投稿、送信、入力又は録音する行為\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 当社は、当社の基準に従って、第１項に基づいて登録申請を行った登録希望者（以下、「登録申請者」といいます）の登録の可否を判断し\nminimum_age:\n  value:\
  \ null\n  text: 未成年者、成年被後見人、被保佐人又は被補助人のいずれかであり、法定代理人、後見人、保佐人又は補助人の同意等を得ていなかった場合\n"
source_yaml_url: https://artifacts.apis.io/unifa/eligibility/unifa-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Unifa's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Childcare
- Education Technology
- Early Childhood Education
- Software-as-a-Service
- Japan
- IoT
- Artificial Intelligence
- Workforce Management
- Photo Sharing
---
