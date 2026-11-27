---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - CO
    text: Zíro es una compañía de base tecnológica que ofrece servicios financieros para los micro y pequeños empresarios en Colombia
  entity_types:
  - text: Actualmente, otorgamos financiación a personas naturales bajo la modalidad Compre Ahora y Pague Después
    type: individual
  minimum_age:
    text: Ser mayor de edad.
    value: mayor de edad
  restricted_uses:
  - summary: No cash or electronic transfer loans
    text: Zíro no realiza préstamos en efectivo o en transferencias electrónicas a cuentas.
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
name: Ziro
provenance_date: '2026-11-10'
provider_name: Ziro
provider_slug: ziro
slug: ziro-eligibility
source_date: '2026-11-10'
source_filename: ziro-eligibility.yml
source_heading: Eligibility
source_page: https://somosziro.com/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ziro\naid: ziro\nurl: https://somosziro.com/terminos-y-condiciones\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CO\n  excluded: []\n  text: Zíro es una compañía de base tecnológica que ofrece servicios financieros para los micro y pequeños empresarios\n    en Colombia\nentity_types:\n- type: individual\n  text: Actualmente, otorgamos financiación a personas naturales bajo la modalidad Compre Ahora y Pague Después\nrestricted_uses:\n- summary: No cash or electronic transfer loans\n  text: Zíro no realiza préstamos en efectivo o en transferencias electrónicas a cuentas.\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: mayor de edad\n  text: Ser mayor de edad.\n"
source_yaml_url: https://artifacts.apis.io/ziro/eligibility/ziro-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ziro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Credit
- Lending
- Embedded Finance
- Payments
- Small Business
- Colombia
- Latin America
---
