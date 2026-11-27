---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: los Servicios sólo van dirigidos a residentes de los Estados Unidos Mexicanos
  entity_types:
  - text: declara bajo protesta de decir verdad que actúa por nombre propio y es mayor de edad
    type: individual
  - text: no podrá usar el Servicio para ningún uso comercial o en nombre o por cuenta de otra persona
    type: business
  minimum_age:
    text: si el Usuario es menor de 18 (dieciocho) años no puede utilizar los Servicios
    value: '18'
  restricted_uses:
  - summary: Minors excluded
    text: si el Usuario es menor de 18 (dieciocho) años no puede utilizar los Servicios ni acceder al Sitio Web o Aplicación bajo ninguna circunstancia
  - summary: VPN or location masking
    text: Si está utilizando o intentando utilizar una VPN o alguna tecnología similar para ocultar su ubicación
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: es posible que requiramos verificar la identidad del Usuario, lo que incluye pasar ciertos controles. Podremos solicitarle que proporcione una prueba de identificación válida
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Draftea
provenance_date: '2026-11-09'
provider_name: Draftea
provider_slug: draftea
slug: draftea-eligibility
source_date: '2026-11-09'
source_filename: draftea-eligibility.yml
source_heading: Eligibility
source_page: https://www.draftea.mx/page/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Draftea\naid: draftea\nurl: https://www.draftea.mx/page/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: los Servicios sólo van dirigidos a residentes de los Estados Unidos Mexicanos\nentity_types:\n- type: individual\n  text: declara bajo protesta de decir verdad que actúa por nombre propio y es mayor de edad\n- type: business\n  text: no podrá usar el Servicio para ningún uso comercial o en nombre o por cuenta de otra persona\nrestricted_uses:\n- summary: Minors excluded\n  text: si el Usuario es menor de 18 (dieciocho) años no puede\
  \ utilizar los Servicios ni acceder al Sitio Web o\n    Aplicación bajo ninguna circunstancia\n- summary: VPN or location masking\n  text: Si está utilizando o intentando utilizar una VPN o alguna tecnología similar para ocultar su ubicación\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: es posible que requiramos verificar la identidad del Usuario, lo que incluye pasar ciertos controles. Podremos\n    solicitarle que proporcione una prueba de identificación válida\nminimum_age:\n  value: '18'\n  text: si el Usuario es menor de 18 (dieciocho) años no puede utilizar los Servicios\n"
source_yaml_url: https://artifacts.apis.io/draftea/eligibility/draftea-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Draftea's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fantasy Sports
- Daily Fantasy Sports
- Sports Betting
- Gaming
- Sports
- Mexico
- Latin America
- Consumer
---
