---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - PE
    text: exclusivamente en la República del Perú
  entity_types:
  - text: Solo podrán registrarse personas naturales residentes en la República del Perú
    type: individual
  minimum_age:
    text: Ser mayor de edad (mínimo 18 años).
    value: '18'
  restricted_uses:
  - summary: Funds linked to money laundering or terrorism financing
    text: No gestionar fondos provenientes o vinculados con el lavado de activos o el financiamiento del terrorismo.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: verifica la identidad de los Usuarios y cuenta con controles en materia de PLAFT
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PreAuth (Instacash)
provenance_date: '2026-11-09'
provider_name: PreAuth (Instacash)
provider_slug: instacash-pe
slug: instacash-pe-eligibility
source_date: '2026-11-09'
source_filename: instacash-pe-eligibility.yml
source_heading: Eligibility
source_page: https://reevalua.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PreAuth (Instacash)\naid: instacash-pe\nurl: https://reevalua.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - PE\n  excluded: []\n  text: exclusivamente en la República del Perú\nentity_types:\n- type: individual\n  text: Solo podrán registrarse personas naturales residentes en la República del Perú\nrestricted_uses:\n- summary: Funds linked to money laundering or terrorism financing\n  text: No gestionar fondos provenientes o vinculados con el lavado de activos o el financiamiento del terrorismo.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: verifica la identidad\
  \ de los Usuarios y cuenta con controles en materia de PLAFT\nminimum_age:\n  value: '18'\n  text: Ser mayor de edad (mínimo 18 años).\n"
source_yaml_url: https://artifacts.apis.io/instacash-pe/eligibility/instacash-pe-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from PreAuth (Instacash)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
---
