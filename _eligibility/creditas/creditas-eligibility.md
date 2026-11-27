---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Caso você esteja usufruindo de nossos serviços fora do Brasil, você será responsável pelo cumprimento das leis locais
  entity_types:
  - text: Ao aceitar as disposições deste Termo, você declara expressamente que domina a língua portuguesa, está familiarizado com o ambiente da Plataforma, possui capacidade civil
    type: individual
  minimum_age:
    text: 'Você declara expressamente ter, no mínimo: (i) 18 (dezoito) anos de idade; ou (ii) 16 (dezesseis) anos de idade, desde que seja emancipado ou esteja sob supervisão e autorização de seu responsável legal.'
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent activity
    text: Praticar qualquer tipo de fraude; e
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: A Creditas poderá negar ou cancelar o cadastro do usuário
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Creditas
provenance_date: '2026-11-09'
provider_name: Creditas
provider_slug: creditas
slug: creditas-eligibility
source_date: '2026-11-09'
source_filename: creditas-eligibility.yml
source_heading: Eligibility
source_page: https://www.creditas.com/legal/termos-condicoes
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Creditas\naid: creditas\nurl: https://www.creditas.com/legal/termos-condicoes\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Caso você esteja usufruindo de nossos serviços fora do Brasil, você será responsável pelo cumprimento das\n    leis locais\nentity_types:\n- type: individual\n  text: Ao aceitar as disposições deste Termo, você declara expressamente que domina a língua portuguesa, está familiarizado\n    com o ambiente da Plataforma, possui capacidade civil\nrestricted_uses:\n- summary: Illegal or fraudulent activity\n  text: Praticar qualquer tipo de fraude; e\nverification:\n\
  \  kyc: true\n  kyb: null\n  approval_required: null\n  text: A Creditas poderá negar ou cancelar o cadastro do usuário\nminimum_age:\n  value: '18'\n  text: 'Você declara expressamente ter, no mínimo: (i) 18 (dezoito) anos de idade; ou (ii) 16 (dezesseis) anos\n    de idade, desde que seja emancipado ou esteja sob supervisão e autorização de seu responsável legal.'\n"
source_yaml_url: https://artifacts.apis.io/creditas/eligibility/creditas-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Creditas's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Credit
- Fintech
- Lending
- Brazil
- Insurance
- Financial Services
- Payroll Loans
---
