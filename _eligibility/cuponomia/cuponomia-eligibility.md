---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A plataforma do Cuponomia está disponível exclusivamente para usuários maiores de idade e que gozem de capacidade legal para contratá-lo.
    type: individual
  minimum_age:
    text: A plataforma do Cuponomia está disponível exclusivamente para usuários maiores de idade
    value: adult
  restricted_uses:
  - summary: Commercial or resale use
    text: Seu uso para fins comerciais, incluindo compra de produtos/serviços para revenda, não é válido.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: O CPF informado deve ser autêntico e pertencer ao usuário que está realizando o cadastro.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cuponomia
provenance_date: '2026-11-09'
provider_name: Cuponomia
provider_slug: cuponomia
slug: cuponomia-eligibility
source_date: '2026-11-09'
source_filename: cuponomia-eligibility.yml
source_heading: Eligibility
source_page: https://www.cuponomia.com.br/termos-uso
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cuponomia\naid: cuponomia\nurl: https://www.cuponomia.com.br/termos-uso\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A plataforma do Cuponomia está disponível exclusivamente para usuários maiores de idade e que gozem de capacidade\n    legal para contratá-lo.\nrestricted_uses:\n- summary: Commercial or resale use\n  text: Seu uso para fins comerciais, incluindo compra de produtos/serviços para revenda, não é válido.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: O CPF informado deve ser autêntico e\
  \ pertencer ao usuário que está realizando o cadastro.\nminimum_age:\n  value: adult\n  text: A plataforma do Cuponomia está disponível exclusivamente para usuários maiores de idade\n"
source_yaml_url: https://artifacts.apis.io/cuponomia/eligibility/cuponomia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Cuponomia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coupons
- Cashback
- Discounts
- E-Commerce
- Affiliate Marketing
- Deals
- Brazil
- Consumer
---
