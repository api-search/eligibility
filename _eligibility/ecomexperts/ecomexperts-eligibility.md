---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AR
    - MX
    - CL
    - UY
    - CO
    - PE
    text: 'Según el país desde el que contrates, tu contraparte es una de estas tres sociedades:'
  entity_types:
  - text: El servicio está dirigido a personas humanas o jurídicas que desarrollan una actividad comercial.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted or prohibited products
    text: Comercializar productos cuya venta esté prohibida o restringida sin contar con las autorizaciones correspondientes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Quien contrata en nombre de una empresa declara tener facultades suficientes para hacerlo.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: EcomExperts
provenance_date: '2026-11-09'
provider_name: EcomExperts
provider_slug: ecomexperts
slug: ecomexperts-eligibility
source_date: '2026-11-09'
source_filename: ecomexperts-eligibility.yml
source_heading: Eligibility
source_page: https://www.ecomexperts.com/terminos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EcomExperts\naid: ecomexperts\nurl: https://www.ecomexperts.com/terminos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AR\n  - MX\n  - CL\n  - UY\n  - CO\n  - PE\n  excluded: []\n  text: 'Según el país desde el que contrates, tu contraparte es una de estas tres sociedades:'\nentity_types:\n- type: business\n  text: El servicio está dirigido a personas humanas o jurídicas que desarrollan una actividad comercial.\nrestricted_uses:\n- summary: Restricted or prohibited products\n  text: Comercializar productos cuya venta esté prohibida o restringida sin contar con las autorizaciones correspondientes.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Quien contrata en nombre de una empresa declara tener facultades suficientes para hacerlo.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ecomexperts/eligibility/ecomexperts-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from EcomExperts's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- ERP
- Omnichannel
- Inventory
- E-Invoicing
- Marketplace Integration
- Mercado Libre
- Software-as-a-Service
- Latin America
---
