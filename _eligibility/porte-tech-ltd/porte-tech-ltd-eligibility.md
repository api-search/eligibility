---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: «Пользователь» - лицо, использующее Приложение Porte.
    type: individual
  minimum_age:
    text: Приложение Porte доступно только лицам от 18 лет и старше.
    value: '18'
  restricted_uses:
  - summary: No use of another person's account or payment data
    text: использовать или пытаться использовать личную учетную запись Porte другого лица
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Регистрация учетной записи требует предоставления Пользователем Porte определенных персональных данных
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Porte Tech
provenance_date: '2026-11-10'
provider_name: Porte Tech
provider_slug: porte-tech-ltd
slug: porte-tech-ltd-eligibility
source_date: '2026-11-10'
source_filename: porte-tech-ltd-eligibility.yml
source_heading: Eligibility
source_page: https://porte.tech/docs/Terms_of_use-RU.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Porte Tech\naid: porte-tech-ltd\nurl: https://porte.tech/docs/Terms_of_use-RU.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: «Пользователь» - лицо, использующее Приложение Porte.\nrestricted_uses:\n- summary: No use of another person's account or payment data\n  text: использовать или пытаться использовать личную учетную запись Porte другого лица\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Регистрация учетной записи требует предоставления Пользователем Porte определенных персональных данных\nminimum_age:\n\
  \  value: '18'\n  text: Приложение Porte доступно только лицам от 18 лет и старше.\n"
source_yaml_url: https://artifacts.apis.io/porte-tech-ltd/eligibility/porte-tech-ltd-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Porte Tech's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hospitality
- Hotel Technology
- Digital Concierge
- Guest Experience
- Access Control
- Kazakhstan
---
