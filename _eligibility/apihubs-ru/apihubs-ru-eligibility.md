---
api_specs:
- filename: apihubs-ru-default-api-openapi.yml
  format: yaml
  label: apihubs-ru Агент API
  slug: apihubs-ru-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apihubs-ru/openapi/apihubs-ru-default-api-openapi.yml
- filename: apihubs-ru-llm-api-openapi.yml
  format: yaml
  label: apihubs-ru LLM API
  slug: apihubs-ru-llm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apihubs-ru/openapi/apihubs-ru-llm-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - RU
    text: Услуга доступна на территории Российской Федерации и в иных странах, где ее получение не запрещено применимым законодательством.
  entity_types:
  - text: Пользователем может быть дееспособное физическое лицо, достигшее 18 лет
    type: individual
  - text: индивидуальный предприниматель, плательщик налога на профессиональный доход или юридическое лицо
    type: business
  minimum_age:
    text: дееспособное физическое лицо, достигшее 18 лет
    value: '18'
  restricted_uses:
  - summary: Prohibited content
    text: 'Запрещается направлять в Заданиях и создавать с помощью Сервиса материалы: содержащие сексуальную эксплуатацию несовершеннолетних либо изображающие несовершеннолетних в сексуализированном контексте'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Для использования Сервиса Пользователь создает аккаунт, указывая адрес электронной почты и пароль
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: apihubs-ru
provenance_date: '2026-11-09'
provider_name: apihubs-ru
provider_slug: apihubs-ru
slug: apihubs-ru-eligibility
source_date: '2026-11-09'
source_filename: apihubs-ru-eligibility.yml
source_heading: Eligibility
source_page: https://apihubs.ru/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: apihubs-ru\naid: apihubs-ru\nurl: https://apihubs.ru/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - RU\n  excluded: []\n  text: Услуга доступна на территории Российской Федерации и в иных странах, где ее получение не запрещено применимым\n    законодательством.\nentity_types:\n- type: individual\n  text: Пользователем может быть дееспособное физическое лицо, достигшее 18 лет\n- type: business\n  text: индивидуальный предприниматель, плательщик налога на профессиональный доход или юридическое лицо\nrestricted_uses:\n- summary: Prohibited content\n  text: 'Запрещается направлять в Заданиях и создавать\
  \ с помощью Сервиса материалы: содержащие сексуальную эксплуатацию\n    несовершеннолетних либо изображающие несовершеннолетних в сексуализированном контексте'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Для использования Сервиса Пользователь создает аккаунт, указывая адрес электронной почты и пароль\nminimum_age:\n  value: '18'\n  text: дееспособное физическое лицо, достигшее 18 лет\n"
source_yaml_url: https://artifacts.apis.io/apihubs-ru/eligibility/apihubs-ru-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from apihubs-ru's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketplace
- Russian
- Software-as-a-Service
---
