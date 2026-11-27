---
api_specs:
- filename: srezai-ru-openapi-generated.yml
  format: yaml
  label: srezai-ru API
  slug: srezai-ru-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/srezai-ru/openapi/_ae-authored/srezai-ru-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Регистрация лиц младше 18 лет допускается только с согласия законного представителя.
    type: individual
  minimum_age:
    text: Регистрация лиц младше 18 лет допускается только с согласия законного представителя.
    value: '18'
  restricted_uses:
  - summary: Prohibited unlawful or harmful uses
    text: использовать Сервис для рассылки спама, фишинга, распространения вредоносного кода, нарушения работы информационных систем третьих лиц
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
name: srezai-ru
provenance_date: '2026-11-10'
provider_name: srezai-ru
provider_slug: srezai-ru
slug: srezai-ru-eligibility
source_date: '2026-11-10'
source_filename: srezai-ru-eligibility.yml
source_heading: Eligibility
source_page: https://srezai.ru/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: srezai-ru\naid: srezai-ru\nurl: https://srezai.ru/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Регистрация лиц младше 18 лет допускается только с согласия законного представителя.\nrestricted_uses:\n- summary: Prohibited unlawful or harmful uses\n  text: использовать Сервис для рассылки спама, фишинга, распространения вредоносного кода, нарушения работы информационных\n    систем третьих лиц\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Регистрация\
  \ лиц младше 18 лет допускается только с согласия законного представителя.\n"
source_yaml_url: https://artifacts.apis.io/srezai-ru/eligibility/srezai-ru-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from srezai-ru's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Search
- Artificial Intelligence
- Russia
---
