---
api_specs:
- filename: appsmax-rest-api-v1-access-api-openapi.yml
  format: yaml
  label: AppsMax Access API
  slug: appsmax-rest-api-v1-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-access-api-openapi.yml
- filename: appsmax-rest-api-v1-applications-api-openapi.yml
  format: yaml
  label: AppsMax Applications API
  slug: appsmax-rest-api-v1-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-applications-api-openapi.yml
- filename: appsmax-rest-api-v1-bots-api-openapi.yml
  format: yaml
  label: AppsMax Bots API
  slug: appsmax-rest-api-v1-bots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-bots-api-openapi.yml
- filename: appsmax-rest-api-v1-campaigns-api-openapi.yml
  format: yaml
  label: AppsMax Campaigns API
  slug: appsmax-rest-api-v1-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-campaigns-api-openapi.yml
- filename: appsmax-rest-api-v1-funnels-api-openapi.yml
  format: yaml
  label: AppsMax Funnels API
  slug: appsmax-rest-api-v1-funnels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-funnels-api-openapi.yml
- filename: appsmax-rest-api-v1-interactive-menu-api-openapi.yml
  format: yaml
  label: AppsMax Interactive menu API
  slug: appsmax-rest-api-v1-interactive-menu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-interactive-menu-api-openapi.yml
- filename: appsmax-rest-api-v1-miniapps-api-openapi.yml
  format: yaml
  label: AppsMax Miniapps API
  slug: appsmax-rest-api-v1-miniapps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-miniapps-api-openapi.yml
- filename: appsmax-rest-api-v1-organizations-api-openapi.yml
  format: yaml
  label: AppsMax Organizations API
  slug: appsmax-rest-api-v1-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-organizations-api-openapi.yml
- filename: appsmax-rest-api-v1-subscribers-api-openapi.yml
  format: yaml
  label: AppsMax Subscribers API
  slug: appsmax-rest-api-v1-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-subscribers-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Пользователь — физическое лицо, индивидуальный предприниматель или организация, принявшие оферту.
    type: individual
  - text: Для организаций и предпринимателей порядок прекращения и расчётов определяется настоящей офертой и применимыми нормами гражданского законодательства.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Акцептом считается одновременная отдельная отметка о принятии оферты и завершение регистрации либо оплата выбранной услуги.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AppsMax
provenance_date: '2026-11-09'
provider_name: AppsMax
provider_slug: appsmax-rest-api-v1
slug: appsmax-rest-api-v1-eligibility
source_date: '2026-11-09'
source_filename: appsmax-rest-api-v1-eligibility.yml
source_heading: Eligibility
source_page: https://appsmax.ru/documents/publichnaya-oferta/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AppsMax\naid: appsmax-rest-api-v1\nurl: https://appsmax.ru/documents/publichnaya-oferta/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Пользователь — физическое лицо, индивидуальный предприниматель или организация, принявшие оферту.\n- type: business\n  text: Для организаций и предпринимателей порядок прекращения и расчётов определяется настоящей офертой и применимыми\n    нормами гражданского законодательства.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Акцептом считается одновременная\
  \ отдельная отметка о принятии оферты и завершение регистрации либо оплата\n    выбранной услуги.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/appsmax-rest-api-v1/eligibility/appsmax-rest-api-v1-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from AppsMax's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Messaging
- Business Automation
- Chatbots
- Mini Apps
- Customer Requests
- Workflow Automation
- MAX
- Telegram
- Russian Language
---
