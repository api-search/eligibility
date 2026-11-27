---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - VN
    text: Leflair chỉ giao hàng tận nơi đến các địa điểm trong phạm vi Việt Nam
  entity_types:
  - text: Dịch vụ của chúng tôi chỉ được cung cấp cho hội viên và hãy chắc chắn rằng bạn đủ 18 tuổi trở lên để tham gia truy cập.
    type: individual
  minimum_age:
    text: hãy chắc chắn rằng bạn đủ 18 tuổi trở lên để tham gia truy cập
    value: '18'
  restricted_uses:
  - summary: Spam and unsolicited content
    text: bất kỳ chuỗi thư điện tử, bán hàng đa cấp, tin rác, các cuộc thi, hay tài liệu quảng cáo
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
name: Leflair
provenance_date: '2026-11-09'
provider_name: Leflair
provider_slug: leflair
slug: leflair-eligibility
source_date: '2026-11-09'
source_filename: leflair-eligibility.yml
source_heading: Eligibility
source_page: https://leflair.com/pages/cac-dieu-khoan-su-dung
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Leflair\naid: leflair\nurl: https://leflair.com/pages/cac-dieu-khoan-su-dung\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - VN\n  excluded: []\n  text: Leflair chỉ giao hàng tận nơi đến các địa điểm trong phạm vi Việt Nam\nentity_types:\n- type: individual\n  text: Dịch vụ của chúng tôi chỉ được cung cấp cho hội viên và hãy chắc chắn rằng bạn đủ 18 tuổi trở lên để tham\n    gia truy cập.\nrestricted_uses:\n- summary: Spam and unsolicited content\n  text: bất kỳ chuỗi thư điện tử, bán hàng đa cấp, tin rác, các cuộc thi, hay tài liệu quảng cáo\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: hãy chắc chắn rằng bạn đủ 18 tuổi trở lên để tham gia truy cập\n"
source_yaml_url: https://artifacts.apis.io/leflair/eligibility/leflair-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Leflair's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Vietnam
- Fashion
- Beauty
- Flash Sales
- Consumer
---
