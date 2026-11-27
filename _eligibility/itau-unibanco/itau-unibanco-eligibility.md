---
api_specs:
- filename: itau-unibanco-accounts-api-openapi.yml
  format: yaml
  label: Itaú Unibanco Accounts API
  slug: itau-unibanco-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itau-unibanco/openapi/itau-unibanco-accounts-api-openapi.yml
- filename: itau-unibanco-channels-api-openapi.yml
  format: yaml
  label: Itaú Unibanco Channels API
  slug: itau-unibanco-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itau-unibanco/openapi/itau-unibanco-channels-api-openapi.yml
- filename: itau-unibanco-credit-cards-api-openapi.yml
  format: yaml
  label: Itaú Unibanco Credit Cards API
  slug: itau-unibanco-credit-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itau-unibanco/openapi/itau-unibanco-credit-cards-api-openapi.yml
- filename: itau-unibanco-discovery-api-openapi.yml
  format: yaml
  label: Itaú Unibanco Discovery API
  slug: itau-unibanco-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itau-unibanco/openapi/itau-unibanco-discovery-api-openapi.yml
- filename: itau-unibanco-financings-api-openapi.yml
  format: yaml
  label: Itaú Unibanco Financings API
  slug: itau-unibanco-financings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itau-unibanco/openapi/itau-unibanco-financings-api-openapi.yml
- filename: itau-unibanco-invoice-financings-api-openapi.yml
  format: yaml
  label: Itaú Unibanco Invoice Financings API
  slug: itau-unibanco-invoice-financings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itau-unibanco/openapi/itau-unibanco-invoice-financings-api-openapi.yml
- filename: itau-unibanco-loans-api-openapi.yml
  format: yaml
  label: Itaú Unibanco Loans API
  slug: itau-unibanco-loans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itau-unibanco/openapi/itau-unibanco-loans-api-openapi.yml
- filename: itau-unibanco-unarranged-account-overdraft-api-openapi.yml
  format: yaml
  label: Itaú Unibanco Unarranged Account Overdraft API
  slug: itau-unibanco-unarranged-account-overdraft-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itau-unibanco/openapi/itau-unibanco-unarranged-account-overdraft-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a pessoa física (maior e capaz)
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consumer scoring or credit classification
    text: Utilizar uma API, Conteúdo API e/ou Serviço API, no todo ou em parte, para alterar a classificação ou o conceito de determinado consumidor
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Tal disponibilização será feita exclusivamente a determinados Desenvolvedores previamente selecionados e convidados pelo Itaú Unibanco
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Itaú Unibanco
provenance_date: '2026-11-09'
provider_name: Itaú Unibanco
provider_slug: itau-unibanco
slug: itau-unibanco-eligibility
source_date: '2026-11-09'
source_filename: itau-unibanco-eligibility.yml
source_heading: Eligibility
source_page: https://devportal.itau.com.br/termos-de-uso
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Itaú Unibanco\naid: itau-unibanco\nurl: https://devportal.itau.com.br/termos-de-uso\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: a pessoa física (maior e capaz)\nrestricted_uses:\n- summary: Consumer scoring or credit classification\n  text: Utilizar uma API, Conteúdo API e/ou Serviço API, no todo ou em parte, para alterar a classificação ou o\n    conceito de determinado consumidor\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Tal disponibilização será feita exclusivamente a determinados Desenvolvedores\
  \ previamente selecionados e\n    convidados pelo Itaú Unibanco\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/itau-unibanco/eligibility/itau-unibanco-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Itaú Unibanco's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Financial Services
- Payments
- Pix
- Open Finance
- Brazil
- Foreign Exchange
- Credit
---
