---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    text: cadastros de proteção de crédito disponíveis no Brasil
  entity_types:
  - text: Garante ser plenamente capaz de contratar os serviços da QUERO ou estar devidamente autorizado pelos seus responsáveis legais
    type: individual
  minimum_age:
    text: Garante ser plenamente capaz de contratar os serviços da QUERO ou estar devidamente autorizado pelos seus responsáveis legais
    value: null
  restricted_uses:
  - summary: Fraud in selection process
    text: O Usuário candidato é único e exclusivo responsável civil e criminalmente por toda e qualquer fraude e/ou falsidade ideológica no âmbito do processo seletivo digital
  - summary: Unlawful or harmful content
    text: 'O Usuário não poderá enviar, via Plataforma, qualquer conteúdo que:'
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
name: Quero Educação
provenance_date: '2026-11-10'
provider_name: Quero Educação
provider_slug: quero-educa-o
slug: quero-educa-o-eligibility
source_date: '2026-11-10'
source_filename: quero-educa-o-eligibility.yml
source_heading: Eligibility
source_page: https://querobolsa.com.br/ajuda/termos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quero Educação\naid: quero-educa-o\nurl: https://querobolsa.com.br/ajuda/termos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BR\n  excluded: []\n  text: cadastros de proteção de crédito disponíveis no Brasil\nentity_types:\n- type: individual\n  text: Garante ser plenamente capaz de contratar os serviços da QUERO ou estar devidamente autorizado pelos seus\n    responsáveis legais\nrestricted_uses:\n- summary: Fraud in selection process\n  text: O Usuário candidato é único e exclusivo responsável civil e criminalmente por toda e qualquer fraude e/ou\n    falsidade ideológica no âmbito do processo seletivo\
  \ digital\n- summary: Unlawful or harmful content\n  text: 'O Usuário não poderá enviar, via Plataforma, qualquer conteúdo que:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Garante ser plenamente capaz de contratar os serviços da QUERO ou estar devidamente autorizado pelos seus\n    responsáveis legais\n"
source_yaml_url: https://artifacts.apis.io/quero-educa-o/eligibility/quero-educa-o-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Quero Educação's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- Marketplace
- Brazil
- Scholarships
- Higher Education
- Enrollment
---
