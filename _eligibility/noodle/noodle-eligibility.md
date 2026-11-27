---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: para pessoa física, no mínimo, nome completo e número de inscrição no CPF/MF válido e ativo
    type: individual
  - text: 'no caso de pessoa jurídica, deverão ser fornecidos: razão social ou denominação, número de inscrição no CNPJ/MF válido e ativo'
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: bem como o envio de documentos que permitam a confirmação dos dados fornecidos pelo USUÁRIO
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Noodle
provenance_date: '2026-11-10'
provider_name: Noodle
provider_slug: noodle
slug: noodle-eligibility
source_date: '2026-11-10'
source_filename: noodle-eligibility.yml
source_heading: Eligibility
source_page: https://storage.googleapis.com/noodleproduction-paginas-publicas/politica-de-privacidade
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Noodle\naid: noodle\nurl: https://storage.googleapis.com/noodleproduction-paginas-publicas/politica-de-privacidade\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: para pessoa física, no mínimo, nome completo e número de inscrição no CPF/MF válido e ativo\n- type: business\n  text: 'no caso de pessoa jurídica, deverão ser fornecidos: razão social ou denominação, número de inscrição no\n    CNPJ/MF válido e ativo'\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: bem como o envio de documentos\
  \ que permitam a confirmação dos dados fornecidos pelo USUÁRIO\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/noodle/eligibility/noodle-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from Noodle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Payouts
- Creator Economy
- Brazil
- Foreign Exchange
- Financial Services
---
