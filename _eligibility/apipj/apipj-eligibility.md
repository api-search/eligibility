---
api_specs:
- filename: apipj-billing-api-openapi.yml
  format: yaml
  label: apipj (MASTER BI TECNOLOGIA LTDA) Billing API
  slug: apipj-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apipj/openapi/apipj-billing-api-openapi.yml
- filename: apipj-chaves-api-openapi.yml
  format: yaml
  label: apipj (MASTER BI TECNOLOGIA LTDA) Chaves API
  slug: apipj-chaves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apipj/openapi/apipj-chaves-api-openapi.yml
- filename: apipj-consulta-api-openapi.yml
  format: yaml
  label: apipj (MASTER BI TECNOLOGIA LTDA) Consulta API
  slug: apipj-consulta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apipj/openapi/apipj-consulta-api-openapi.yml
- filename: apipj-conta-api-openapi.yml
  format: yaml
  label: apipj (MASTER BI TECNOLOGIA LTDA) Conta API
  slug: apipj-conta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apipj/openapi/apipj-conta-api-openapi.yml
- filename: apipj-interno-api-openapi.yml
  format: yaml
  label: apipj (MASTER BI TECNOLOGIA LTDA) Interno API
  slug: apipj-interno-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apipj/openapi/apipj-interno-api-openapi.yml
- filename: apipj-p-blico-api-openapi.yml
  format: yaml
  label: apipj (MASTER BI TECNOLOGIA LTDA) Público API
  slug: apipj-p-blico-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apipj/openapi/apipj-p-blico-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: O Serviço destina-se a pessoas maiores de 18 anos e a pessoas jurídicas, por meio de representante autorizado.
    type: individual
  - text: O Serviço destina-se a pessoas maiores de 18 anos e a pessoas jurídicas, por meio de representante autorizado.
    type: business
  minimum_age:
    text: O Serviço destina-se a pessoas maiores de 18 anos
    value: '18'
  restricted_uses:
  - summary: Mass messaging without legal basis
    text: (k) usar os resultados para disparo de mensagens em massa (e-mail, SMS, WhatsApp, ligação automatizada) sem base legal própria e sem respeitar a oposição do destinatário
  - summary: Profiling or discriminatory decisions
    text: (l) montar perfis de pessoas físicas ou usar os dados para decisões discriminatórias
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Podemos exigir verificação adicional (por exemplo, confirmação do e-mail ou informação de CPF/CNPJ) e recusar ou encerrar cadastros feitos com e-mail descartável
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: apipj (MASTER BI TECNOLOGIA LTDA)
provenance_date: '2026-11-09'
provider_name: apipj (MASTER BI TECNOLOGIA LTDA)
provider_slug: apipj
slug: apipj-eligibility
source_date: '2026-11-09'
source_filename: apipj-eligibility.yml
source_heading: Eligibility
source_page: https://apipj.com.br/termos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: apipj (MASTER BI TECNOLOGIA LTDA)\naid: apipj\nurl: https://apipj.com.br/termos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: O Serviço destina-se a pessoas maiores de 18 anos e a pessoas jurídicas, por meio de representante autorizado.\n- type: business\n  text: O Serviço destina-se a pessoas maiores de 18 anos e a pessoas jurídicas, por meio de representante autorizado.\nrestricted_uses:\n- summary: Mass messaging without legal basis\n  text: (k) usar os resultados para disparo de mensagens em massa (e-mail, SMS, WhatsApp, ligação\
  \ automatizada)\n    sem base legal própria e sem respeitar a oposição do destinatário\n- summary: Profiling or discriminatory decisions\n  text: (l) montar perfis de pessoas físicas ou usar os dados para decisões discriminatórias\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Podemos exigir verificação adicional (por exemplo, confirmação do e-mail ou informação de CPF/CNPJ) e recusar\n    ou encerrar cadastros feitos com e-mail descartável\nminimum_age:\n  value: '18'\n  text: O Serviço destina-se a pessoas maiores de 18 anos\n"
source_yaml_url: https://artifacts.apis.io/apipj/eligibility/apipj-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from apipj (MASTER BI TECNOLOGIA LTDA)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Brazil
- CNPJ
- Registry
- Public APIs
---
