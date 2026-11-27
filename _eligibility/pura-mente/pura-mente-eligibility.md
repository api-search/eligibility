---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Las personas físicas que se registren en la app de Pura Mente se denominan “Usuario o Usuarios”.
    type: individual
  minimum_age:
    text: No podrán utilizar los servicios los menores de edad sin la participación y consentimiento del responsable legal, padre o tutor legal
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Pura Mente se reserva el derecho de hacer una verificación manual sobre la veracidad del Usuario basándose en prueba suficiente que el mismo Usuario deberá presentar
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pura Mente
provenance_date: '2026-11-10'
provider_name: Pura Mente
provider_slug: pura-mente
slug: pura-mente-eligibility
source_date: '2026-11-10'
source_filename: pura-mente-eligibility.yml
source_heading: Eligibility
source_page: https://www.puramente.app/terminos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pura Mente\naid: pura-mente\nurl: https://www.puramente.app/terminos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Las personas físicas que se registren en la app de Pura Mente se denominan “Usuario o Usuarios”.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Pura Mente se reserva el derecho de hacer una verificación manual sobre la veracidad del Usuario basándose\n    en prueba suficiente que el mismo Usuario deberá presentar\nminimum_age:\n  value: null\n  text: No podrán utilizar\
  \ los servicios los menores de edad sin la participación y consentimiento del responsable\n    legal, padre o tutor legal\n"
source_yaml_url: https://artifacts.apis.io/pura-mente/eligibility/pura-mente-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Pura Mente's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Meditation
- Mindfulness
- Sleep
- Wellness
- Mental Health
- Consumer App
- Mobile
---
