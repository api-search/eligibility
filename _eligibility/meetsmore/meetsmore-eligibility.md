---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 本プラットフォームを利用する個人、法人または団体等をいい
    type: individual
  - text: 法人または団体等である会員登録希望者について、その法人または団体等のために会員登録手続を行う自然人に、その法人または団体等を代表する正当な権限がない場合
    type: business
  minimum_age:
    text: ユーザーが未成年者、成年被後見人、被保佐人、被補助人である場合は、事前に親権者、成年後見人、保佐人、補助人の包括的な同意を得たうえで本プラットフォームを利用してください。
    value: null
  restricted_uses:
  - summary: Sexual purposes or dating with strangers
    text: 性行為やわいせつな行為を目的とする行為および面識のない個人との出会いや交際を目的とする行為
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: 受注者は、本プラットフォームの利用に先立って、以下に定める確認を行うものとします。 その会員から本サイトを通じて当社に登録される、個人の会員については運転免許証、健康保険証その他当社の別途定める書類、法人または団体等の会員については上記、もしくは履歴事項全部証明書その他当社の別途定める書類の記載が、その会員について当社に登録される情報に合致することの確認
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MeetsMore
provenance_date: '2026-11-10'
provider_name: MeetsMore
provider_slug: meetsmore
slug: meetsmore-eligibility
source_date: '2026-11-10'
source_filename: meetsmore-eligibility.yml
source_heading: Eligibility
source_page: https://meetsmore.com/policies/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MeetsMore\naid: meetsmore\nurl: https://meetsmore.com/policies/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 本プラットフォームを利用する個人、法人または団体等をいい\n- type: business\n  text: 法人または団体等である会員登録希望者について、その法人または団体等のために会員登録手続を行う自然人に、その法人または団体等を代表する正当な権限がない場合\nrestricted_uses:\n- summary: Sexual purposes or dating with strangers\n  text: 性行為やわいせつな行為を目的とする行為および面識のない個人との出会いや交際を目的とする行為\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: 受注者は、本プラットフォームの利用に先立って、以下に定める確認を行うものとします。 その会員から本サイトを通じて当社に登録される、個人の会員については運転免許証、健康保険証その他当社の別途定める書類、法人または団体等の会員については上記、もしくは履歴事項全部証明書その他当社の別途定める書類の記載が、その会員について当社に登録される情報に合致することの確認\n\
  minimum_age:\n  value: null\n  text: ユーザーが未成年者、成年被後見人、被保佐人、被補助人である場合は、事前に親権者、成年後見人、保佐人、補助人の包括的な同意を得たうえで本プラットフォームを利用してください。\n"
source_yaml_url: https://artifacts.apis.io/meetsmore/eligibility/meetsmore-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from MeetsMore's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Local Services
- Home Services
- Japan
- Scheduling
- Calendar
- Booking
- Field Service Management
- Open Source
- Artificial Intelligence
- Agents
---
