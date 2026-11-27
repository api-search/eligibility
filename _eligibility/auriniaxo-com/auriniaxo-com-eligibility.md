---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: для будь-якої фізичної особи (надалі - «Гість»)
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Pets only with prior approval
    text: Проживання з тваринами дозволено за умови попереднього узгодження з адміністрацією.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: При заселенні Гість зобов'язаний надати документ, що посвідчує особу (паспорт, Дія).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AURINIA XO HOSTEL
provenance_date: '2026-11-09'
provider_name: AURINIA XO HOSTEL
provider_slug: auriniaxo-com
slug: auriniaxo-com-eligibility
source_date: '2026-11-09'
source_filename: auriniaxo-com-eligibility.yml
source_heading: Eligibility
source_page: https://auriniaxo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AURINIA XO HOSTEL\naid: auriniaxo-com\nurl: https://auriniaxo.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: для будь-якої фізичної особи (надалі - «Гість»)\nrestricted_uses:\n- summary: Pets only with prior approval\n  text: Проживання з тваринами дозволено за умови попереднього узгодження з адміністрацією.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: При заселенні Гість зобов'язаний надати документ, що посвідчує особу (паспорт, Дія).\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/auriniaxo-com/eligibility/auriniaxo-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from AURINIA XO HOSTEL's own page on 2026-11-09.
synthetic: false
tags:
- Hostel
- Accommodation
- Ukraine
- Budget Travel
- Kamianets-Podilskyi
---
