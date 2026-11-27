---
api_specs:
- filename: nuvemshop-tiendanube-events-asyncapi.yml
  format: yaml
  label: Nuvemshop Tiendanube API
  slug: nuvemshop-tiendanube-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/nuvemshop-tiendanube/asyncapi/nuvemshop-tiendanube-events-asyncapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Pessoas físicas devem ter 18 anos ou mais
    type: individual
  - text: Pessoas jurídicas devem ter um CNPJ válido e um representante legal autorizado para firmar contratos
    type: business
  minimum_age:
    text: Pessoas físicas devem ter 18 anos ou mais
    value: '18'
  restricted_uses:
  - summary: Compliance with law
    text: A atividade comercial deve estar em conformidade com a legislação vigente
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: alguns serviços, como Nuvem Pago e Nuvem Envio , possuem critérios adicionais de análise e aprovação.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nuvemshop Tiendanube
provenance_date: '2026-11-10'
provider_name: Nuvemshop Tiendanube
provider_slug: nuvemshop-tiendanube
slug: nuvemshop-tiendanube-eligibility
source_date: '2026-11-10'
source_filename: nuvemshop-tiendanube-eligibility.yml
source_heading: Eligibility
source_page: https://www.nuvemshop.com.br/termos-de-uso
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nuvemshop Tiendanube\naid: nuvemshop-tiendanube\nurl: https://www.nuvemshop.com.br/termos-de-uso\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Pessoas físicas devem ter 18 anos ou mais\n- type: business\n  text: Pessoas jurídicas devem ter um CNPJ válido e um representante legal autorizado para firmar contratos\nrestricted_uses:\n- summary: Compliance with law\n  text: A atividade comercial deve estar em conformidade com a legislação vigente\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: alguns serviços,\
  \ como Nuvem Pago e Nuvem Envio , possuem critérios adicionais de análise e aprovação.\nminimum_age:\n  value: '18'\n  text: Pessoas físicas devem ter 18 anos ou mais\n"
source_yaml_url: https://artifacts.apis.io/nuvemshop-tiendanube/eligibility/nuvemshop-tiendanube-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Nuvemshop Tiendanube's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Online Store
- Payments
- Shipping
- Webhook
- OAuth
- Latin America
- Storefront
- Apps Platform
- Authentication
---
