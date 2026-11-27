---
api_specs:
- filename: bitrefill-account-api-openapi.yml
  format: yaml
  label: Bitrefill Account API
  slug: bitrefill-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitrefill/openapi/bitrefill-account-api-openapi.yml
- filename: bitrefill-checkout-api-openapi.yml
  format: yaml
  label: Bitrefill Checkout API
  slug: bitrefill-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitrefill/openapi/bitrefill-checkout-api-openapi.yml
- filename: bitrefill-discovery-api-openapi.yml
  format: yaml
  label: Bitrefill Discovery API
  slug: bitrefill-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitrefill/openapi/bitrefill-discovery-api-openapi.yml
- filename: bitrefill-payments-api-openapi.yml
  format: yaml
  label: Bitrefill Payments API
  slug: bitrefill-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitrefill/openapi/bitrefill-payments-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Bitrefill allows the Customer to select their country and displays all the offers available in that country.
  minimum_age:
    text: Each Contest is open to all persons of legal age, excluding employees of Bitrefill
    value: null
  restricted_uses:
  - summary: Resale of products
    text: Customers are intended end-users of the Products. If you want to purchase Products for resale, please reach out to us at support@bitrefill.com
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
name: Bitrefill
provenance_date: '2026-11-09'
provider_name: Bitrefill
provider_slug: bitrefill
slug: bitrefill-eligibility
source_date: '2026-11-09'
source_filename: bitrefill-eligibility.yml
source_heading: Eligibility
source_page: https://www.bitrefill.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bitrefill\naid: bitrefill\nurl: https://www.bitrefill.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Bitrefill allows the Customer to select their country and displays all the offers available in that country.\nentity_types: []\nrestricted_uses:\n- summary: Resale of products\n  text: Customers are intended end-users of the Products. If you want to purchase Products for resale, please reach\n    out to us at support@bitrefill.com\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Each\
  \ Contest is open to all persons of legal age, excluding employees of Bitrefill\n"
source_yaml_url: https://artifacts.apis.io/bitrefill/eligibility/bitrefill-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bitrefill's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Payments
- Gift Cards
- Mobile Top-Up
---
