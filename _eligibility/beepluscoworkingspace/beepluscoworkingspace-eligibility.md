---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: O (A) CONTRATANTE é a pessoa física ou jurídica adquirente de um plano do BeePlus
    type: individual
  - text: No caso de pessoa jurídica, essa possuirá um representante designado no próprio cadastro, responsável pelo CONTRATO.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: Utilizar os serviços e o conteúdo disponibilizado pelo sítio do BeePlus somente para fins lícitos, com estrita observância ao presente instrumento e à legislação em vigor
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Considera-se CLIENTE regularmente cadastrado todo usuário que estiver dentro das condições estabelecidas pelo BeePlus e seu cadastro previamente aprovado.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Beepluscoworkingspace
provenance_date: '2026-11-09'
provider_name: Beepluscoworkingspace
provider_slug: beepluscoworkingspace
slug: beepluscoworkingspace-eligibility
source_date: '2026-11-09'
source_filename: beepluscoworkingspace-eligibility.yml
source_heading: Eligibility
source_page: https://beeplus.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beepluscoworkingspace\naid: beepluscoworkingspace\nurl: https://beeplus.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: O (A) CONTRATANTE é a pessoa física ou jurídica adquirente de um plano do BeePlus\n- type: business\n  text: No caso de pessoa jurídica, essa possuirá um representante designado no próprio cadastro, responsável pelo\n    CONTRATO.\nrestricted_uses:\n- summary: Lawful use only\n  text: Utilizar os serviços e o conteúdo disponibilizado pelo sítio do BeePlus somente para fins lícitos, com estrita\n    observância\
  \ ao presente instrumento e à legislação em vigor\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Considera-se CLIENTE regularmente cadastrado todo usuário que estiver dentro das condições estabelecidas\n    pelo BeePlus e seu cadastro previamente aprovado.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/beepluscoworkingspace/eligibility/beepluscoworkingspace-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Beepluscoworkingspace's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agile
- Management
- Software-as-a-Service
- Brazil
---
