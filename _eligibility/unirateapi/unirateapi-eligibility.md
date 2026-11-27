---
api_specs:
- filename: unirateapi-commodity-api-openapi.yml
  format: yaml
  label: UniRate API Commodity API
  slug: unirateapi-commodity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unirateapi/openapi/unirateapi-commodity-api-openapi.yml
- filename: unirateapi-currency-api-openapi.yml
  format: yaml
  label: UniRate API Currency API
  slug: unirateapi-currency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unirateapi/openapi/unirateapi-currency-api-openapi.yml
- filename: unirateapi-historical-currency-api-openapi.yml
  format: yaml
  label: UniRate API Historical Currency API
  slug: unirateapi-historical-currency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unirateapi/openapi/unirateapi-historical-currency-api-openapi.yml
- filename: unirateapi-vat-rates-api-openapi.yml
  format: yaml
  label: UniRate API VAT Rates API
  slug: unirateapi-vat-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unirateapi/openapi/unirateapi-vat-rates-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Informational use only, not trading or investing
    text: All data provided is for informational purposes only, and is not intended for trading or investing purposes.
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
name: UniRate API
provenance_date: '2026-11-10'
provider_name: UniRate API
provider_slug: unirateapi
slug: unirateapi-eligibility
source_date: '2026-11-10'
source_filename: unirateapi-eligibility.yml
source_heading: Eligibility
source_page: https://unirateapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UniRate API\naid: unirateapi\nurl: https://unirateapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Informational use only, not trading or investing\n  text: All data provided is for informational purposes only, and is not intended for trading or investing purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/unirateapi/eligibility/unirateapi-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from UniRate API's own page on 2026-11-10.
synthetic: false
tags:
- Currency
- Exchange Rates
- Foreign Exchange
- Currency Conversion
- VAT
- Finance
- Financial Data
---
