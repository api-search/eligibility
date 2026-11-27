---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Este registro sólo está permitido para las personas naturales mayores de 18 años o a personas jurídicas.
    type: individual
  - text: Este registro sólo está permitido para las personas naturales mayores de 18 años o a personas jurídicas.
    type: business
  minimum_age:
    text: Este registro sólo está permitido para las personas naturales mayores de 18 años
    value: '18'
  restricted_uses:
  - summary: Illegal or violent conduct
    text: Deshabilitaremos al Usuario que realice actos que contraríen la ley colombiana, así como a quienes tengan comportamientos violentos dentro de las Vicos o Vicos Urban.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Realizamos un proceso de verificación tanto a los Propietarios como a los Inquilinos.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vico
provenance_date: '2026-11-10'
provider_name: Vico
provider_slug: vico
slug: vico-eligibility
source_date: '2026-11-10'
source_filename: vico-eligibility.yml
source_heading: Eligibility
source_page: https://getvico.com/terminos-y-condiciones/latest
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vico\naid: vico\nurl: https://getvico.com/terminos-y-condiciones/latest\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Este registro sólo está permitido para las personas naturales mayores de 18 años o a personas jurídicas.\n- type: business\n  text: Este registro sólo está permitido para las personas naturales mayores de 18 años o a personas jurídicas.\nrestricted_uses:\n- summary: Illegal or violent conduct\n  text: Deshabilitaremos al Usuario que realice actos que contraríen la ley colombiana, así como a quienes\
  \ tengan\n    comportamientos violentos dentro de las Vicos o Vicos Urban.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Realizamos un proceso de verificación tanto a los Propietarios como a los Inquilinos.\nminimum_age:\n  value: '18'\n  text: Este registro sólo está permitido para las personas naturales mayores de 18 años\n"
source_yaml_url: https://artifacts.apis.io/vico/eligibility/vico-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Vico's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Rentals
- Housing
- Marketplace
- Co-Living
- Colombia
- Travel
---
