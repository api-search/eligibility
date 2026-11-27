---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    text: more no brasil, seja registrado no cadastro nacional de pessoas físicas (CPF/MF)
  entity_types:
  - text: Para se cadastrar na plataforma do Enjoei, é necessário que você tenha mais de 18 (dezoito) anos e seja capaz na forma da lei
    type: individual
  minimum_age:
    text: é necessário que você tenha mais de 18 (dezoito) anos e seja capaz na forma da lei
    value: '18'
  restricted_uses:
  - summary: Prohibited product categories
    text: 'São exemplos de produtos que não podem ser vendidos no Enjoei, sob nenhuma hipótese: Armas de fogo, armas brancas ou similares, pólvora ou material explosivo, narcóticos, tóxicos e qualquer sorte de drogas ilegais;'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A qualquer momento, o Enjoei poderá verificar seus dados pessoais, pedindo documentos e comprovantes que confirmem a veracidade das informações do seu cadastro.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Enjoei
provenance_date: '2026-11-09'
provider_name: Enjoei
provider_slug: enjoei
slug: enjoei-eligibility
source_date: '2026-11-09'
source_filename: enjoei-eligibility.yml
source_heading: Eligibility
source_page: https://www.enjoei.com.br/ajuda/sobre-o-enjoei/sobre-os-termos-de-uso/termos-de-uso-do-enjoei
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enjoei\naid: enjoei\nurl: https://www.enjoei.com.br/ajuda/sobre-o-enjoei/sobre-os-termos-de-uso/termos-de-uso-do-enjoei\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BR\n  excluded: []\n  text: more no brasil, seja registrado no cadastro nacional de pessoas físicas (CPF/MF)\nentity_types:\n- type: individual\n  text: Para se cadastrar na plataforma do Enjoei, é necessário que você tenha mais de 18 (dezoito) anos e seja\n    capaz na forma da lei\nrestricted_uses:\n- summary: Prohibited product categories\n  text: 'São exemplos de produtos que não podem ser vendidos no Enjoei, sob nenhuma hipótese: Armas\
  \ de fogo, armas\n    brancas ou similares, pólvora ou material explosivo, narcóticos, tóxicos e qualquer sorte de drogas ilegais;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A qualquer momento, o Enjoei poderá verificar seus dados pessoais, pedindo documentos e comprovantes que\n    confirmem a veracidade das informações do seu cadastro.\nminimum_age:\n  value: '18'\n  text: é necessário que você tenha mais de 18 (dezoito) anos e seja capaz na forma da lei\n"
source_yaml_url: https://artifacts.apis.io/enjoei/eligibility/enjoei-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Enjoei's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Marketplace
- E-Commerce
- Resale
- Secondhand
- Fashion
- Brazil
---
