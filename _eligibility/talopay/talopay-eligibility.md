---
api_specs:
- filename: talopay-openapi-generated.yml
  format: yaml
  label: Talo Pay API
  slug: talopay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talopay/openapi/_ae-authored/talopay-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Para poder registrarse como Usuario, deberá contar con la mayoría de edad requerida por el ordenamiento jurídico argentino para contratar
    type: individual
  - text: Para el caso de personas jurídicas, únicamente aquellas personas que cuenten con las facultades necesarias para representar y obligar dicha persona jurídica
    type: business
  minimum_age:
    text: deberá contar con la mayoría de edad requerida por el ordenamiento jurídico argentino para contratar
    value: null
  restricted_uses:
  - summary: Uso de QR limitado
    text: El Usuario acepta utilizarlo únicamente para transferencias inmediatas y/o pagos de bienes y/o servicios adquiridos en establecimientos físicos o en línea.
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
name: Talo Pay
provenance_date: '2026-11-10'
provider_name: Talo Pay
provider_slug: talopay
slug: talopay-eligibility
source_date: '2026-11-10'
source_filename: talopay-eligibility.yml
source_heading: Eligibility
source_page: https://talopay.com/ar/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Talo Pay\naid: talopay\nurl: https://talopay.com/ar/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Para poder registrarse como Usuario, deberá contar con la mayoría de edad requerida por el ordenamiento\n    jurídico argentino para contratar\n- type: business\n  text: Para el caso de personas jurídicas, únicamente aquellas personas que cuenten con las facultades necesarias\n    para representar y obligar dicha persona jurídica\nrestricted_uses:\n- summary: Uso de QR limitado\n  text: El Usuario\
  \ acepta utilizarlo únicamente para transferencias inmediatas y/o pagos de bienes y/o servicios\n    adquiridos en establecimientos físicos o en línea.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: deberá contar con la mayoría de edad requerida por el ordenamiento jurídico argentino para contratar\n"
source_yaml_url: https://artifacts.apis.io/talopay/eligibility/talopay-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Talo Pay's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Payments
- Argentina
- E-Commerce
- Bank Transfers
---
