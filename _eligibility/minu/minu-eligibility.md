---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: Ley General de Protección de Datos Personales en Posesión de Sujetos Obligados (México)
  entity_types:
  - text: Cualquier persona física mayor de edad, que labora o presta sus servicios personales en favor de una Empresa Afiliada
    type: individual
  minimum_age:
    text: Cualquier persona física mayor de edad
    value: null
  restricted_uses:
  - summary: Savings account must be in the user's own name
    text: en ningún momento el titular de la Cuenta Ordenante podrá ser distinto al Usuario
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: MINU, bajo ninguna circunstancia tendrá la facultad u obligación de prestar sus Servicios a los Usuarios que no estén aprobados por el área de recursos humanos o similar de la Empresa Afiliada
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Minu
provenance_date: '2026-11-10'
provider_name: Minu
provider_slug: minu
slug: minu-eligibility
source_date: '2026-11-10'
source_filename: minu-eligibility.yml
source_heading: Eligibility
source_page: https://www.minu.mx/tycos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Minu\naid: minu\nurl: https://www.minu.mx/tycos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: Ley General de Protección de Datos Personales en Posesión de Sujetos Obligados (México)\nentity_types:\n- type: individual\n  text: Cualquier persona física mayor de edad, que labora o presta sus servicios personales en favor de una Empresa\n    Afiliada\nrestricted_uses:\n- summary: Savings account must be in the user's own name\n  text: en ningún momento el titular de la Cuenta Ordenante podrá ser distinto al Usuario\nverification:\n  kyc: true\n  kyb: null\n\
  \  approval_required: true\n  text: MINU, bajo ninguna circunstancia tendrá la facultad u obligación de prestar sus Servicios a los Usuarios\n    que no estén aprobados por el área de recursos humanos o similar de la Empresa Afiliada\nminimum_age:\n  value: null\n  text: Cualquier persona física mayor de edad\n"
source_yaml_url: https://artifacts.apis.io/minu/eligibility/minu-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Minu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Earned Wage Access
- Employee Benefits
- Financial Wellness
- Fintech
- Payroll
- Mexico
---
