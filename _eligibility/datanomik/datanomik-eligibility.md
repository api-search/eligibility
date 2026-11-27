---
api_specs:
- filename: datanomik-accounts-api-openapi.yml
  format: yaml
  label: Datanomik Accounts API
  slug: datanomik-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datanomik/openapi/datanomik-accounts-api-openapi.yml
- filename: datanomik-applications-api-openapi.yml
  format: yaml
  label: Datanomik Applications API
  slug: datanomik-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datanomik/openapi/datanomik-applications-api-openapi.yml
- filename: datanomik-balances-api-openapi.yml
  format: yaml
  label: Datanomik Balances API
  slug: datanomik-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datanomik/openapi/datanomik-balances-api-openapi.yml
- filename: datanomik-general-owners-api-openapi.yml
  format: yaml
  label: Datanomik General Owners API
  slug: datanomik-general-owners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datanomik/openapi/datanomik-general-owners-api-openapi.yml
- filename: datanomik-investments-api-openapi.yml
  format: yaml
  label: Datanomik Investments API
  slug: datanomik-investments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datanomik/openapi/datanomik-investments-api-openapi.yml
- filename: datanomik-links-api-openapi.yml
  format: yaml
  label: Datanomik Links API
  slug: datanomik-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datanomik/openapi/datanomik-links-api-openapi.yml
- filename: datanomik-payment-slips-api-openapi.yml
  format: yaml
  label: Datanomik Payment Slips API
  slug: datanomik-payment-slips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datanomik/openapi/datanomik-payment-slips-api-openapi.yml
- filename: datanomik-payments-api-openapi.yml
  format: yaml
  label: Datanomik Payments API
  slug: datanomik-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datanomik/openapi/datanomik-payments-api-openapi.yml
- filename: datanomik-pix-transactions-api-openapi.yml
  format: yaml
  label: Datanomik Pix Transactions API
  slug: datanomik-pix-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datanomik/openapi/datanomik-pix-transactions-api-openapi.yml
- filename: datanomik-transactions-api-openapi.yml
  format: yaml
  label: Datanomik Transactions API
  slug: datanomik-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datanomik/openapi/datanomik-transactions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: O acesso à Plataforma é direcionado a pessoas jurídicas devidamente constituídas sob qualquer forma societária permitida pela legislação aplicável
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: O Usuário entende e aceita que a aprovação de seu cadastro depende da avaliação da Datanomik, conforme suas regras e critérios internos.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Datanomik
provenance_date: '2026-11-09'
provider_name: Datanomik
provider_slug: datanomik
slug: datanomik-eligibility
source_date: '2026-11-09'
source_filename: datanomik-eligibility.yml
source_heading: Eligibility
source_page: https://datanomik.com/termos-e-condicoes
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Datanomik\naid: datanomik\nurl: https://datanomik.com/termos-e-condicoes\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: O acesso à Plataforma é direcionado a pessoas jurídicas devidamente constituídas sob qualquer forma societária\n    permitida pela legislação aplicável\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: O Usuário entende e aceita que a aprovação de seu cadastro depende da avaliação da Datanomik, conforme suas\n    regras e critérios internos.\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/datanomik/eligibility/datanomik-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Datanomik's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Open Finance
- Open Banking
- Treasury Management
- Cash Management
- Payments
- Pix
- Financial Data
- Bank Connectivity
- Brazil
- Latin America
- Fintech
---
