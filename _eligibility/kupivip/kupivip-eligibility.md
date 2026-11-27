---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - RU
    text: Быстрая доставка по РФ
  entity_types:
  - text: 'Физические лица: Ф. И. О. Покупателя; контактный телефон; адрес электронной почты'
    type: individual
  - text: 'Юридические лица: полное наименование; Ф. И. О. представителя, уполномоченного на получение продукции'
    type: business
  minimum_age:
    text: Покупатель дает гарантию, что на момент приобретения продукции имеет полную дееспособность и необходимые полномочия для покупки продукции.
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
name: KupiVIP
provenance_date: '2026-11-09'
provider_name: KupiVIP
provider_slug: kupivip
slug: kupivip-eligibility
source_date: '2026-11-09'
source_filename: kupivip-eligibility.yml
source_heading: Eligibility
source_page: https://kupivip.ru/usloviya-prodazhi/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KupiVIP\naid: kupivip\nurl: https://kupivip.ru/usloviya-prodazhi/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - RU\n  excluded: []\n  text: Быстрая доставка по РФ\nentity_types:\n- type: individual\n  text: 'Физические лица: Ф. И. О. Покупателя; контактный телефон; адрес электронной почты'\n- type: business\n  text: 'Юридические лица: полное наименование; Ф. И. О. представителя, уполномоченного на получение продукции'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Покупатель дает гарантию, что на момент приобретения\
  \ продукции имеет полную дееспособность и необходимые\n    полномочия для покупки продукции.\n"
source_yaml_url: https://artifacts.apis.io/kupivip/eligibility/kupivip-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from KupiVIP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- E-Commerce
- Retail
- Fashion
- Apparel
- Luxury Goods
- Online Shopping
- Russia
---
