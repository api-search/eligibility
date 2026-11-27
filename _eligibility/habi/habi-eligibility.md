---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - CO
    text: Los Servicios estarán disponibles en Bogotá D.C. Habi podrá, bajo su propio criterio, ampliar la cobertura de los Servicios a otras ciudades.
  entity_types:
  - text: Los servicios y productos ofrecidos por Habi están destinados para mayores de edad.
    type: individual
  minimum_age:
    text: Los servicios y productos ofrecidos por Habi están destinados para mayores de edad.
    value: '18'
  restricted_uses:
  - summary: Illicit or harmful use
    text: El Usuario de la Página Web no podrá hacer uso de la misma con fines ilícitos, que lesionen derechos e intereses de Habi, terceros
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Habi
provenance_date: '2026-11-09'
provider_name: Habi
provider_slug: habi
slug: habi-eligibility
source_date: '2026-11-09'
source_filename: habi-eligibility.yml
source_heading: Eligibility
source_page: https://habi.co/terminosycondiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Habi\naid: habi\nurl: https://habi.co/terminosycondiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CO\n  excluded: []\n  text: Los Servicios estarán disponibles en Bogotá D.C. Habi podrá, bajo su propio criterio, ampliar la cobertura\n    de los Servicios a otras ciudades.\nentity_types:\n- type: individual\n  text: Los servicios y productos ofrecidos por Habi están destinados para mayores de edad.\nrestricted_uses:\n- summary: Illicit or harmful use\n  text: El Usuario de la Página Web no podrá hacer uso de la misma con fines ilícitos, que lesionen derechos e intereses\n    de Habi, terceros\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Los servicios y productos ofrecidos por Habi están destinados para mayores de edad.\n"
source_yaml_url: https://artifacts.apis.io/habi/eligibility/habi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Habi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- PropTech
- Real Estate
- iBuyer
- Colombia
- Mexico
- Mortgage
- Home Buying
---
