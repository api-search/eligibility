---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ผู้ใช้งานจะต้องมีอายุไม่ต่ำกว่า 18 ปีบริบูรณ์
    type: individual
  - text: 2.1.2 ผู้ใช้งานประเภทธุรกิจที่มีสถานะเป็นนิติบุคคล
    type: business
  minimum_age:
    text: ผู้ใช้งานจะต้องมีอายุไม่ต่ำกว่า 18 ปีบริบูรณ์ หากผู้ใช้งานมีอายุไม่ถึง 18 ปี ผู้ใช้งานจะสามารถลงทะเบียนเป็นผู้ใช้งานได้ หากอยู่ภายใต้การดูแลของผู้ปกครองหรือผู้มีอำนาจปกครองเท่านั้น
    value: '18'
  restricted_uses:
  - summary: Alcohol sold B2B only
    text: เฟรชเก็ตจะขายสินค้าดังกล่าวผ่านแพลตฟอร์มของเฟรชเก็ตแก่ผู้ใช้งานประเภทธุรกิจเพื่อวัตถุประสงค์ในการทำการค้าระหว่างธุรกิจทำกับธุรกิจ (B2B) เท่านั้น
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: เฟรชเก็ตไม่ได้มีเงื่อนไขในการแนบเอกสารใด ๆ เพื่อเป็นการยืนยันข้อมูลของผู้ใช้งานที่ให้ไว้แก่เฟรชเก็ตว่าถูกต้องและตรงกับความเป็นจริง
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Freshket
provenance_date: '2026-11-09'
provider_name: Freshket
provider_slug: freshket
slug: freshket-eligibility
source_date: '2026-11-09'
source_filename: freshket-eligibility.yml
source_heading: Eligibility
source_page: https://freshket.co/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Freshket\naid: freshket\nurl: https://freshket.co/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: ผู้ใช้งานจะต้องมีอายุไม่ต่ำกว่า 18 ปีบริบูรณ์\n- type: business\n  text: 2.1.2 ผู้ใช้งานประเภทธุรกิจที่มีสถานะเป็นนิติบุคคล\nrestricted_uses:\n- summary: Alcohol sold B2B only\n  text: เฟรชเก็ตจะขายสินค้าดังกล่าวผ่านแพลตฟอร์มของเฟรชเก็ตแก่ผู้ใช้งานประเภทธุรกิจเพื่อวัตถุประสงค์ในการทำการค้าระหว่างธุรกิจทำกับธุรกิจ\n    (B2B) เท่านั้น\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: เฟรชเก็ตไม่ได้มีเงื่อนไขในการแนบเอกสารใด\
  \ ๆ เพื่อเป็นการยืนยันข้อมูลของผู้ใช้งานที่ให้ไว้แก่เฟรชเก็ตว่าถูกต้องและตรงกับความเป็นจริง\nminimum_age:\n  value: '18'\n  text: ผู้ใช้งานจะต้องมีอายุไม่ต่ำกว่า 18 ปีบริบูรณ์ หากผู้ใช้งานมีอายุไม่ถึง 18 ปี ผู้ใช้งานจะสามารถลงทะเบียนเป็นผู้ใช้งานได้\n    หากอยู่ภายใต้การดูแลของผู้ปกครองหรือผู้มีอำนาจปกครองเท่านั้น\n"
source_yaml_url: https://artifacts.apis.io/freshket/eligibility/freshket-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Freshket's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food and Beverage
- Supply Chain
- Marketplace
- Agriculture
- Logistics
- E-Commerce
- Food Service
- Thailand
---
