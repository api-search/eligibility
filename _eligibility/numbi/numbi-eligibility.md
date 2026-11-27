---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'con la aceptación de estos Términos y Condiciones, declaras expresamente lo siguiente: (i) que eres mayor de edad'
    type: individual
  minimum_age:
    text: que eres mayor de edad y por lo tanto que tienes la capacidad legal para suscribir este Contrato
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: Utilizar el Sitio Web y/o la Plataforma con fines ilícitos, ilegales, contrarios a lo establecido en los presentes Términos y Condiciones
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: No realizamos en Numbi una verificación de la identidad de la Persona que utiliza las Credenciales para ingresar a la Plataforma.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Numbi
provenance_date: '2026-11-10'
provider_name: Numbi
provider_slug: numbi
slug: numbi-eligibility
source_date: '2026-11-10'
source_filename: numbi-eligibility.yml
source_heading: Eligibility
source_page: https://numbi.ai/terminos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Numbi\naid: numbi\nurl: https://numbi.ai/terminos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'con la aceptación de estos Términos y Condiciones, declaras expresamente lo siguiente: (i) que eres mayor\n    de edad'\nrestricted_uses:\n- summary: Illegal or fraudulent use\n  text: Utilizar el Sitio Web y/o la Plataforma con fines ilícitos, ilegales, contrarios a lo establecido en los\n    presentes Términos y Condiciones\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: No realizamos\
  \ en Numbi una verificación de la identidad de la Persona que utiliza las Credenciales para\n    ingresar a la Plataforma.\nminimum_age:\n  value: '18'\n  text: que eres mayor de edad y por lo tanto que tienes la capacidad legal para suscribir este Contrato\n"
source_yaml_url: https://artifacts.apis.io/numbi/eligibility/numbi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Numbi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Accounting
- Payroll
- Tax Compliance
- Bookkeeping
- Colombia
---
