---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Declara el Usuario ser una persona física mayor de edad y contar con capacidad para contratar y contraer toda clase de obligaciones.
    type: individual
  minimum_age:
    text: Declara el Usuario ser una persona física mayor de edad
    value: null
  restricted_uses:
  - summary: Restricted account segments
    text: 'albo se reserva el derecho a cancelar o abrir cuentas que tengan, entre otros, alguno de los siguientes segmentos como actividad principal o ingreso de recursos:'
  - summary: Illicit funds prohibited
    text: g) Llevar a cabo actos u operaciones con recursos de procedencia ilícita.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: A través de la Plataforma y el servicio, los Usuarios registran datos personales y de debida diligencia para tener una adecuada identificación y conocimiento del Usuario.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Albo
provenance_date: '2026-11-09'
provider_name: Albo
provider_slug: albo
slug: albo-eligibility
source_date: '2026-11-09'
source_filename: albo-eligibility.yml
source_heading: Eligibility
source_page: https://www.albo.com/albo/terminos-y-condiciones.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Albo\naid: albo\nurl: https://www.albo.com/albo/terminos-y-condiciones.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Declara el Usuario ser una persona física mayor de edad y contar con capacidad para contratar y contraer\n    toda clase de obligaciones.\nrestricted_uses:\n- summary: Restricted account segments\n  text: 'albo se reserva el derecho a cancelar o abrir cuentas que tengan, entre otros, alguno de los siguientes\n    segmentos como actividad principal o ingreso de recursos:'\n- summary: Illicit funds prohibited\n\
  \  text: g) Llevar a cabo actos u operaciones con recursos de procedencia ilícita.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: A través de la Plataforma y el servicio, los Usuarios registran datos personales y de debida diligencia\n    para tener una adecuada identificación y conocimiento del Usuario.\nminimum_age:\n  value: null\n  text: Declara el Usuario ser una persona física mayor de edad\n"
source_yaml_url: https://artifacts.apis.io/albo/eligibility/albo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Albo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Financial Services
- Fintech
- Neobank
- Digital Banking
- Payments
- Mexico
- Latin America
- Consumer Finance
---
