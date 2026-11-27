---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 若您未满18周岁、且不具备完全行为能力，在使用中医在线时您的行为应当与您年龄、智力相符否则，在使用中医在线服务前，必须事先取得您的监护人的同意。
    value: '18'
  restricted_uses:
  - summary: Harmful or illegal content
    text: 利用中医在线网络服务发表、传送、传播、储存危害国家安全、国家统一、社会稳定的内容
  - summary: Computer network attacks
    text: 进行任何危害计算机网络安全的行为
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
name: Chinese Medicine Online
provenance_date: '2026-11-09'
provider_name: Chinese Medicine Online
provider_slug: chinese-medicine-online
slug: chinese-medicine-online-eligibility
source_date: '2026-11-09'
source_filename: chinese-medicine-online-eligibility.yml
source_heading: Eligibility
source_page: http://www.tcmmooc.com/page/useragreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chinese Medicine Online\naid: chinese-medicine-online\nurl: http://www.tcmmooc.com/page/useragreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harmful or illegal content\n  text: 利用中医在线网络服务发表、传送、传播、储存危害国家安全、国家统一、社会稳定的内容\n- summary: Computer network attacks\n  text: 进行任何危害计算机网络安全的行为\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 若您未满18周岁、且不具备完全行为能力，在使用中医在线时您的行为应当与您年龄、智力相符否则，在使用中医在线服务前，必须事先取得您的监护人的同意。\n"
source_yaml_url: https://artifacts.apis.io/chinese-medicine-online/eligibility/chinese-medicine-online-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Chinese Medicine Online's own page on 2026-11-09.
synthetic: false
tags:
- Traditional Chinese Medicine
- Healthcare
- Medical Education
- Continuing Medical Education
- E-Learning
- Artificial Intelligence
- China
- Software-as-a-Service
- Company
---
