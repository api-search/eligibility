---
api_specs:
- filename: exchangerate-api-enriched-data-api-openapi.yml
  format: yaml
  label: ExchangeRate-API Enriched Data API
  slug: exchangerate-api-enriched-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exchangerate-api/openapi/exchangerate-api-enriched-data-api-openapi.yml
- filename: exchangerate-api-historical-rates-api-openapi.yml
  format: yaml
  label: ExchangeRate-API Historical Rates API
  slug: exchangerate-api-historical-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exchangerate-api/openapi/exchangerate-api-historical-rates-api-openapi.yml
- filename: exchangerate-api-latest-rates-api-openapi.yml
  format: yaml
  label: ExchangeRate-API Latest Rates API
  slug: exchangerate-api-latest-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exchangerate-api/openapi/exchangerate-api-latest-rates-api-openapi.yml
- filename: exchangerate-api-open-access-api-openapi.yml
  format: yaml
  label: ExchangeRate-API Open Access API
  slug: exchangerate-api-open-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exchangerate-api/openapi/exchangerate-api-open-access-api-openapi.yml
- filename: exchangerate-api-pair-conversion-api-openapi.yml
  format: yaml
  label: ExchangeRate-API Pair Conversion API
  slug: exchangerate-api-pair-conversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exchangerate-api/openapi/exchangerate-api-pair-conversion-api-openapi.yml
- filename: exchangerate-api-quota-api-openapi.yml
  format: yaml
  label: ExchangeRate-API Quota API
  slug: exchangerate-api-quota-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exchangerate-api/openapi/exchangerate-api-quota-api-openapi.yml
- filename: exchangerate-api-supported-codes-api-openapi.yml
  format: yaml
  label: ExchangeRate-API Supported Codes API
  slug: exchangerate-api-supported-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exchangerate-api/openapi/exchangerate-api-supported-codes-api-openapi.yml
- filename: exchangerate-api-account-api-openapi.yml
  format: yaml
  label: ExchangeRate-API Account API
  slug: exchangerate-api-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exchangerate-api/openapi/exchangerate-api-account-api-openapi.yml
- filename: exchangerate-api-currencies-api-openapi.yml
  format: yaml
  label: ExchangeRate-API Currencies API
  slug: exchangerate-api-currencies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exchangerate-api/openapi/exchangerate-api-currencies-api-openapi.yml
- filename: exchangerate-api-latest-api-openapi.yml
  format: yaml
  label: ExchangeRate-API Latest API
  slug: exchangerate-api-latest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exchangerate-api/openapi/exchangerate-api-latest-api-openapi.yml
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
  - summary: No programmatic redistribution of rate data
    text: ExchangeRate-API data may only be used for your end purposes and not in any product or service that offers programmatic or automatic access to exchange rate data.
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
name: ExchangeRate-API
provenance_date: '2026-11-09'
provider_name: ExchangeRate-API
provider_slug: exchangerate-api
slug: exchangerate-api-eligibility
source_date: '2026-11-09'
source_filename: exchangerate-api-eligibility.yml
source_heading: Eligibility
source_page: https://www.exchangerate-api.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ExchangeRate-API\naid: exchangerate-api\nurl: https://www.exchangerate-api.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No programmatic redistribution of rate data\n  text: ExchangeRate-API data may only be used for your end purposes and not in any product or service that offers\n    programmatic or automatic access to exchange rate data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/exchangerate-api/eligibility/exchangerate-api-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from ExchangeRate-API's own page on 2026-11-09.
synthetic: false
tags:
- Foreign Exchange
- Financial Data
- Currency Conversion
- Public APIs
---
