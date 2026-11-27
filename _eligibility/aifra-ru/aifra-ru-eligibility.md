---
api_specs:
- filename: aifra-ru-analytics-api-openapi.yml
  format: yaml
  label: AIfra Analytics API
  slug: aifra-ru-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifra-ru/openapi/aifra-ru-analytics-api-openapi.yml
- filename: aifra-ru-health-api-openapi.yml
  format: yaml
  label: AIfra Health API
  slug: aifra-ru-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifra-ru/openapi/aifra-ru-health-api-openapi.yml
- filename: aifra-ru-mcp-api-openapi.yml
  format: yaml
  label: AIfra MCP API
  slug: aifra-ru-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifra-ru/openapi/aifra-ru-mcp-api-openapi.yml
- filename: aifra-ru-previews-api-openapi.yml
  format: yaml
  label: AIfra Previews API
  slug: aifra-ru-previews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifra-ru/openapi/aifra-ru-previews-api-openapi.yml
- filename: aifra-ru-ready-api-openapi.yml
  format: yaml
  label: AIfra Ready API
  slug: aifra-ru-ready-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifra-ru/openapi/aifra-ru-ready-api-openapi.yml
- filename: aifra-ru-remote-api-openapi.yml
  format: yaml
  label: AIfra Remote API
  slug: aifra-ru-remote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifra-ru/openapi/aifra-ru-remote-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Используйте сервис самостоятельно при наличии необходимой дееспособности либо с надлежащими полномочиями представителя.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Demo data only for MVP
    text: 'Для MVP используйте демоданные: не загружайте персональные данные реальных людей, платёжные реквизиты, документы, секреты или материалы ограниченного доступа.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Для публикации нужны готовые статические файлы и явное принятие условий
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AIfra
provenance_date: '2026-11-09'
provider_name: AIfra
provider_slug: aifra-ru
slug: aifra-ru-eligibility
source_date: '2026-11-09'
source_filename: aifra-ru-eligibility.yml
source_heading: Eligibility
source_page: https://aifra.ru/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIfra\naid: aifra-ru\nurl: https://aifra.ru/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Используйте сервис самостоятельно при наличии необходимой дееспособности либо с надлежащими полномочиями\n    представителя.\nrestricted_uses:\n- summary: Demo data only for MVP\n  text: 'Для MVP используйте демоданные: не загружайте персональные данные реальных людей, платёжные реквизиты,\n    документы, секреты или материалы ограниченного доступа.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Для\
  \ публикации нужны готовые статические файлы и явное принятие условий\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aifra-ru/eligibility/aifra-ru-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from AIfra's own page on 2026-11-09.
synthetic: false
tags:
- Software-as-a-Service
- Static-Previews
- Artificial Intelligence
- CLI
- REST
---
