---
api_specs:
- filename: ozow-banks-api-openapi.yml
  format: yaml
  label: Ozow Banks API
  slug: ozow-banks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozow/openapi/ozow-banks-api-openapi.yml
- filename: ozow-payments-api-openapi.yml
  format: yaml
  label: Ozow Payments API
  slug: ozow-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozow/openapi/ozow-payments-api-openapi.yml
- filename: ozow-refunds-api-openapi.yml
  format: yaml
  label: Ozow Refunds API
  slug: ozow-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozow/openapi/ozow-refunds-api-openapi.yml
- filename: ozow-transactions-api-openapi.yml
  format: yaml
  label: Ozow Transactions API
  slug: ozow-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozow/openapi/ozow-transactions-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - ZA
    text: ZR Billing are only applicable for use within the South African borders
  entity_types:
  - text: The Website is intended for persons who are at least 18 years or older and who have the legal capacity to enter into contracts in the Republic of South Africa.
    type: individual
  - text: Whether you are a guest, an Ozow merchant or a consumer (“you” or “your”)
    type: business
  minimum_age:
    text: The Website is intended for persons who are at least 18 years or older
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: in any way that is unlawful, improper, immoral or fraudulent or has such purpose or effect
  - summary: Screen or database scraping
    text: to collect, or attempt to collect, personal information about third parties without their knowledge or consent, or to engage in “screen scraping,” “database scraping,” or any other activity with the purpose of obtaining lists of users or other data
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must apply with Ozow to register as a merchant.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ozow
provenance_date: '2026-11-10'
provider_name: Ozow
provider_slug: ozow
slug: ozow-eligibility
source_date: '2026-11-10'
source_filename: ozow-eligibility.yml
source_heading: Eligibility
source_page: https://ozow.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ozow\naid: ozow\nurl: https://ozow.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - ZA\n  excluded: []\n  text: ZR Billing are only applicable for use within the South African borders\nentity_types:\n- type: individual\n  text: The Website is intended for persons who are at least 18 years or older and who have the legal capacity to\n    enter into contracts in the Republic of South Africa.\n- type: business\n  text: Whether you are a guest, an Ozow merchant or a consumer (“you” or “your”)\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: in any\
  \ way that is unlawful, improper, immoral or fraudulent or has such purpose or effect\n- summary: Screen or database scraping\n  text: to collect, or attempt to collect, personal information about third parties without their knowledge or consent,\n    or to engage in “screen scraping,” “database scraping,” or any other activity with the purpose of obtaining\n    lists of users or other data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must apply with Ozow to register as a merchant.\nminimum_age:\n  value: '18'\n  text: The Website is intended for persons who are at least 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/ozow/eligibility/ozow-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Ozow's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Instant EFT
- Pay by Bank
- Fintech
- South Africa
---
