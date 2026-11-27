---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: el Cliente debe tener al menos 18 años
    type: individual
  - text: o ser una empresa, organización u otra entidad legalmente constituida y vigente que cumpla con las leyes aplicables
    type: business
  minimum_age:
    text: el Cliente debe tener al menos 18 años
    value: '18'
  restricted_uses:
  - summary: Hazardous materials
    text: No se aceptarán para su transportación, almacenamiento y/o custodia artículos y materiales peligrosos, incluyendo materiales peligrosos regulados como tales en términos de la ley aplicable.
  - summary: Restricted goods
    text: No se aceptarán monedas, billetes de banco, documentos negociables, títulos de crédito, antigüedades, vinos, armas de fuego, explosivos, plantas y animales
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Mubit.co podrá supeditar el acceso y uso del Sitio Web o de ciertas áreas o funciones del mismo, a determinadas condiciones o requisitos, como realizar un proceso de verificación
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mubit
provenance_date: '2026-11-10'
provider_name: Mubit
provider_slug: mubit
slug: mubit-eligibility
source_date: '2026-11-10'
source_filename: mubit-eligibility.yml
source_heading: Eligibility
source_page: https://mubit.co/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mubit\naid: mubit\nurl: https://mubit.co/terminos-y-condiciones\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: el Cliente debe tener al menos 18 años\n- type: business\n  text: o ser una empresa, organización u otra entidad legalmente constituida y vigente que cumpla con las leyes\n    aplicables\nrestricted_uses:\n- summary: Hazardous materials\n  text: No se aceptarán para su transportación, almacenamiento y/o custodia artículos y materiales peligrosos, incluyendo\n    materiales peligrosos regulados como tales en términos de la\
  \ ley aplicable.\n- summary: Restricted goods\n  text: No se aceptarán monedas, billetes de banco, documentos negociables, títulos de crédito, antigüedades, vinos,\n    armas de fuego, explosivos, plantas y animales\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Mubit.co podrá supeditar el acceso y uso del Sitio Web o de ciertas áreas o funciones del mismo, a determinadas\n    condiciones o requisitos, como realizar un proceso de verificación\nminimum_age:\n  value: '18'\n  text: el Cliente debe tener al menos 18 años\n"
source_yaml_url: https://artifacts.apis.io/mubit/eligibility/mubit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Mubit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Storage
- Self Storage
- Logistics
- Warehousing
- Inventory
- Moving
- Mexico
---
