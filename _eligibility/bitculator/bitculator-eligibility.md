---
api_specs:
- filename: bitculator-alarms-api-openapi.yml
  format: yaml
  label: Bitculator Alarms API
  slug: bitculator-alarms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-alarms-api-openapi.yml
- filename: bitculator-calculators-api-openapi.yml
  format: yaml
  label: Bitculator Calculators API
  slug: bitculator-calculators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-calculators-api-openapi.yml
- filename: bitculator-coins-api-openapi.yml
  format: yaml
  label: Bitculator Coins API
  slug: bitculator-coins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-coins-api-openapi.yml
- filename: bitculator-conversion-api-openapi.yml
  format: yaml
  label: Bitculator Conversion API
  slug: bitculator-conversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-conversion-api-openapi.yml
- filename: bitculator-editorial-api-openapi.yml
  format: yaml
  label: Bitculator Editorial API
  slug: bitculator-editorial-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-editorial-api-openapi.yml
- filename: bitculator-exchanges-api-openapi.yml
  format: yaml
  label: Bitculator Exchanges API
  slug: bitculator-exchanges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-exchanges-api-openapi.yml
- filename: bitculator-global-market-api-openapi.yml
  format: yaml
  label: Bitculator Global Market API
  slug: bitculator-global-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-global-market-api-openapi.yml
- filename: bitculator-indicators-api-openapi.yml
  format: yaml
  label: Bitculator Indicators API
  slug: bitculator-indicators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-indicators-api-openapi.yml
- filename: bitculator-liquidations-api-openapi.yml
  format: yaml
  label: Bitculator Liquidations API
  slug: bitculator-liquidations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-liquidations-api-openapi.yml
- filename: bitculator-markets-api-openapi.yml
  format: yaml
  label: Bitculator Markets API
  slug: bitculator-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-markets-api-openapi.yml
- filename: bitculator-meta-api-openapi.yml
  format: yaml
  label: Bitculator Meta API
  slug: bitculator-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-meta-api-openapi.yml
- filename: bitculator-prices-api-openapi.yml
  format: yaml
  label: Bitculator Prices API
  slug: bitculator-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-prices-api-openapi.yml
- filename: bitculator-sentiment-api-openapi.yml
  format: yaml
  label: Bitculator Sentiment API
  slug: bitculator-sentiment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-sentiment-api-openapi.yml
- filename: bitculator-wallets-api-openapi.yml
  format: yaml
  label: Bitculator Wallets API
  slug: bitculator-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-wallets-api-openapi.yml
- filename: bitculator-webhooks-api-openapi.yml
  format: yaml
  label: Bitculator Webhooks API
  slug: bitculator-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 to hold an account.
    type: individual
  - text: If you use Bitculator for business purposes, you use it at your own risk, the limits above apply fully, and you cover us for claims that come from your use of the service or your content.
    type: business
  minimum_age:
    text: You must be at least 18 to hold an account.
    value: '18'
  restricted_uses:
  - summary: No illegal, misleading or scam content
    text: Do not post anything illegal, hateful, misleading, someone else's private data, or a scam - including "guaranteed return" claims and pump-and-dump schemes.
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
name: Bitculator
provenance_date: '2026-11-09'
provider_name: Bitculator
provider_slug: bitculator
slug: bitculator-eligibility
source_date: '2026-11-09'
source_filename: bitculator-eligibility.yml
source_heading: Eligibility
source_page: https://bitculator.com/en/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bitculator\naid: bitculator\nurl: https://bitculator.com/en/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 to hold an account.\n- type: business\n  text: If you use Bitculator for business purposes, you use it at your own risk, the limits above apply fully,\n    and you cover us for claims that come from your use of the service or your content.\nrestricted_uses:\n- summary: No illegal, misleading or scam content\n  text: Do not post anything illegal, hateful, misleading, someone else's private\
  \ data, or a scam - including \"guaranteed\n    return\" claims and pump-and-dump schemes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 to hold an account.\n"
source_yaml_url: https://artifacts.apis.io/bitculator/eligibility/bitculator-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bitculator's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- crypto-market-data
- Blockchain
- Finance
- Fintech
- Web3
- Trading
- Exchange Data
- Wallets
- Sentiment
- Indicators
---
