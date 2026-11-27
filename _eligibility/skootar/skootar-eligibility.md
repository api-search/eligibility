---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ผู้ใช้งาน หมายถึง ลูกค้า (บุคคลหรือนิติบุคคล)
    type: individual
  - text: ผู้ใช้งาน หมายถึง ลูกค้า (บุคคลหรือนิติบุคคล)
    type: business
  minimum_age:
    text: ผู้ใช้งานรับรองว่าตนเป็นผู้บรรลุนิติภาวะตามกฎหมายไทย
    value: null
  restricted_uses:
  - summary: Prohibited items for delivery
    text: ผู้ใช้งานยืนยันว่าสิ่งของในรายการรับ-ส่งนี้ไม่ใช่สัตว์มีชีวิต สิ่งเสพติด วัตถุลามกอนาจาร วัตถุระเบิด/วัตถุไวไฟ วัตถุมีคมที่ปราศจากสิ่งหุ้มห่อ หรือสิ่งของที่ผิดกฎหมายประเทศไทยอื่นๆ
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
name: Skootar
provenance_date: '2026-11-10'
provider_name: Skootar
provider_slug: skootar
slug: skootar-eligibility
source_date: '2026-11-10'
source_filename: skootar-eligibility.yml
source_heading: Eligibility
source_page: https://www.skootar.com/th/termsandconditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skootar\naid: skootar\nurl: https://www.skootar.com/th/termsandconditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: ผู้ใช้งาน หมายถึง ลูกค้า (บุคคลหรือนิติบุคคล)\n- type: business\n  text: ผู้ใช้งาน หมายถึง ลูกค้า (บุคคลหรือนิติบุคคล)\nrestricted_uses:\n- summary: Prohibited items for delivery\n  text: ผู้ใช้งานยืนยันว่าสิ่งของในรายการรับ-ส่งนี้ไม่ใช่สัตว์มีชีวิต สิ่งเสพติด วัตถุลามกอนาจาร วัตถุระเบิด/วัตถุไวไฟ\n    วัตถุมีคมที่ปราศจากสิ่งหุ้มห่อ หรือสิ่งของที่ผิดกฎหมายประเทศไทยอื่นๆ\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: ผู้ใช้งานรับรองว่าตนเป็นผู้บรรลุนิติภาวะตามกฎหมายไทย\n"
source_yaml_url: https://artifacts.apis.io/skootar/eligibility/skootar-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Skootar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Delivery
- Couriers
- Messenger
- Last Mile Delivery
- Transportation
- Thailand
---
