---
api_specs:
- filename: cloudwalk-checkout-links-api-openapi.yml
  format: yaml
  label: CloudWalk Checkout Links API
  slug: cloudwalk-checkout-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudwalk/openapi/cloudwalk-checkout-links-api-openapi.yml
- filename: cloudwalk-infinitepay-checkout-api-api-openapi.yml
  format: yaml
  label: CloudWalk InfinitePay Checkout API
  slug: cloudwalk-infinitepay-checkout-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudwalk/openapi/cloudwalk-infinitepay-checkout-api-api-openapi.yml
- filename: cloudwalk-payments-api-openapi.yml
  format: yaml
  label: CloudWalk Payments API
  slug: cloudwalk-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudwalk/openapi/cloudwalk-payments-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Ao realizar o cadastro, o usuário declara ser maior de idade e civilmente capaz.
    type: individual
  minimum_age:
    text: Ao realizar o cadastro, o usuário declara ser maior de idade e civilmente capaz.
    value: null
  restricted_uses:
  - summary: Unlicensed financial or payment services
    text: Realização de prestação de serviços que configurem serviços financeiros e/ou de pagamentos sem que o Cliente possua as referidas autorizações para tanto
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: a INFINITEPAY realiza procedimentos de identificação e qualificação do usuário, mediante coleta e verificação de dados cadastrais, consulta e cruzamento de informações com bases de dados públicas e privadas e análise facial para validação de identidade
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CloudWalk
provenance_date: '2026-11-09'
provider_name: CloudWalk
provider_slug: cloudwalk
slug: cloudwalk-eligibility
source_date: '2026-11-09'
source_filename: cloudwalk-eligibility.yml
source_heading: Eligibility
source_page: https://www.infinitepay.io/legal/termos-de-uso
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CloudWalk\naid: cloudwalk\nurl: https://www.infinitepay.io/legal/termos-de-uso\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Ao realizar o cadastro, o usuário declara ser maior de idade e civilmente capaz.\nrestricted_uses:\n- summary: Unlicensed financial or payment services\n  text: Realização de prestação de serviços que configurem serviços financeiros e/ou de pagamentos sem que o Cliente\n    possua as referidas autorizações para tanto\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text:\
  \ a INFINITEPAY realiza procedimentos de identificação e qualificação do usuário, mediante coleta e verificação\n    de dados cadastrais, consulta e cruzamento de informações com bases de dados públicas e privadas e análise facial\n    para validação de identidade\nminimum_age:\n  value: null\n  text: Ao realizar o cadastro, o usuário declara ser maior de idade e civilmente capaz.\n"
source_yaml_url: https://artifacts.apis.io/cloudwalk/eligibility/cloudwalk-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from CloudWalk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Financial Services
- Fintech
- Checkout
- Point-of-Sale
- Acquiring
- Pix
- Brazil
- Banking
- Webhook
- Tap to Pay
---
