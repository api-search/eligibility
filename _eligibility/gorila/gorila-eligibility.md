---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Por usuários pessoa física (modelo B2C gratuito).
    type: individual
  - text: Por clientes institucionais (modelo B2B);
    type: business
  minimum_age:
    text: O uso por menores de 18 anos exige o consentimento expresso dos responsáveis legais.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A criação de uma Conta Gorila requer o fornecimento de dados verídicos e atualizados
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gorila
provenance_date: '2026-11-09'
provider_name: Gorila
provider_slug: gorila
slug: gorila-eligibility
source_date: '2026-11-09'
source_filename: gorila-eligibility.yml
source_heading: Eligibility
source_page: https://gorila.com.br/termos-de-uso/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gorila\naid: gorila\nurl: https://gorila.com.br/termos-de-uso/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Por usuários pessoa física (modelo B2C gratuito).\n- type: business\n  text: Por clientes institucionais (modelo B2B);\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A criação de uma Conta Gorila requer o fornecimento de dados verídicos e atualizados\nminimum_age:\n  value: '18'\n  text: O uso por menores de 18 anos exige o consentimento expresso dos responsáveis legais.\n"
source_yaml_url: https://artifacts.apis.io/gorila/eligibility/gorila-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Gorila's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Investment
- Portfolio Management
- Wealth Management
- Financial Data
- Investment Consolidation
- Brazil
---
