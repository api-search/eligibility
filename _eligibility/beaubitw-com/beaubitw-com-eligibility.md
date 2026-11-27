---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - TW
    text: 適用地區：中華民國（臺灣）
  entity_types:
  - text: 使用本平台須年滿 18 歲，或於法定代理人監護下使用。
    type: individual
  minimum_age:
    text: 使用本平台須年滿 18 歲，或於法定代理人監護下使用。
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: 客戶須以 LINE 帳號完成身份驗證，並提供真實姓名及有效手機號碼。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Beaubi 行動美研
provenance_date: '2026-11-09'
provider_name: Beaubi 行動美研
provider_slug: beaubitw-com
slug: beaubitw-com-eligibility
source_date: '2026-11-09'
source_filename: beaubitw-com-eligibility.yml
source_heading: Eligibility
source_page: https://beaubitw.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beaubi 行動美研\naid: beaubitw-com\nurl: https://beaubitw.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - TW\n  excluded: []\n  text: 適用地區：中華民國（臺灣）\nentity_types:\n- type: individual\n  text: 使用本平台須年滿 18 歲，或於法定代理人監護下使用。\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: 客戶須以 LINE 帳號完成身份驗證，並提供真實姓名及有效手機號碼。\nminimum_age:\n  value: '18'\n  text: 使用本平台須年滿 18 歲，或於法定代理人監護下使用。\n"
source_yaml_url: https://artifacts.apis.io/beaubitw-com/eligibility/beaubitw-com-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Beaubi 行動美研's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
