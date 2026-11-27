---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - CL
    - CO
    - MX
    - PE
    - EC
    - AR
    text: Para usuarios en Chile... Para usuarios en Colombia... Para usuarios en México... Para usuarios en Perú... Para usuarios en Ecuador... Para usuarios en Argentina
  entity_types:
  - text: Siempre que en estos Términos se haga referencia al “Usuario” se entenderá por tal a cualquier persona natural que sea estudiante, egresado o titulado de programas de pregrado o postgrado
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Firstjob.me
provenance_date: '2026-11-09'
provider_name: Firstjob.me
provider_slug: firstjobme
slug: firstjobme-eligibility
source_date: '2026-11-09'
source_filename: firstjobme-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.firstjob.me/terminos-de-uso-y-condiciones.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Firstjob.me\naid: firstjobme\nurl: https://cdn.firstjob.me/terminos-de-uso-y-condiciones.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CL\n  - CO\n  - MX\n  - PE\n  - EC\n  - AR\n  excluded: []\n  text: Para usuarios en Chile... Para usuarios en Colombia... Para usuarios en México... Para usuarios en Perú...\n    Para usuarios en Ecuador... Para usuarios en Argentina\nentity_types:\n- type: individual\n  text: Siempre que en estos Términos se haga referencia al “Usuario” se entenderá por tal a cualquier persona natural\n    que sea estudiante, egresado o titulado de programas de pregrado o postgrado\n\
  restricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/firstjobme/eligibility/firstjobme-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Firstjob.me's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Job
- Recruiting
- Employment
- Careers
- Internships
- Human Resources
- Latin America
- Chile
---
