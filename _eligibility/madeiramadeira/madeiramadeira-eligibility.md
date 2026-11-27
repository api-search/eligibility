---
api_specs:
- filename: madeiramadeira-callbacks-api-openapi.yml
  format: yaml
  label: Madeiramadeira Callbacks API
  slug: madeiramadeira-callbacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/madeiramadeira/openapi/madeiramadeira-callbacks-api-openapi.yml
- filename: madeiramadeira-categorias-api-openapi.yml
  format: yaml
  label: Madeiramadeira Categorias API
  slug: madeiramadeira-categorias-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/madeiramadeira/openapi/madeiramadeira-categorias-api-openapi.yml
- filename: madeiramadeira-financeiro-api-openapi.yml
  format: yaml
  label: Madeiramadeira Financeiro API
  slug: madeiramadeira-financeiro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/madeiramadeira/openapi/madeiramadeira-financeiro-api-openapi.yml
- filename: madeiramadeira-frete-api-openapi.yml
  format: yaml
  label: Madeiramadeira Frete API
  slug: madeiramadeira-frete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/madeiramadeira/openapi/madeiramadeira-frete-api-openapi.yml
- filename: madeiramadeira-mensageria-api-openapi.yml
  format: yaml
  label: Madeiramadeira Mensageria API
  slug: madeiramadeira-mensageria-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/madeiramadeira/openapi/madeiramadeira-mensageria-api-openapi.yml
- filename: madeiramadeira-pedido-api-openapi.yml
  format: yaml
  label: Madeiramadeira Pedido API
  slug: madeiramadeira-pedido-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/madeiramadeira/openapi/madeiramadeira-pedido-api-openapi.yml
- filename: madeiramadeira-produtos-api-openapi.yml
  format: yaml
  label: Madeiramadeira Produtos API
  slug: madeiramadeira-produtos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/madeiramadeira/openapi/madeiramadeira-produtos-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Qualquer pessoa, física ou jurídica, que visita o Marketplace na condição de comprador, podendo realizar o devido cadastro para realização de compras.
    type: individual
  - text: No caso de Comprador ser pessoa jurídica, a entrega só poderá ser realizada no endereço cadastrado como sede ou filial no Cadastro Nacional de Pessoas Jurídicas.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Madeiramadeira
provenance_date: '2026-11-10'
provider_name: Madeiramadeira
provider_slug: madeiramadeira
slug: madeiramadeira-eligibility
source_date: '2026-11-10'
source_filename: madeiramadeira-eligibility.yml
source_heading: Eligibility
source_page: https://www.madeiramadeira.com.br/termos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Madeiramadeira\naid: madeiramadeira\nurl: https://www.madeiramadeira.com.br/termos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Qualquer pessoa, física ou jurídica, que visita o Marketplace na condição de comprador, podendo realizar\n    o devido cadastro para realização de compras.\n- type: business\n  text: No caso de Comprador ser pessoa jurídica, a entrega só poderá ser realizada no endereço cadastrado como\n    sede ou filial no Cadastro Nacional de Pessoas Jurídicas.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/madeiramadeira/eligibility/madeiramadeira-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Madeiramadeira's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Marketplace
- Retail
- Home Goods
- Furniture
- Brazil
- Seller Integration
- Product Catalog
- Order
- Shipping
- Logistics
---
