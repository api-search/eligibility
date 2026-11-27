---
api_specs:
- filename: alfil-co-b-squeda-api-openapi.yml
  format: yaml
  label: Alfil Búsqueda API
  slug: alfil-co-b-squeda-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alfil-co/openapi/alfil-co-b-squeda-api-openapi.yml
- filename: alfil-co-congreso-api-openapi.yml
  format: yaml
  label: Alfil Congreso API
  slug: alfil-co-congreso-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alfil-co/openapi/alfil-co-congreso-api-openapi.yml
- filename: alfil-co-contrataci-n-api-openapi.yml
  format: yaml
  label: Alfil Contratación API
  slug: alfil-co-contrataci-n-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alfil-co/openapi/alfil-co-contrataci-n-api-openapi.yml
- filename: alfil-co-electoral-api-openapi.yml
  format: yaml
  label: Alfil Electoral API
  slug: alfil-co-electoral-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alfil-co/openapi/alfil-co-electoral-api-openapi.yml
- filename: alfil-co-finanzas-api-openapi.yml
  format: yaml
  label: Alfil Finanzas API
  slug: alfil-co-finanzas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alfil-co/openapi/alfil-co-finanzas-api-openapi.yml
- filename: alfil-co-geograf-as-api-openapi.yml
  format: yaml
  label: Alfil Geografías API
  slug: alfil-co-geograf-as-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alfil-co/openapi/alfil-co-geograf-as-api-openapi.yml
- filename: alfil-co-partidos-api-openapi.yml
  format: yaml
  label: Alfil Partidos API
  slug: alfil-co-partidos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alfil-co/openapi/alfil-co-partidos-api-openapi.yml
- filename: alfil-co-pol-ticos-api-openapi.yml
  format: yaml
  label: Alfil Políticos API
  slug: alfil-co-pol-ticos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alfil-co/openapi/alfil-co-pol-ticos-api-openapi.yml
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
  - summary: Scoring, listas negras y decisiones reguladas
    text: hacer scoring de personas, listas negras, background checks indiscriminados, KYC o decisiones sobre empleo, crédito, seguro, vivienda u otros servicios regulados
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
name: Alfil
provenance_date: '2026-11-09'
provider_name: Alfil
provider_slug: alfil-co
slug: alfil-co-eligibility
source_date: '2026-11-09'
source_filename: alfil-co-eligibility.yml
source_heading: Eligibility
source_page: https://www.alfil.co/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alfil\naid: alfil-co\nurl: https://www.alfil.co/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Scoring, listas negras y decisiones reguladas\n  text: hacer scoring de personas, listas negras, background checks indiscriminados, KYC o decisiones sobre empleo,\n    crédito, seguro, vivienda u otros servicios regulados\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alfil-co/eligibility/alfil-co-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Alfil's own page on 2026-11-09.
synthetic: false
tags:
- Politics
- Colombia
- Elections
- Public Procurement
- Data Analysis
- Intelligence
---
