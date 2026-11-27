---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: Ley Federal del Derecho de Autor, la Ley de la Propiedad Industrial, así como cualquier otro ordenamiento en materia de Propiedad Intelectual aplicable de los Estados Unidos Mexicanos.
  entity_types:
  - text: La Plataforma está diseñada para el uso exclusivo de personas físicas, por lo que no podrán registrarse y/o celebrar operaciones con Baubap ninguna persona moral.
    type: individual
  minimum_age:
    text: Los Servicios sólo están disponibles para personas físicas mayores de edad con plena capacidad legal para contratar
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: El destino de los servicios o productos adquiridos será dedicado tan solo a fines permitidos por la ley
  verification:
    approval_required: true
    kyb: false
    kyc: true
    text: Baubap podrá utilizar diversos medios para identificar a sus Usuarios, pero Baubap no se responsabiliza por la veracidad de los Datos Personales provistos por sus Usuarios. Baubap se reserva el derecho de solicitar algún comprobante adicional
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Baubap
provenance_date: '2026-11-09'
provider_name: Baubap
provider_slug: baubap
slug: baubap-eligibility
source_date: '2026-11-09'
source_filename: baubap-eligibility.yml
source_heading: Eligibility
source_page: https://www.baubap.com/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Baubap\naid: baubap\nurl: https://www.baubap.com/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: Ley Federal del Derecho de Autor, la Ley de la Propiedad Industrial, así como cualquier otro ordenamiento\n    en materia de Propiedad Intelectual aplicable de los Estados Unidos Mexicanos.\nentity_types:\n- type: individual\n  text: La Plataforma está diseñada para el uso exclusivo de personas físicas, por lo que no podrán registrarse\n    y/o celebrar operaciones con Baubap ninguna persona moral.\nrestricted_uses:\n- summary: Lawful purposes\
  \ only\n  text: El destino de los servicios o productos adquiridos será dedicado tan solo a fines permitidos por la ley\nverification:\n  kyc: true\n  kyb: false\n  approval_required: true\n  text: Baubap podrá utilizar diversos medios para identificar a sus Usuarios, pero Baubap no se responsabiliza\n    por la veracidad de los Datos Personales provistos por sus Usuarios. Baubap se reserva el derecho de solicitar\n    algún comprobante adicional\nminimum_age:\n  value: null\n  text: Los Servicios sólo están disponibles para personas físicas mayores de edad con plena capacidad legal para\n    contratar\n"
source_yaml_url: https://artifacts.apis.io/baubap/eligibility/baubap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Baubap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Microloans
- Consumer Finance
- Financial Inclusion
- Mexico
- Mobile App
---
