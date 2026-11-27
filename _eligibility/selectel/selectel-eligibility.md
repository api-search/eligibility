---
api_specs:
- filename: selectel-openapi-generated.yml
  format: yaml
  label: Selectel API
  slug: selectel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/selectel/openapi/_ae-authored/selectel-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use where service failure could threaten security or health
    text: Заказчик не должен пользоваться Услугами в любой ситуации, когда оказание Услуг может создать угрозу безопасности и обороноспособности государства, здоровью и безопасности людей
  - summary: Storing RF citizens' personal data abroad
    text: не размещать персональные данные граждан РФ с использованием баз данных, находящихся за пределами территории РФ
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
name: Selectel
provenance_date: '2026-11-10'
provider_name: Selectel
provider_slug: selectel
slug: selectel-eligibility
source_date: '2026-11-10'
source_filename: selectel-eligibility.yml
source_heading: Eligibility
source_page: https://files.selectel.ru/docs/ru/terms-of-use-for-services.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Selectel\naid: selectel\nurl: https://files.selectel.ru/docs/ru/terms-of-use-for-services.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use where service failure could threaten security or health\n  text: Заказчик не должен пользоваться Услугами в любой ситуации, когда оказание Услуг может создать угрозу безопасности\n    и обороноспособности государства, здоровью и безопасности людей\n- summary: Storing RF citizens' personal data abroad\n  text: не размещать персональные данные граждан РФ с использованием баз данных, находящихся\
  \ за пределами территории\n    РФ\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/selectel/eligibility/selectel-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Selectel's own page on 2026-11-10.
synthetic: false
tags:
- Cloud
- Infrastructure
- VPS
- Storage
- Kubernetes
---
