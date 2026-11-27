---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - RU
    text: Доставка по России — транспортными компаниями до двери или до пункта выдачи.
  entity_types:
  - text: Покупатель — юридическое лицо, индивидуальный предприниматель или физическое лицо, оформившее заказ на Сайте
    type: business
  - text: 'Для физических лиц: после оформления заказа менеджер связывается с покупателем'
    type: individual
  minimum_age:
    text: null
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
name: 5 дюймов
provenance_date: '2026-11-09'
provider_name: 5 дюймов
provider_slug: 5dyuymov-ru
slug: 5dyuymov-ru-eligibility
source_date: '2026-11-09'
source_filename: 5dyuymov-ru-eligibility.yml
source_heading: Eligibility
source_page: https://5dyuymov.ru/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 5 дюймов\naid: 5dyuymov-ru\nurl: https://5dyuymov.ru/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - RU\n  excluded: []\n  text: Доставка по России — транспортными компаниями до двери или до пункта выдачи.\nentity_types:\n- type: business\n  text: Покупатель — юридическое лицо, индивидуальный предприниматель или физическое лицо, оформившее заказ на Сайте\n- type: individual\n  text: 'Для физических лиц: после оформления заказа менеджер связывается с покупателем'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/5dyuymov-ru/eligibility/5dyuymov-ru-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 3 quoted statements, read from 5 дюймов's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pipelines
- Valves
- Pumps
- Heating
---
