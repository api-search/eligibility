---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Personas físicas que proveedores independientes de servicios de cuidado de mascotas que desean ofertar sus servicios a través de la Plataforma
    type: individual
  minimum_age:
    text: debes de ser mayor de edad, en ninguna circunstancia, permitimos el acceso y/o utilización de la Plataforma a menores de 18 (Dieciocho) años.
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: CMM evaluará la información brindada, y eventualmente aceptará o rechazará la solicitud.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cuida Mi Mascota
provenance_date: '2026-11-09'
provider_name: Cuida Mi Mascota
provider_slug: cuida-mi-mascota
slug: cuida-mi-mascota-eligibility
source_date: '2026-11-09'
source_filename: cuida-mi-mascota-eligibility.yml
source_heading: Eligibility
source_page: https://www.cuidamimascota.com.mx/tyc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cuida Mi Mascota\naid: cuida-mi-mascota\nurl: https://www.cuidamimascota.com.mx/tyc\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Personas físicas que proveedores independientes de servicios de cuidado de mascotas que desean ofertar sus\n    servicios a través de la Plataforma\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: CMM evaluará la información brindada, y eventualmente aceptará o rechazará la solicitud.\nminimum_age:\n  value: '18'\n  text: debes de ser mayor de edad, en ninguna\
  \ circunstancia, permitimos el acceso y/o utilización de la Plataforma\n    a menores de 18 (Dieciocho) años.\n"
source_yaml_url: https://artifacts.apis.io/cuida-mi-mascota/eligibility/cuida-mi-mascota-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Cuida Mi Mascota's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pets
- Pet Care
- Marketplace
- Mobile
- Consumer
- Mexico
- Two-Sided Marketplace
---
