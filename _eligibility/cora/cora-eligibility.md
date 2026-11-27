---
api_specs:
- filename: cora-balance-api-openapi.yml
  format: yaml
  label: Cora Balance API
  slug: cora-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-balance-api-openapi.yml
- filename: cora-banks-api-openapi.yml
  format: yaml
  label: Cora Banks API
  slug: cora-banks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-banks-api-openapi.yml
- filename: cora-boletos-v2-api-openapi.yml
  format: yaml
  label: Cora Boletos V2 API
  slug: cora-boletos-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-boletos-v2-api-openapi.yml
- filename: cora-businesses-api-openapi.yml
  format: yaml
  label: Cora Businesses API
  slug: cora-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-businesses-api-openapi.yml
- filename: cora-credentials-api-openapi.yml
  format: yaml
  label: Cora Credentials API
  slug: cora-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-credentials-api-openapi.yml
- filename: cora-dados-de-conta-api-openapi.yml
  format: yaml
  label: Cora Dados De Conta API
  slug: cora-dados-de-conta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-dados-de-conta-api-openapi.yml
- filename: cora-initiate-api-openapi.yml
  format: yaml
  label: Cora Initiate API
  slug: cora-initiate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-initiate-api-openapi.yml
- filename: cora-issuer-api-openapi.yml
  format: yaml
  label: Cora Issuer API
  slug: cora-issuer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-issuer-api-openapi.yml
- filename: cora-notifica-es-api-openapi.yml
  format: yaml
  label: Cora Notificações API
  slug: cora-notifica-es-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-notifica-es-api-openapi.yml
- filename: cora-notifications-api-openapi.yml
  format: yaml
  label: Cora Notifications API
  slug: cora-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-notifications-api-openapi.yml
- filename: cora-pagamento-de-impostos-api-openapi.yml
  format: yaml
  label: Cora Pagamento De Impostos API
  slug: cora-pagamento-de-impostos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-pagamento-de-impostos-api-openapi.yml
- filename: cora-pay-api-openapi.yml
  format: yaml
  label: Cora Pay API
  slug: cora-pay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-pay-api-openapi.yml
- filename: cora-service-receipt-api-openapi.yml
  format: yaml
  label: Cora Service Receipt API
  slug: cora-service-receipt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-service-receipt-api-openapi.yml
- filename: cora-statement-api-openapi.yml
  format: yaml
  label: Cora Statement API
  slug: cora-statement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cora/openapi/cora-statement-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ser Empresa nos termos definidos nos Termos de Uso como “Sua Empresa”, com cadastro ativo
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No BaaS or intermediated financial services
    text: as APIs não constituem infraestrutura de Banking as a Service (BaaS), plataforma transacional para terceiros
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
name: Cora
provenance_date: '2026-11-09'
provider_name: Cora
provider_slug: cora
slug: cora-eligibility
source_date: '2026-11-09'
source_filename: cora-eligibility.yml
source_heading: Eligibility
source_page: https://www.cora.com.br/termos-e-condicoes-de-apis/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cora\naid: cora\nurl: https://www.cora.com.br/termos-e-condicoes-de-apis/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: ser Empresa nos termos definidos nos Termos de Uso como “Sua Empresa”, com cadastro ativo\nrestricted_uses:\n- summary: No BaaS or intermediated financial services\n  text: as APIs não constituem infraestrutura de Banking as a Service (BaaS), plataforma transacional para terceiros\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cora/eligibility/cora-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Cora's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Brazil
- Payments
- Pix
- Boleto
- Invoicing
- Small Business
- Fintech
- Banking as a Service
---
