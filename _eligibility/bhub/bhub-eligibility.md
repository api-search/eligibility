---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Os nossos sites/aplicativos/plataformas são direcionados apenas a pessoas maiores de 18 anos.
    type: individual
  - text: Caso esteja acessando, usando ou, de qualquer outra forma, interagindo com os nossos ambientes em nome de alguma organização, o usuário declara, desde já, possuir todos os poderes legais para vincular a referida organização
    type: business
  minimum_age:
    text: Os nossos sites/aplicativos/plataformas são direcionados apenas a pessoas maiores de 18 anos.
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
name: Bhub
provenance_date: '2026-11-09'
provider_name: Bhub
provider_slug: bhub
slug: bhub-eligibility
source_date: '2026-11-09'
source_filename: bhub-eligibility.yml
source_heading: Eligibility
source_page: https://bhub.com/termos-e-condicoes-de-uso/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bhub\naid: bhub\nurl: https://bhub.com/termos-e-condicoes-de-uso/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Os nossos sites/aplicativos/plataformas são direcionados apenas a pessoas maiores de 18 anos.\n- type: business\n  text: Caso esteja acessando, usando ou, de qualquer outra forma, interagindo com os nossos ambientes em nome de\n    alguma organização, o usuário declara, desde já, possuir todos os poderes legais para vincular a referida organização\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Os nossos sites/aplicativos/plataformas são direcionados apenas a pessoas maiores de 18 anos.\n"
source_yaml_url: https://artifacts.apis.io/bhub/eligibility/bhub-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Bhub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Accounting
- BPO
- Brazil
- Tax
- Small Business
- Financial Services
---
