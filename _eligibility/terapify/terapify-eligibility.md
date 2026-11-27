---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Al ingresar al sitio web, el usuario declara ser mayor de 18 años
    value: '18'
  restricted_uses:
  - summary: Emergency medical use
    text: No utilice el sitio web para necesidades médicas de emergencia.
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
name: Terapify
provenance_date: '2026-11-10'
provider_name: Terapify
provider_slug: terapify
slug: terapify-eligibility
source_date: '2026-11-10'
source_filename: terapify-eligibility.yml
source_heading: Eligibility
source_page: https://www.terapify.com:443/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Terapify\naid: terapify\nurl: https://www.terapify.com:443/terminos-y-condiciones\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Emergency medical use\n  text: No utilice el sitio web para necesidades médicas de emergencia.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Al ingresar al sitio web, el usuario declara ser mayor de 18 años\n"
source_yaml_url: https://artifacts.apis.io/terapify/eligibility/terapify-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Terapify's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mental Health
- Therapy
- Telehealth
- Healthcare
- Psychology
- Wellness
- Mexico
---
