---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: son aplicables exclusivamente dentro de los Estados Unidos Mexicanos
  entity_types:
  - text: Las Usuarias declaran contar con capacidad legal para contratar, de conformidad con la legislación aplicable.
    type: individual
  minimum_age:
    text: A partir de los 18 (dieciocho) años, el beneficiario podrá utilizar los Servicios de manera directa e independiente.
    value: '18'
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
name: Plenna
provenance_date: '2026-11-10'
provider_name: Plenna
provider_slug: plenna
slug: plenna-eligibility
source_date: '2026-11-10'
source_filename: plenna-eligibility.yml
source_heading: Eligibility
source_page: https://soyplenna.com/footer/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plenna\naid: plenna\nurl: https://soyplenna.com/footer/terminos-y-condiciones\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: son aplicables exclusivamente dentro de los Estados Unidos Mexicanos\nentity_types:\n- type: individual\n  text: Las Usuarias declaran contar con capacidad legal para contratar, de conformidad con la legislación aplicable.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: A partir de los 18 (dieciocho) años, el beneficiario podrá utilizar los\
  \ Servicios de manera directa e independiente.\n"
source_yaml_url: https://artifacts.apis.io/plenna/eligibility/plenna-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Plenna's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Women's Health
- Femtech
- Telehealth
- Medical Clinics
- Mexico
- Digital Health
---
