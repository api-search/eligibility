---
api_specs:
- filename: stockdata-entities-api-openapi.yml
  format: yaml
  label: StockData Entities API
  slug: stockdata-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stockdata/openapi/stockdata-entities-api-openapi.yml
- filename: stockdata-news-api-openapi.yml
  format: yaml
  label: StockData News API
  slug: stockdata-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stockdata/openapi/stockdata-news-api-openapi.yml
- filename: stockdata-stock-data-api-openapi.yml
  format: yaml
  label: StockData Stock Data API
  slug: stockdata-stock-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stockdata/openapi/stockdata-stock-data-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: you will not use the Site for any illegal or unauthorized purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: StockData
provenance_date: '2026-11-10'
provider_name: StockData
provider_slug: stockdata
slug: stockdata-eligibility
source_date: '2026-11-10'
source_filename: stockdata-eligibility.yml
source_heading: Eligibility
source_page: https://www.stockdata.org/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StockData\naid: stockdata\nurl: https://www.stockdata.org/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: you will not use the Site\
  \ for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Site.\nminimum_age:\n  value: '13'\n  text: The Site is intended for users who are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/stockdata/eligibility/stockdata-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from StockData's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Financial Data
- Stock Market
- Market Data
- News
- Sentiment Analysis
---
