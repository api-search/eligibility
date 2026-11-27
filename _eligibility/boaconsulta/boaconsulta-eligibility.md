---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: disponibiliza plataforma de gestão para Instituições de Saúde.
    type: business
  minimum_age:
    text: Para utilizar o BoaConsulta, o Parceiro BoaConsulta deve ter pelo menos 18 (dezoito) anos.
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: O BoaConsulta se reserva o direito de solicitar documentos e/ou informações adicionais com o fim de conferir os dados submetidos ao cadastro
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BoaConsulta
provenance_date: '2026-11-09'
provider_name: BoaConsulta
provider_slug: boaconsulta
slug: boaconsulta-eligibility
source_date: '2026-11-09'
source_filename: boaconsulta-eligibility.yml
source_heading: Eligibility
source_page: https://gestao.boaconsulta.com/termos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BoaConsulta\naid: boaconsulta\nurl: https://gestao.boaconsulta.com/termos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: disponibiliza plataforma de gestão para Instituições de Saúde.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: O BoaConsulta se reserva o direito de solicitar documentos e/ou informações adicionais com o fim de conferir\n    os dados submetidos ao cadastro\nminimum_age:\n  value: '18'\n  text: Para utilizar o BoaConsulta, o Parceiro BoaConsulta deve ter pelo menos\
  \ 18 (dezoito) anos.\n"
source_yaml_url: https://artifacts.apis.io/boaconsulta/eligibility/boaconsulta-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from BoaConsulta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Appointment Booking
- Marketplace
- Software-as-a-Service
- Practice Management
- Electronic Health Records
- Brazil
- LGPD
---
