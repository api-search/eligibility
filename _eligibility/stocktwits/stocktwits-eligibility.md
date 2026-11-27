---
api_specs:
- filename: stocktwits-account-api-openapi.yml
  format: yaml
  label: StockTwits Account API
  slug: stocktwits-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stocktwits/openapi/stocktwits-account-api-openapi.yml
- filename: stocktwits-deletions-api-openapi.yml
  format: yaml
  label: StockTwits Deletions API
  slug: stocktwits-deletions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stocktwits/openapi/stocktwits-deletions-api-openapi.yml
- filename: stocktwits-friendships-api-openapi.yml
  format: yaml
  label: StockTwits Friendships API
  slug: stocktwits-friendships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stocktwits/openapi/stocktwits-friendships-api-openapi.yml
- filename: stocktwits-graph-social-api-openapi.yml
  format: yaml
  label: StockTwits Graph (Social) API
  slug: stocktwits-graph-social-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stocktwits/openapi/stocktwits-graph-social-api-openapi.yml
- filename: stocktwits-messages-api-openapi.yml
  format: yaml
  label: StockTwits Messages API
  slug: stocktwits-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stocktwits/openapi/stocktwits-messages-api-openapi.yml
- filename: stocktwits-search-api-openapi.yml
  format: yaml
  label: StockTwits Search API
  slug: stocktwits-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stocktwits/openapi/stocktwits-search-api-openapi.yml
- filename: stocktwits-streams-api-openapi.yml
  format: yaml
  label: StockTwits Streams API
  slug: stocktwits-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stocktwits/openapi/stocktwits-streams-api-openapi.yml
- filename: stocktwits-trending-api-openapi.yml
  format: yaml
  label: StockTwits Trending API
  slug: stocktwits-trending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stocktwits/openapi/stocktwits-trending-api-openapi.yml
- filename: stocktwits-watchlists-api-openapi.yml
  format: yaml
  label: StockTwits Watchlists API
  slug: stocktwits-watchlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stocktwits/openapi/stocktwits-watchlists-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least eighteen (18) years old to use the Service.
    type: individual
  - text: If you access or use the Service on behalf of a company or other entity, you represent and warrant that you are authorized to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Market manipulation and fraud
    text: artificially amplify, suppress, coordinate, or otherwise manipulate engagement, sentiment, visibility, or market perception on the Service
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
name: StockTwits
provenance_date: '2026-11-10'
provider_name: StockTwits
provider_slug: stocktwits
slug: stocktwits-eligibility
source_date: '2026-11-10'
source_filename: stocktwits-eligibility.yml
source_heading: Eligibility
source_page: https://stocktwits.com/about/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StockTwits\naid: stocktwits\nurl: https://stocktwits.com/about/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old to use the Service.\n- type: business\n  text: If you access or use the Service on behalf of a company or other entity, you represent and warrant that\n    you are authorized to bind that entity to these Terms\nrestricted_uses:\n- summary: Market manipulation and fraud\n  text: artificially amplify, suppress, coordinate, or otherwise manipulate engagement, sentiment,\
  \ visibility, or\n    market perception on the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/stocktwits/eligibility/stocktwits-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from StockTwits's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Social
- Stocks
- Trading
- Investing
- Market Data
- Social Finance
- Watchlist
- Messaging
---
