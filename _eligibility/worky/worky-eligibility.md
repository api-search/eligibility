---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Se considera como CLIENTE aquella persona física o moral que contrate los servicios ofrecidos por WORKY.
    type: business
  - text: Se considera un Usuario a cualquier persona física, que tenga o no tenga una relación directa o indirecta con EL CLIENTE
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or contrary use
    text: las consecuencias que se puedan derivar de una utilización, con fines o efectos ilícitos o contrarios al presente documento
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
name: Worky
provenance_date: '2026-11-10'
provider_name: Worky
provider_slug: worky
slug: worky-eligibility
source_date: '2026-11-10'
source_filename: worky-eligibility.yml
source_heading: Eligibility
source_page: https://www.worky.mx/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Worky\naid: worky\nurl: https://www.worky.mx/terminos-y-condiciones\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Se considera como CLIENTE aquella persona física o moral que contrate los servicios ofrecidos por WORKY.\n- type: individual\n  text: Se considera un Usuario a cualquier persona física, que tenga o no tenga una relación directa o indirecta\n    con EL CLIENTE\nrestricted_uses:\n- summary: Unlawful or contrary use\n  text: las consecuencias que se puedan derivar de una utilización, con fines o efectos ilícitos o contrarios\
  \ al\n    presente documento\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/worky/eligibility/worky-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Worky's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payroll
- Human Resources
- Mexico
- CFDI
- Attendance
- Recruiting
- Benefits
- Artificial Intelligence
---
