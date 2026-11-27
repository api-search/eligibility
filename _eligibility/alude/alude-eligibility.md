---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: pessoa física ou jurídica, identificada na ficha cadastral
    type: individual
  - text: Se o Usuário for pessoa jurídica, seus funcionários poderão ter acesso ao Sistema
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal or harmful uso
    text: O Usuário não pode utilizar o Sistema para infringir a legislação brasileira, para causar danos a terceiros
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
name: Alude
provenance_date: '2026-11-09'
provider_name: Alude
provider_slug: alude
slug: alude-eligibility
source_date: '2026-11-09'
source_filename: alude-eligibility.yml
source_heading: Eligibility
source_page: https://www.alude.com.br/termos-de-uso-de-politica-de-privacidade-e-de-tratamento-de-dados-pessoais.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alude\naid: alude\nurl: https://www.alude.com.br/termos-de-uso-de-politica-de-privacidade-e-de-tratamento-de-dados-pessoais.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: pessoa física ou jurídica, identificada na ficha cadastral\n- type: business\n  text: Se o Usuário for pessoa jurídica, seus funcionários poderão ter acesso ao Sistema\nrestricted_uses:\n- summary: No illegal or harmful uso\n  text: O Usuário não pode utilizar o Sistema para infringir a legislação brasileira, para causar danos a terceiros\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alude/eligibility/alude-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Alude's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Software-as-a-Service
- Property Management
- Rental Management
- E-Signature
- Insurance
- Brazil
- Fintech
---
