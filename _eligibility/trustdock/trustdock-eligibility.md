---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ユーザーは本規約に同意して本アプリを自己の通信端末にダウンロードした、本サービス等を利用する全ての方をいいます。
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Antisocial forces prohibited
    text: 反社会的勢力等による本アプリ及び本サービス等の利用を禁止します。
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
name: Trustdock
provenance_date: '2026-11-10'
provider_name: Trustdock
provider_slug: trustdock
slug: trustdock-eligibility
source_date: '2026-11-10'
source_filename: trustdock-eligibility.yml
source_heading: Eligibility
source_page: https://biz.trustdock.io/terms/identity/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trustdock\naid: trustdock\nurl: https://biz.trustdock.io/terms/identity/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: ユーザーは本規約に同意して本アプリを自己の通信端末にダウンロードした、本サービス等を利用する全ての方をいいます。\nrestricted_uses:\n- summary: Antisocial forces prohibited\n  text: 反社会的勢力等による本アプリ及び本サービス等の利用を禁止します。\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trustdock/eligibility/trustdock-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Trustdock's own page on 2026-11-10.
synthetic: false
tags:
- Company
- eKYC
- Identity Verification
- KYC
- Digital Identity
- Authentication
- RegTech
- Fintech
- Japan
---
