---
api_specs:
- filename: cryptonews-account-api-openapi.yml
  format: yaml
  label: CryptoNews API Account API
  slug: cryptonews-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptonews/openapi/cryptonews-account-api-openapi.yml
- filename: cryptonews-categories-api-openapi.yml
  format: yaml
  label: CryptoNews API Categories API
  slug: cryptonews-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptonews/openapi/cryptonews-categories-api-openapi.yml
- filename: cryptonews-digest-api-openapi.yml
  format: yaml
  label: CryptoNews API Digest API
  slug: cryptonews-digest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptonews/openapi/cryptonews-digest-api-openapi.yml
- filename: cryptonews-news-api-openapi.yml
  format: yaml
  label: CryptoNews API News API
  slug: cryptonews-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptonews/openapi/cryptonews-news-api-openapi.yml
- filename: cryptonews-prices-api-openapi.yml
  format: yaml
  label: CryptoNews API Prices API
  slug: cryptonews-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptonews/openapi/cryptonews-prices-api-openapi.yml
- filename: cryptonews-sentiment-stats-api-openapi.yml
  format: yaml
  label: CryptoNews API Sentiment & Stats API
  slug: cryptonews-sentiment-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptonews/openapi/cryptonews-sentiment-stats-api-openapi.yml
- filename: cryptonews-trending-api-openapi.yml
  format: yaml
  label: CryptoNews API Trending API
  slug: cryptonews-trending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptonews/openapi/cryptonews-trending-api-openapi.yml
- filename: cryptonews-whale-transactions-api-openapi.yml
  format: yaml
  label: CryptoNews API Whale Transactions API
  slug: cryptonews-whale-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptonews/openapi/cryptonews-whale-transactions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using Crypto News API on behalf of an organization such as your employer, you are agreeing to these Terms on behalf of that organization
    type: business
  - text: To use Crypto News API, you'll need to create an account.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: CryptoNews API
provenance_date: '2026-11-09'
provider_name: CryptoNews API
provider_slug: cryptonews
slug: cryptonews-eligibility
source_date: '2026-11-09'
source_filename: cryptonews-eligibility.yml
source_heading: Eligibility
source_page: https://cryptonews-api.com/termsandconditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CryptoNews API\naid: cryptonews\nurl: https://cryptonews-api.com/termsandconditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using Crypto News API on behalf of an organization such as your employer, you are agreeing to\n    these Terms on behalf of that organization\n- type: individual\n  text: To use Crypto News API, you'll need to create an account.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cryptonews/eligibility/cryptonews-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from CryptoNews API's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- News
- Sentiment Analysis
- Bitcoin
- Market Data
- Whale Transactions
- Crypto Prices
---
