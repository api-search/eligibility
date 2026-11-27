---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: personas físicas, personas físicas con actividad empresarial o personas morales, todos de nacionalidad mexicana.
  entity_types:
  - text: Es una persona física de nacionalidad mexicana, mayor de edad, con plena capacidad para obligarse y contratar
    type: individual
  - text: Es una persona moral debidamente constituida conforme a las leyes mexicanas
    type: business
  minimum_age:
    text: mayor de edad
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: El destino del Crédito será dedicado tan solo a fines permitidos por la ley y que no se encuentran dentro de los supuestos establecidos por los artículos 139 Quáter y 400 Bis del Código Penal Federal.
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
name: Tienda Pago
provenance_date: '2026-11-10'
provider_name: Tienda Pago
provider_slug: tienda-pago
slug: tienda-pago-eligibility
source_date: '2026-11-10'
source_filename: tienda-pago-eligibility.yml
source_heading: Eligibility
source_page: https://tiendapago.com/es-MX/contract
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tienda Pago\naid: tienda-pago\nurl: https://tiendapago.com/es-MX/contract\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: personas físicas, personas físicas con actividad empresarial o personas morales, todos de nacionalidad mexicana.\nentity_types:\n- type: individual\n  text: Es una persona física de nacionalidad mexicana, mayor de edad, con plena capacidad para obligarse y contratar\n- type: business\n  text: Es una persona moral debidamente constituida conforme a las leyes mexicanas\nrestricted_uses:\n- summary: Lawful purposes only\n  text: El destino\
  \ del Crédito será dedicado tan solo a fines permitidos por la ley y que no se encuentran dentro\n    de los supuestos establecidos por los artículos 139 Quáter y 400 Bis del Código Penal Federal.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: mayor de edad\n"
source_yaml_url: https://artifacts.apis.io/tienda-pago/eligibility/tienda-pago-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Tienda Pago's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Lending
- Fintech
- Payments
- Working Capital
- Buy Now Pay Later
- Mexico
- Peru
- Small Business
---
