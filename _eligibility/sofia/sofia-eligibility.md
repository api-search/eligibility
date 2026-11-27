---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Persona que ha solicitado la contratación del Plan para sí o para terceras personas
    type: individual
  - text: Totalidad de los Socios o Socias en servicio activo de una empresa constituida legalmente
    type: business
  minimum_age:
    text: Los Usuarios menores de 18 años de edad, pueden utilizar los Servicios únicamente con la autorización, participación e involucramiento de sus padres o tutores
    value: '18'
  restricted_uses:
  - summary: No video consultation for medical emergencies
    text: el Usuario reconoce, que deberá abstenerse de utilizar el Servicio de Videoconsulta en relación con una urgencia médica.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Sofía se reserva el derecho de rechazar cualquier solicitud de Cuenta, cancelar o suspender una Cuenta, sin que esté obligado a comunicar las razones de ello
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sofia
provenance_date: '2026-11-10'
provider_name: Sofia
provider_slug: sofia
slug: sofia-eligibility
source_date: '2026-11-10'
source_filename: sofia-eligibility.yml
source_heading: Eligibility
source_page: https://www.sofiasalud.com/otros/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sofia\naid: sofia\nurl: https://www.sofiasalud.com/otros/terminos-y-condiciones\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Persona que ha solicitado la contratación del Plan para sí o para terceras personas\n- type: business\n  text: Totalidad de los Socios o Socias en servicio activo de una empresa constituida legalmente\nrestricted_uses:\n- summary: No video consultation for medical emergencies\n  text: el Usuario reconoce, que deberá abstenerse de utilizar el Servicio de Videoconsulta en relación con una\n    urgencia médica.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Sofía se reserva el derecho de rechazar cualquier solicitud de Cuenta, cancelar o suspender una Cuenta,\n    sin que esté obligado a comunicar las razones de ello\nminimum_age:\n  value: '18'\n  text: Los Usuarios menores de 18 años de edad, pueden utilizar los Servicios únicamente con la autorización, participación\n    e involucramiento de sus padres o tutores\n"
source_yaml_url: https://artifacts.apis.io/sofia/eligibility/sofia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Sofia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurtech
- Insurance
- Health Insurance
- Healthcare
- Digital Health
- Mexico
- Consumer
---
