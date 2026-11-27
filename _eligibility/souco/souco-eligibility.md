---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 本システムの利用者として登録できるのは、原則として法人に限られ、個人は本システムの利用者として登録することはできないものとする。
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No anti-social-forces involvement
    text: 当社及び登録ユーザーは、現在及び将来において、第1号に掲げる者（以下「反社会的勢力」という。）に一切該当せず
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 当社が登録を認める場合には、その旨を登録希望者に通知するものとする。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Souco
provenance_date: '2026-11-10'
provider_name: Souco
provider_slug: souco
slug: souco-eligibility
source_date: '2026-11-10'
source_filename: souco-eligibility.yml
source_heading: Eligibility
source_page: https://www.souco.space/terms_of_souco_system/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Souco\naid: souco\nurl: https://www.souco.space/terms_of_souco_system/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 本システムの利用者として登録できるのは、原則として法人に限られ、個人は本システムの利用者として登録することはできないものとする。\nrestricted_uses:\n- summary: No anti-social-forces involvement\n  text: 当社及び登録ユーザーは、現在及び将来において、第1号に掲げる者（以下「反社会的勢力」という。）に一切該当せず\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 当社が登録を認める場合には、その旨を登録希望者に通知するものとする。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/souco/eligibility/souco-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Souco's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Warehousing
- Supply Chain
- Marketplace
- Storage
- Transportation
- Japan
---
