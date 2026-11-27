---
api_specs:
- filename: dadata-clean-openapi-generated.yml
  format: yaml
  label: DaData API-методы API
  slug: clean-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dadata/openapi/_ae-authored/dadata-clean-openapi-generated.yml
- filename: dadata-core-openapi-generated.yml
  format: yaml
  label: DaData core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dadata/openapi/_ae-authored/dadata-core-openapi-generated.yml
- filename: dadata-suggest-openapi-generated.yml
  format: yaml
  label: DaData API-методы API
  slug: suggest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dadata/openapi/_ae-authored/dadata-suggest-openapi-generated.yml
claim_count: 1
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
  - summary: Automated processing via Podskazki
    text: Использовать сервис «Подсказки» для автоматической обработки адресов, ФИО и email.
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
name: DaData
provenance_date: '2026-11-09'
provider_name: DaData
provider_slug: dadata
slug: dadata-eligibility
source_date: '2026-11-09'
source_filename: dadata-eligibility.yml
source_heading: Eligibility
source_page: https://dadata.ru/offer/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DaData\naid: dadata\nurl: https://dadata.ru/offer/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Automated processing via Podskazki\n  text: Использовать сервис «Подсказки» для автоматической обработки адресов, ФИО и email.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dadata/eligibility/dadata-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from DaData's own page on 2026-11-09.
synthetic: false
tags:
- Data
- Russian
- Data Enrichment
- AddressStandardization
---
