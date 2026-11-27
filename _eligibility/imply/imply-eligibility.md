---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - IR
    - SY
    - CU
    - SD
    - KP
    served: []
    text: any country to which the United States has prohibited export transactions (including, without limitation, Iran, Syria, Cuba, Sudan, North Korea, and the Ukrainian regions of Crimea, Luhansk, and Donetsk)
  entity_types:
  - text: as an employee, contractor, or agent of a corporation, partnership or similar entity
    type: business
  - text: the entity or person placing an order for or accessing
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No weapons development
    text: any prohibited development, design, manufacture or production of missiles or nuclear, chemical or biological weapons
  - summary: Evaluation licenses not for production
    text: Customer may not use an Evaluation License for any production, professional or for-profit purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: must register and set up an authorized account to use the SaaS
excluded_countries:
- IR
- SY
- CU
- SD
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Imply
provenance_date: '2026-11-09'
provider_name: Imply
provider_slug: imply
slug: imply-eligibility
source_date: '2026-11-09'
source_filename: imply-eligibility.yml
source_heading: Eligibility
source_page: https://imply.io/imply-software-license-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Imply\naid: imply\nurl: https://imply.io/imply-software-license-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - SY\n  - CU\n  - SD\n  - KP\n  text: any country to which the United States has prohibited export transactions (including, without limitation,\n    Iran, Syria, Cuba, Sudan, North Korea, and the Ukrainian regions of Crimea, Luhansk, and Donetsk)\nentity_types:\n- type: business\n  text: as an employee, contractor, or agent of a corporation, partnership or similar entity\n- type: individual\n  text: the entity or person placing an order for or accessing\nrestricted_uses:\n\
  - summary: No weapons development\n  text: any prohibited development, design, manufacture or production of missiles or nuclear, chemical or biological\n    weapons\n- summary: Evaluation licenses not for production\n  text: Customer may not use an Evaluation License for any production, professional or for-profit purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: must register and set up an authorized account to use the SaaS\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/imply/eligibility/imply-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Imply's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Real-Time Analytics
- Database
- Apache Druid
- Data
- Database-as-a-Service
- Streaming
---
