---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Este Portal tem como base o horário oficial de Brasília.
  entity_types:
  - text: Somente é permitido aos usuários maiores de 18 anos utilizarem a plataforma.
    type: individual
  - text: Em caso de cadastro de pessoa jurídica, deverá ser indicada pessoa física responsável pela conta
    type: business
  minimum_age:
    text: Somente é permitido aos usuários maiores de 18 anos utilizarem a plataforma.
    value: '18'
  restricted_uses:
  - summary: Human use only
    text: Este Portal foi desenvolvido para a utilização por seres humanos
  - summary: No automated spiders or data mining
    text: Neste Portal é proibida a utilização, de aplicativos spider, ou de mineração de dados, de qualquer tipo ou espécie
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
name: QueroQuitar
provenance_date: '2026-11-10'
provider_name: QueroQuitar
provider_slug: queroquitar
slug: queroquitar-eligibility
source_date: '2026-11-10'
source_filename: queroquitar-eligibility.yml
source_heading: Eligibility
source_page: https://www.queroquitar.com.br/termos-de-uso/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: QueroQuitar\naid: queroquitar\nurl: https://www.queroquitar.com.br/termos-de-uso/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Este Portal tem como base o horário oficial de Brasília.\nentity_types:\n- type: individual\n  text: Somente é permitido aos usuários maiores de 18 anos utilizarem a plataforma.\n- type: business\n  text: Em caso de cadastro de pessoa jurídica, deverá ser indicada pessoa física responsável pela conta\nrestricted_uses:\n- summary: Human use only\n  text: Este Portal foi desenvolvido para a utilização por seres humanos\n- summary: No automated spiders or\
  \ data mining\n  text: Neste Portal é proibida a utilização, de aplicativos spider, ou de mineração de dados, de qualquer tipo\n    ou espécie\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Somente é permitido aos usuários maiores de 18 anos utilizarem a plataforma.\n"
source_yaml_url: https://artifacts.apis.io/queroquitar/eligibility/queroquitar-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from QueroQuitar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Debt Negotiation
- Debt Settlement
- Financial Services
- Consumer Finance
- Brazil
---
