---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: el territorio en el que DEPORPRIVÉ acepta y distribuye pedidos es el comprendido por la República Mexicana
  minimum_age:
    text: dirigido única y exclusivamente a un público mayor de 18 años
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: DEPORPRIVÉ se reserva el derecho a solicitar información, confirmaciones y/o documentos adicionales a los Socios
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DeporPrivé
provenance_date: '2026-11-09'
provider_name: DeporPrivé
provider_slug: deporpriv
slug: deporpriv-eligibility
source_date: '2026-11-09'
source_filename: deporpriv-eligibility.yml
source_heading: Eligibility
source_page: https://www.deporprive.mx/content/2-terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DeporPrivé\naid: deporpriv\nurl: https://www.deporprive.mx/content/2-terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: el territorio en el que DEPORPRIVÉ acepta y distribuye pedidos es el comprendido por la República Mexicana\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: DEPORPRIVÉ se reserva el derecho a solicitar información, confirmaciones y/o documentos adicionales a los\n    Socios\nminimum_age:\n  value: '18'\n  text: dirigido única y exclusivamente a un público mayor de 18 años\n"
source_yaml_url: https://artifacts.apis.io/deporpriv/eligibility/deporpriv-eligibility.yml
stated_fields:
- countries
- verification
- minimum_age
summary_line: 3 quoted statements, read from DeporPrivé's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Sports
- Mexico
- Flash Sales
- Consumer
---
