---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - CL
    text: La Suscripción sólo está disponible en Chile, por lo que el Usuario Suscriptor acepta no solicitar el servicio desde fuera de esta ubicación.
  entity_types:
  - text: Toda persona natural o jurídica, o representante de la misma, que utilice la Plataforma, sea que cuente o no con una Suscripción
    type: individual
  minimum_age:
    text: la Plataforma solamente puede ser utilizada por mayores de 18 años
    value: '18'
  restricted_uses:
  - summary: No resale of purchased products
    text: en ningún momento, buscan la posterior comercialización, reventa o cualquier otro tipo de transacción con los Productos adquiridos.
  - summary: Personal use only
    text: exclusivamente para su uso personal, privado y no lucrativo.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: AgroUrbana se reserva el derecho a solicitar, en cualquier momento, algún comprobante y/o dato adicional a efectos de corroborar los datos personales indicados en el Registro
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AgroUrbana
provenance_date: '2026-11-09'
provider_name: AgroUrbana
provider_slug: agrourbana
slug: agrourbana-eligibility
source_date: '2026-11-09'
source_filename: agrourbana-eligibility.yml
source_heading: Eligibility
source_page: https://www.agrourbana.ag/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgroUrbana\naid: agrourbana\nurl: https://www.agrourbana.ag/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CL\n  excluded: []\n  text: La Suscripción sólo está disponible en Chile, por lo que el Usuario Suscriptor acepta no solicitar el servicio\n    desde fuera de esta ubicación.\nentity_types:\n- type: individual\n  text: Toda persona natural o jurídica, o representante de la misma, que utilice la Plataforma, sea que cuente\n    o no con una Suscripción\nrestricted_uses:\n- summary: No resale of purchased products\n  text: en ningún momento, buscan la posterior comercialización,\
  \ reventa o cualquier otro tipo de transacción con\n    los Productos adquiridos.\n- summary: Personal use only\n  text: exclusivamente para su uso personal, privado y no lucrativo.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: AgroUrbana se reserva el derecho a solicitar, en cualquier momento, algún comprobante y/o dato adicional\n    a efectos de corroborar los datos personales indicados en el Registro\nminimum_age:\n  value: '18'\n  text: la Plataforma solamente puede ser utilizada por mayores de 18 años\n"
source_yaml_url: https://artifacts.apis.io/agrourbana/eligibility/agrourbana-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from AgroUrbana's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- AgTech
- Vertical Farming
- Food and Beverage
- Controlled Environment Agriculture
- Chile
- Latin America
- Sustainability
---
