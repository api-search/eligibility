---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: el asegurado deberá declarar, tener como mínimo 18 años de edad
    type: individual
  minimum_age:
    text: tener como mínimo 18 años de edad
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: verificación de identidad por medio de selfie u otros procesos para verificar su identidad
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Crabi
provenance_date: '2026-11-09'
provider_name: Crabi
provider_slug: crabi
slug: crabi-eligibility
source_date: '2026-11-09'
source_filename: crabi-eligibility.yml
source_heading: Eligibility
source_page: https://www.crabi.com/legal/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crabi\naid: crabi\nurl: https://www.crabi.com/legal/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: el asegurado deberá declarar, tener como mínimo 18 años de edad\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: verificación de identidad por medio de selfie u otros procesos para verificar su identidad\nminimum_age:\n  value: '18'\n  text: tener como mínimo 18 años de edad\n"
source_yaml_url: https://artifacts.apis.io/crabi/eligibility/crabi-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Crabi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Auto Insurance
- Mexico
- Financial Services
- Fintech
- Mobile
---
