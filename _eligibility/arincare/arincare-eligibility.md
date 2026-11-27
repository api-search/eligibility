---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ร้านขายยาไทยที่จดทะเบียนในนามบุคคลธรรมดา
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful, good-faith use only
    text: ท่านมีสิทธิใช้บริการของ arincare.com เพื่อจัดการร้านขายยาของท่านโดยสุจริต และชอบด้วยกฎหมายเท่านั้น
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: arincare.com ขอสงวนสิทธิในการปฏิเสธคำขอใช้บริการใด ๆ ที่ ไม่ผ่านหลักเกณฑ์การประเมินของ arincare.com
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Arincare
provenance_date: '2026-11-09'
provider_name: Arincare
provider_slug: arincare
slug: arincare-eligibility
source_date: '2026-11-09'
source_filename: arincare-eligibility.yml
source_heading: Eligibility
source_page: https://arincare.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arincare\naid: arincare\nurl: https://arincare.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: ร้านขายยาไทยที่จดทะเบียนในนามบุคคลธรรมดา\nrestricted_uses:\n- summary: Lawful, good-faith use only\n  text: ท่านมีสิทธิใช้บริการของ arincare.com เพื่อจัดการร้านขายยาของท่านโดยสุจริต และชอบด้วยกฎหมายเท่านั้น\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: arincare.com ขอสงวนสิทธิในการปฏิเสธคำขอใช้บริการใด ๆ ที่ ไม่ผ่านหลักเกณฑ์การประเมินของ arincare.com\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arincare/eligibility/arincare-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Arincare's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pharmacy
- Digital Health
- Thailand
- Software-as-a-Service
---
