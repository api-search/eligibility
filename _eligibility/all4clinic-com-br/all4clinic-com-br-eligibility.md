---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    text: Feito no Brasil, para clínicas brasileiras.
  entity_types:
  - text: Você afirma que tem pelo menos 18 anos de idade e está autorizado legalmente a usar o All4Clinic em sua clínica, consultório ou prática médica.
    type: individual
  minimum_age:
    text: Você afirma que tem pelo menos 18 anos de idade
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
name: All4Clinic
provenance_date: '2026-11-09'
provider_name: All4Clinic
provider_slug: all4clinic-com-br
slug: all4clinic-com-br-eligibility
source_date: '2026-11-09'
source_filename: all4clinic-com-br-eligibility.yml
source_heading: Eligibility
source_page: https://all4clinic.com.br/termos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: All4Clinic\naid: all4clinic-com-br\nurl: https://all4clinic.com.br/termos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BR\n  excluded: []\n  text: Feito no Brasil, para clínicas brasileiras.\nentity_types:\n- type: individual\n  text: Você afirma que tem pelo menos 18 anos de idade e está autorizado legalmente a usar o All4Clinic em sua\n    clínica, consultório ou prática médica.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Você afirma que tem pelo menos 18 anos de idade\n"
source_yaml_url: https://artifacts.apis.io/all4clinic-com-br/eligibility/all4clinic-com-br-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from All4Clinic's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Clinic Management
- Artificial Intelligence
- Brazil
- Software-as-a-Service
---
