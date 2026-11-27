---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Você deve ser maior de 18 anos e ser legalmente capaz para usar nossos Serviços.
    type: individual
  minimum_age:
    text: Você deve ser maior de 18 anos e ser legalmente capaz para usar nossos Serviços.
    value: '18'
  restricted_uses:
  - summary: Illegal uses
    text: É proibido usar a plataforma para fins ilegais (como lavagem de dinheiro)
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
name: Quinto Andar
provenance_date: '2026-11-10'
provider_name: Quinto Andar
provider_slug: quinto-andar
slug: quinto-andar-eligibility
source_date: '2026-11-10'
source_filename: quinto-andar-eligibility.yml
source_heading: Eligibility
source_page: https://www.quintoandar.com.br/termos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quinto Andar\naid: quinto-andar\nurl: https://www.quintoandar.com.br/termos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Você deve ser maior de 18 anos e ser legalmente capaz para usar nossos Serviços.\nrestricted_uses:\n- summary: Illegal uses\n  text: É proibido usar a plataforma para fins ilegais (como lavagem de dinheiro)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Você deve ser maior de 18 anos e ser legalmente capaz para usar nossos Serviços.\n"
source_yaml_url: https://artifacts.apis.io/quinto-andar/eligibility/quinto-andar-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Quinto Andar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PropTech
- Real Estate
- Marketplace
- Rentals
- Brazil
- Housing
---
