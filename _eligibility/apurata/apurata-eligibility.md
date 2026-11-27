---
api_specs:
- filename: apurata-config-api-openapi.yml
  format: yaml
  label: Apurata Config API
  slug: apurata-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apurata/openapi/apurata-config-api-openapi.yml
- filename: apurata-orders-api-openapi.yml
  format: yaml
  label: Apurata Orders API
  slug: apurata-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apurata/openapi/apurata-orders-api-openapi.yml
- filename: apurata-refunds-api-openapi.yml
  format: yaml
  label: Apurata Refunds API
  slug: apurata-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apurata/openapi/apurata-refunds-api-openapi.yml
- filename: apurata-widgets-api-openapi.yml
  format: yaml
  label: Apurata Widgets API
  slug: apurata-widgets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apurata/openapi/apurata-widgets-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Los «Servicios y Contenidos» ofrecidos en la Página estarán únicamente disponibles para personas que gocen con capacidad legal para contratar
    type: individual
  - text: En caso de solicitar los «Servicios y Contenidos» a cargo de una persona jurídica, se deberá hacer a través de su representante legal debidamente acreditado.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal use only, no resale
    text: La Página es para el uso personal y del usuario por lo que no podrá comercializar de manera alguna los «Servicios y Contenidos»
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Apurata se reserva el derecho de aprobación y/o rechazo de los solicitantes.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Apurata
provenance_date: '2026-11-09'
provider_name: Apurata
provider_slug: apurata
slug: apurata-eligibility
source_date: '2026-11-09'
source_filename: apurata-eligibility.yml
source_heading: Eligibility
source_page: https://apurata.com/blog/terminos-y-condiciones/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apurata\naid: apurata\nurl: https://apurata.com/blog/terminos-y-condiciones/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Los «Servicios y Contenidos» ofrecidos en la Página estarán únicamente disponibles para personas que gocen\n    con capacidad legal para contratar\n- type: business\n  text: En caso de solicitar los «Servicios y Contenidos» a cargo de una persona jurídica, se deberá hacer a través\n    de su representante legal debidamente acreditado.\nrestricted_uses:\n- summary: Personal use only, no resale\n  text: La Página\
  \ es para el uso personal y del usuario por lo que no podrá comercializar de manera alguna los «Servicios\n    y Contenidos»\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Apurata se reserva el derecho de aprobación y/o rechazo de los solicitantes.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apurata/eligibility/apurata-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Apurata's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Lending
- Buy Now Pay Later
- Installment Payments
- Consumer Credit
- Payments
- E-Commerce
- Peru
- Latin America
---
