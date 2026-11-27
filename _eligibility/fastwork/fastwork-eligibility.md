---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ผู้ว่าจ้างที่สมัครใช้บริการแพลตฟอร์มอาจเป็นบุคคลธรรมดาหรือนิติบุคคลก็ได้
    type: individual
  - text: ในกรณีที่เป็นนิติบุคคล ผู้ใช้บริการต้องเป็นผู้แทนนิติบุคคลหรือผู้รับมอบอำนาจจากนิติบุคคลนั้น ๆ เพื่อสมัครใช้บริการแพลตฟอร์ม
    type: business
  minimum_age:
    text: ในกรณีที่เป็นบุคคลธรรมดา ผู้ใช้บริการจะต้องเป็นบุคคลธรรมดาที่มีอายุครบ 15 ปีบริบูรณ์เท่านั้น
    value: '15'
  restricted_uses:
  - summary: Unlawful or immoral use
    text: ท่านรับรองว่าจะไม่ดำเนินการใด ๆ อันเป็นการฝ่าฝืนกฎหมาย ขัดต่อความสงบเรียบร้อย หรือศีลธรรมอันดีของประชาชนผ่านแพลตฟอร์มโดยเด็ดขาด
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: เมื่อมีการตรวจสอบ ผู้ใช้งานต้องแสดงความเป็นเจ้าของบัญชีผู้ใช้งานโดยการแสดงหลักฐานต่าง ๆ อาทิ บัตรประจำตัวประชาชน
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fastwork
provenance_date: '2026-11-09'
provider_name: Fastwork
provider_slug: fastwork
slug: fastwork-eligibility
source_date: '2026-11-09'
source_filename: fastwork-eligibility.yml
source_heading: Eligibility
source_page: https://static.fastwork.co/contents/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fastwork\naid: fastwork\nurl: https://static.fastwork.co/contents/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: ผู้ว่าจ้างที่สมัครใช้บริการแพลตฟอร์มอาจเป็นบุคคลธรรมดาหรือนิติบุคคลก็ได้\n- type: business\n  text: ในกรณีที่เป็นนิติบุคคล ผู้ใช้บริการต้องเป็นผู้แทนนิติบุคคลหรือผู้รับมอบอำนาจจากนิติบุคคลนั้น ๆ เพื่อสมัครใช้บริการแพลตฟอร์ม\nrestricted_uses:\n- summary: Unlawful or immoral use\n  text: ท่านรับรองว่าจะไม่ดำเนินการใด ๆ อันเป็นการฝ่าฝืนกฎหมาย ขัดต่อความสงบเรียบร้อย หรือศีลธรรมอันดีของประชาชนผ่านแพลตฟอร์มโดยเด็ดขาด\n\
  verification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: เมื่อมีการตรวจสอบ ผู้ใช้งานต้องแสดงความเป็นเจ้าของบัญชีผู้ใช้งานโดยการแสดงหลักฐานต่าง ๆ อาทิ บัตรประจำตัวประชาชน\nminimum_age:\n  value: '15'\n  text: ในกรณีที่เป็นบุคคลธรรมดา ผู้ใช้บริการจะต้องเป็นบุคคลธรรมดาที่มีอายุครบ 15 ปีบริบูรณ์เท่านั้น\n"
source_yaml_url: https://artifacts.apis.io/fastwork/eligibility/fastwork-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Fastwork's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Freelance
- Marketplace
- Services
- Gig Economy
- Thailand
- Southeast Asia
- Escrow Payments
---
