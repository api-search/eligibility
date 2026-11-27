---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Avify es una plataforma de software como servicio (SaaS) para empresas que venden a través de WhatsApp, redes sociales, tiendas en línea y puntos de venta físicos.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: AVI for medical, legal or financial advice
    text: El Usuario no debe configurarlo para dar diagnósticos, indicaciones médicas, asesoría legal o financiera, ni para tomar decisiones que requieran criterio profesional.
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
name: Avify
provenance_date: '2026-11-09'
provider_name: Avify
provider_slug: avify
slug: avify-eligibility
source_date: '2026-11-09'
source_filename: avify-eligibility.yml
source_heading: Eligibility
source_page: https://avify.com/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avify\naid: avify\nurl: https://avify.com/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Avify es una plataforma de software como servicio (SaaS) para empresas que venden a través de WhatsApp,\n    redes sociales, tiendas en línea y puntos de venta físicos.\nrestricted_uses:\n- summary: AVI for medical, legal or financial advice\n  text: El Usuario no debe configurarlo para dar diagnósticos, indicaciones médicas, asesoría legal o financiera,\n    ni para tomar decisiones que requieran criterio profesional.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/avify/eligibility/avify-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Avify's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commerce
- E-Commerce
- CRM
- WhatsApp
- Conversational Commerce
- Inventory
- Point-of-Sale
- Payments
- Order
- GraphQL
- Latin America
- Small Business
---
