---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ผู้เยาว์สามารถใช้หรือรับบริการฯ ได้ต่อเมื่อได้รับความยินยอมจากบิดามารดาหรือผู้ปกครองตามกฎหมายเท่านั้น
    type: individual
  - text: ในกรณีตัวแทนของผู้ใช้บริการฯ กระทำการแทน และ/หรือ เพื่อวัตถุประสงค์ขององค์กรธุรกิจใด ๆ ให้ถือว่า องค์กรธุรกิจดังกล่าวได้ยอมรับข้อกำหนดและเงื่อนไขนี้ด้วยแล้ว
    type: business
  minimum_age:
    text: ผู้เยาว์สามารถใช้หรือรับบริการฯ ได้ต่อเมื่อได้รับความยินยอมจากบิดามารดาหรือผู้ปกครองตามกฎหมายเท่านั้น
    value: null
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
name: 24 FIX
provenance_date: '2026-11-09'
provider_name: 24 FIX
provider_slug: 24fix
slug: 24fix-eligibility
source_date: '2026-11-09'
source_filename: 24fix-eligibility.yml
source_heading: Eligibility
source_page: https://24x.co.th/th/term-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 24 FIX\naid: 24fix\nurl: https://24x.co.th/th/term-condition\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: ผู้เยาว์สามารถใช้หรือรับบริการฯ ได้ต่อเมื่อได้รับความยินยอมจากบิดามารดาหรือผู้ปกครองตามกฎหมายเท่านั้น\n- type: business\n  text: ในกรณีตัวแทนของผู้ใช้บริการฯ กระทำการแทน และ/หรือ เพื่อวัตถุประสงค์ขององค์กรธุรกิจใด ๆ ให้ถือว่า องค์กรธุรกิจดังกล่าวได้ยอมรับข้อกำหนดและเงื่อนไขนี้ด้วยแล้ว\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: ผู้เยาว์สามารถใช้หรือรับบริการฯ\
  \ ได้ต่อเมื่อได้รับความยินยอมจากบิดามารดาหรือผู้ปกครองตามกฎหมายเท่านั้น\n"
source_yaml_url: https://artifacts.apis.io/24fix/eligibility/24fix-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from 24 FIX's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Home Services
- Property Maintenance
- Facility Management
- Field Service Management
- Marketplace
- Construction
- Renovation
- Consumer Services
- Thailand
- Southeast Asia
---
