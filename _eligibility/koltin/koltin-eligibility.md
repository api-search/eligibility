---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Los servicios de protección en beneficio de personas adultas mayores entre 60 y 85 años, según se puedan señalar en la Página de tiempo en tiempo.
  entity_types:
  - text: significa cualquier persona física o moral que utilice, tenga acceso a una cuenta de Koltin o contrate nuestros Servicios a través de la Página
    type: individual
  - text: Si usa o contrata nuestros Servicios en representación de otra persona física o moral, declara y garantiza que se encuentra autorizado y facultado para aceptar el Acuerdo
    type: business
  minimum_age:
    text: Si se registra como usuario o utiliza nuestros Servicios, declara que tiene al menos 18 años.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Podemos limitar su acceso a nuestros Servicios hasta que podamos verificar la información de su cuenta, como su dirección de correo electrónico
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Koltin
provenance_date: '2026-11-09'
provider_name: Koltin
provider_slug: koltin
slug: koltin-eligibility
source_date: '2026-11-09'
source_filename: koltin-eligibility.yml
source_heading: Eligibility
source_page: https://koltin.mx/terminos-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Koltin\naid: koltin\nurl: https://koltin.mx/terminos-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Los servicios de protección en beneficio de personas adultas mayores entre 60 y 85 años, según se puedan\n    señalar en la Página de tiempo en tiempo.\nentity_types:\n- type: individual\n  text: significa cualquier persona física o moral que utilice, tenga acceso a una cuenta de Koltin o contrate nuestros\n    Servicios a través de la Página\n- type: business\n  text: Si usa o contrata nuestros Servicios en representación de otra persona física o moral, declara y garantiza\n\
  \    que se encuentra autorizado y facultado para aceptar el Acuerdo\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Podemos limitar su acceso a nuestros Servicios hasta que podamos verificar la información de su cuenta,\n    como su dirección de correo electrónico\nminimum_age:\n  value: '18'\n  text: Si se registra como usuario o utiliza nuestros Servicios, declara que tiene al menos 18 años.\n"
source_yaml_url: https://artifacts.apis.io/koltin/eligibility/koltin-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from Koltin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Insurance
- Preventive Medicine
- Senior Care
- Membership
- Mexico
---
