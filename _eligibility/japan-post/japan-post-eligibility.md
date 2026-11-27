---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - JP
    text: 会員サービスは、日本国内に限り提供します。
  entity_types:
  - text: 会員 本規約及び「ゆうゆうポイント利用規約」に同意の上、第5条第１項の規定により、会員登録を完了した個人及び法人
    type: individual
  - text: 会員登録を完了した個人及び法人（法人に準ずる機関、組織又は団体を含みます。）
    type: business
  minimum_age:
    text: 会員登録希望者が未成年の場合には、保護者の事前の同意が必要です。
    value: null
  restricted_uses:
  - summary: Prohibited conduct list
    text: 会員は、会員サービスの利用に当たり、次の各号に掲げる行為を行ってはなりません。
  - summary: Points may not be cashed out
    text: (1) 保有するポイントを換金する行為又はそのおそれのある行為をすること
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 会員は、オンラインによる本人確認が必要なサービス又は商品を利用する場合、「オンラインによる本人確認に関する個別規程」に同意の上、当社所定の手続きをしていただきます。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Japan Post
provenance_date: '2026-11-09'
provider_name: Japan Post
provider_slug: japan-post
slug: japan-post-eligibility
source_date: '2026-11-09'
source_filename: japan-post-eligibility.yml
source_heading: Eligibility
source_page: https://mypage.jpid.pf.japanpost.jp/register/terms?_gl=1*1m33ffs*_ga*NDEwODQwNTg3LjE3NDg0OTQxMzM.*_ga_SHH42S0D3Z*czE3Njg0MDI3NTIkbzE2JGcxJHQxNzY4NDAyNzk0JGoxOCRsMCRoMA..
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Japan Post\naid: japan-post\nurl: https://mypage.jpid.pf.japanpost.jp/register/terms?_gl=1*1m33ffs*_ga*NDEwODQwNTg3LjE3NDg0OTQxMzM.*_ga_SHH42S0D3Z*czE3Njg0MDI3NTIkbzE2JGcxJHQxNzY4NDAyNzk0JGoxOCRsMCRoMA..\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - JP\n  excluded: []\n  text: 会員サービスは、日本国内に限り提供します。\nentity_types:\n- type: individual\n  text: 会員 本規約及び「ゆうゆうポイント利用規約」に同意の上、第5条第１項の規定により、会員登録を完了した個人及び法人\n- type: business\n  text: 会員登録を完了した個人及び法人（法人に準ずる機関、組織又は団体を含みます。）\nrestricted_uses:\n- summary: Prohibited conduct list\n  text: 会員は、会員サービスの利用に当たり、次の各号に掲げる行為を行ってはなりません。\n- summary: Points may not be cashed\
  \ out\n  text: (1) 保有するポイントを換金する行為又はそのおそれのある行為をすること\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 会員は、オンラインによる本人確認が必要なサービス又は商品を利用する場合、「オンラインによる本人確認に関する個別規程」に同意の上、当社所定の手続きをしていただきます。\nminimum_age:\n  value: null\n  text: 会員登録希望者が未成年の場合には、保護者の事前の同意が必要です。\n"
source_yaml_url: https://artifacts.apis.io/japan-post/eligibility/japan-post-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Japan Post's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Postal
- Logistics
- Finance
- e-Services
---
