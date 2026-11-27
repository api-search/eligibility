---
api_specs:
- filename: depixapp-com-account-api-openapi.yml
  format: yaml
  label: DePix App Account API
  slug: depixapp-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-account-api-openapi.yml
- filename: depixapp-com-agents-api-openapi.yml
  format: yaml
  label: DePix App Agents API
  slug: depixapp-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-agents-api-openapi.yml
- filename: depixapp-com-checkouts-api-openapi.yml
  format: yaml
  label: DePix App Checkouts API
  slug: depixapp-com-checkouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-checkouts-api-openapi.yml
- filename: depixapp-com-merchant-api-openapi.yml
  format: yaml
  label: DePix App Merchant API
  slug: depixapp-com-merchant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-merchant-api-openapi.yml
- filename: depixapp-com-meta-api-openapi.yml
  format: yaml
  label: DePix App Meta API
  slug: depixapp-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-meta-api-openapi.yml
- filename: depixapp-com-pay-api-openapi.yml
  format: yaml
  label: DePix App Pay API
  slug: depixapp-com-pay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-pay-api-openapi.yml
- filename: depixapp-com-products-api-openapi.yml
  format: yaml
  label: DePix App Products API
  slug: depixapp-com-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-products-api-openapi.yml
- filename: depixapp-com-public-api-openapi.yml
  format: yaml
  label: DePix App Public API
  slug: depixapp-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-public-api-openapi.yml
- filename: depixapp-com-support-api-openapi.yml
  format: yaml
  label: DePix App Support API
  slug: depixapp-com-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-support-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: é maior de 18 anos e plenamente capaz para os atos da vida civil
    type: individual
  - text: Para o Usuário pessoa jurídica que utilize a Plataforma fora do âmbito do Código de Defesa do Consumidor
    type: business
  minimum_age:
    text: é maior de 18 anos e plenamente capaz para os atos da vida civil
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons
    text: não está sujeito a sanções econômicas nacionais ou internacionais (incluindo listas da ONU, OFAC e União Europeia), nem age por conta de pessoa sancionada
  - summary: Use of third-party accounts or nominees
    text: utilização de contas de terceiros, "laranjas" ou interpostas pessoas
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A identificação do Usuário e a verificação de titularidade ocorrem no âmbito dos Parceiros Bancários
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DePix App
provenance_date: '2026-11-09'
provider_name: DePix App
provider_slug: depixapp-com
slug: depixapp-com-eligibility
source_date: '2026-11-09'
source_filename: depixapp-com-eligibility.yml
source_heading: Eligibility
source_page: https://depixapp.com/termos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DePix App\naid: depixapp-com\nurl: https://depixapp.com/termos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: é maior de 18 anos e plenamente capaz para os atos da vida civil\n- type: business\n  text: Para o Usuário pessoa jurídica que utilize a Plataforma fora do âmbito do Código de Defesa do Consumidor\nrestricted_uses:\n- summary: Sanctioned persons\n  text: não está sujeito a sanções econômicas nacionais ou internacionais (incluindo listas da ONU, OFAC e União\n    Europeia), nem age por conta de pessoa sancionada\n- summary:\
  \ Use of third-party accounts or nominees\n  text: utilização de contas de terceiros, \"laranjas\" ou interpostas pessoas\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A identificação do Usuário e a verificação de titularidade ocorrem no âmbito dos Parceiros Bancários\nminimum_age:\n  value: '18'\n  text: é maior de 18 anos e plenamente capaz para os atos da vida civil\n"
source_yaml_url: https://artifacts.apis.io/depixapp-com/eligibility/depixapp-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from DePix App's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Pix
- Stablecoins
- Cryptocurrency
- Bitcoin
- Liquid Network
- Brazil
- MCP
---
