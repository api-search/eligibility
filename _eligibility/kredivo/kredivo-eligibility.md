---
api_specs:
- filename: kredivo-calculator-api-openapi.yml
  format: yaml
  label: Kredivo Calculator API
  slug: kredivo-calculator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kredivo/openapi/kredivo-calculator-api-openapi.yml
- filename: kredivo-checkout-api-openapi.yml
  format: yaml
  label: Kredivo Checkout API
  slug: kredivo-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kredivo/openapi/kredivo-checkout-api-openapi.yml
- filename: kredivo-confirmation-api-openapi.yml
  format: yaml
  label: Kredivo Confirmation API
  slug: kredivo-confirmation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kredivo/openapi/kredivo-confirmation-api-openapi.yml
- filename: kredivo-tokenization-api-openapi.yml
  format: yaml
  label: Kredivo Tokenization API
  slug: kredivo-tokenization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kredivo/openapi/kredivo-tokenization-api-openapi.yml
- filename: kredivo-transactions-api-openapi.yml
  format: yaml
  label: Kredivo Transactions API
  slug: kredivo-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kredivo/openapi/kredivo-transactions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - ID
    - SG
    - TH
    text: Aplikasi ini pada awalnya dimaksudkan untuk dilihat di kawasan Indonesia, Singapura, dan Thailand dan kemudian di seluruh kawasan Asia Tenggara.
  entity_types:
  - text: Anda memahami bahwa Aplikasi ini ditujukan hanya untuk penggunaan pribadi perorangan.
    type: individual
  minimum_age:
    text: Aplikasi beserta kontennya ditujukan untuk orang-orang berusia 18 tahun ke atas.
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: Anda memahami bahwa Aplikasi ini ditujukan hanya untuk penggunaan pribadi perorangan.
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
name: Kredivo
provenance_date: '2026-11-09'
provider_name: Kredivo
provider_slug: kredivo
slug: kredivo-eligibility
source_date: '2026-11-09'
source_filename: kredivo-eligibility.yml
source_heading: Eligibility
source_page: https://kredivo.com/p/in/tos.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kredivo\naid: kredivo\nurl: https://kredivo.com/p/in/tos.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - ID\n  - SG\n  - TH\n  excluded: []\n  text: Aplikasi ini pada awalnya dimaksudkan untuk dilihat di kawasan Indonesia, Singapura, dan Thailand dan kemudian\n    di seluruh kawasan Asia Tenggara.\nentity_types:\n- type: individual\n  text: Anda memahami bahwa Aplikasi ini ditujukan hanya untuk penggunaan pribadi perorangan.\nrestricted_uses:\n- summary: Personal use only\n  text: Anda memahami bahwa Aplikasi ini ditujukan hanya untuk penggunaan pribadi perorangan.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Aplikasi beserta kontennya ditujukan untuk orang-orang berusia 18 tahun ke atas.\n"
source_yaml_url: https://artifacts.apis.io/kredivo/eligibility/kredivo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kredivo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Buy Now Pay Later
- Lending
- Consumer Credit
- Checkout
- Fintech
- E-Commerce
- Indonesia
- Southeast Asia
- Financial Services
---
