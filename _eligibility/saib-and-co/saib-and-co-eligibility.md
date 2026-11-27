---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 만14세 미만의 아동으로서 부모 등 법정대리인의 동의를 얻지 아니한 경우
    value: '14'
  restricted_uses:
  - summary: Improper or profit-seeking purpose
    text: 부정한 용도 또는 영리를 추구할 목적으로 본 서비스를 이용하고자 하는 경우
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: “몰”이 이러한 신청에 대하여 승인함으로써 체결됩니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SAIB & Co.
provenance_date: '2026-11-10'
provider_name: SAIB & Co.
provider_slug: saib-and-co
slug: saib-and-co-eligibility
source_date: '2026-11-10'
source_filename: saib-and-co-eligibility.yml
source_heading: Eligibility
source_page: https://saibnco.com/member/agreement.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SAIB & Co.\naid: saib-and-co\nurl: https://saibnco.com/member/agreement.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Improper or profit-seeking purpose\n  text: 부정한 용도 또는 영리를 추구할 목적으로 본 서비스를 이용하고자 하는 경우\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: “몰”이 이러한 신청에 대하여 승인함으로써 체결됩니다.\nminimum_age:\n  value: '14'\n  text: 만14세 미만의 아동으로서 부모 등 법정대리인의 동의를 얻지 아니한 경우\n"
source_yaml_url: https://artifacts.apis.io/saib-and-co/eligibility/saib-and-co-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from SAIB & Co.'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cosmetics
- Consumer Goods
- E-Commerce
- Wellness
- Retail
- Cafe24
- OAuth
- Authentication
---
