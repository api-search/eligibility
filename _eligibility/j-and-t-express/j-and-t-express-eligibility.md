---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 本網站內容及服務僅被許可由用戶個人使用而不得被出售或轉讓。
    type: individual
  minimum_age:
    text: 如果您未滿18周歲，請在法定監護人的陪同下閱讀本使用條款。
    value: '18'
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
name: J&T Express
provenance_date: '2026-11-09'
provider_name: J&T Express
provider_slug: j-and-t-express
slug: j-and-t-express-eligibility
source_date: '2026-11-09'
source_filename: j-and-t-express-eligibility.yml
source_heading: Eligibility
source_page: https://www.jtexpress.com/tc/termsOfUse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: J&T Express\naid: j-and-t-express\nurl: https://www.jtexpress.com/tc/termsOfUse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 本網站內容及服務僅被許可由用戶個人使用而不得被出售或轉讓。\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 如果您未滿18周歲，請在法定監護人的陪同下閱讀本使用條款。\n"
source_yaml_url: https://artifacts.apis.io/j-and-t-express/eligibility/j-and-t-express-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from J&T Express's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Logistics
- Delivery
- Shipping
- Express
- Supply Chain
- E-Commerce
- Couriers
- Track and Trace
---
