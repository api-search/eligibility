---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    text: oferecer seguros pessoais por um preço justo para todos os brasileiros
  entity_types:
  - text: Como condição de utilização dos serviços da nossa plataforma, você precisa ter 18 (dezoito) anos ou mais.
    type: individual
  minimum_age:
    text: Como condição de utilização dos serviços da nossa plataforma, você precisa ter 18 (dezoito) anos ou mais.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: Você não pode utilizar nossos serviços ou produtos para qualquer finalidade ilegal ou não autorizada.
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
name: Azos
provenance_date: '2026-11-09'
provider_name: Azos
provider_slug: azos
slug: azos-eligibility
source_date: '2026-11-09'
source_filename: azos-eligibility.yml
source_heading: Eligibility
source_page: https://www.azos.com.br/termos-de-uso
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Azos\naid: azos\nurl: https://www.azos.com.br/termos-de-uso\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BR\n  excluded: []\n  text: oferecer seguros pessoais por um preço justo para todos os brasileiros\nentity_types:\n- type: individual\n  text: Como condição de utilização dos serviços da nossa plataforma, você precisa ter 18 (dezoito) anos ou mais.\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: Você não pode utilizar nossos serviços ou produtos para qualquer finalidade ilegal ou não autorizada.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: Como condição de utilização dos serviços da nossa plataforma, você precisa ter 18 (dezoito) anos ou mais.\n"
source_yaml_url: https://artifacts.apis.io/azos/eligibility/azos-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Azos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Insurance
- Insurtech
- Life Insurance
- Brazil
- Financial Services
- Digital Insurance
---
