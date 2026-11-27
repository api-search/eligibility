---
api_specs:
- filename: deutsche-boerse-order-book-api-api-openapi.yml
  format: yaml
  label: A7 Analytics Platform - Order Book API
  slug: a7-order-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deutsche-boerse/openapi/deutsche-boerse-order-book-api-api-openapi.yml
- filename: deutsche-boerse-market-data-api-eobi-api-openapi.yml
  format: yaml
  label: A7 Analytics Platform - Market Data API (EOBI)
  slug: a7-market-data-eobi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deutsche-boerse/openapi/deutsche-boerse-market-data-api-eobi-api-openapi.yml
- filename: deutsche-boerse-exchanges-assets-securities-api-openapi.yml
  format: yaml
  label: A7 Analytics Platform - CME Market Data API (MDP)
  slug: a7-cme-market-data-mdp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deutsche-boerse/openapi/deutsche-boerse-exchanges-assets-securities-api-openapi.yml
- filename: deutsche-boerse-reference-data-api-api-openapi.yml
  format: yaml
  label: A7 Analytics Platform - Reference Data API (RDI) v2
  slug: a7-reference-data-rdi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deutsche-boerse/openapi/deutsche-boerse-reference-data-api-api-openapi.yml
- filename: deutsche-boerse-cme-reference-data-api-api-openapi.yml
  format: yaml
  label: A7 Analytics Platform - CME Reference Data API (SD)
  slug: a7-cme-reference-data-sd-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deutsche-boerse/openapi/deutsche-boerse-cme-reference-data-api-api-openapi.yml
- filename: deutsche-boerse-algo-management-api-api-openapi.yml
  format: yaml
  label: A7 Analytics Platform - Algo Management API
  slug: a7-algo-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deutsche-boerse/openapi/deutsche-boerse-algo-management-api-api-openapi.yml
- filename: deutsche-boerse-dataset-api-api-openapi.yml
  format: yaml
  label: A7 Analytics Platform - Dataset API
  slug: a7-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deutsche-boerse/openapi/deutsche-boerse-dataset-api-api-openapi.yml
- filename: deutsche-boerse-latency-historgram-api-openapi.yml
  format: yaml
  label: A7 Analytics Platform - Market Data Insights API
  slug: a7-market-data-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deutsche-boerse/openapi/deutsche-boerse-latency-historgram-api-openapi.yml
- filename: deutsche-boerse-option-prices-and-greeks-api-openapi.yml
  format: yaml
  label: A7 Analytics Platform - Option Analytics API
  slug: a7-option-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deutsche-boerse/openapi/deutsche-boerse-option-prices-and-greeks-api-openapi.yml
- filename: deutsche-boerse-precalc-api-api-openapi.yml
  format: yaml
  label: A7 Analytics Platform - Precalc API
  slug: a7-precalc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deutsche-boerse/openapi/deutsche-boerse-precalc-api-api-openapi.yml
- filename: deutsche-boerse-auctions-api-openapi.yml
  format: yaml
  label: A7 Analytics Platform - Auction Simulation API
  slug: a7-auction-simulation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deutsche-boerse/openapi/deutsche-boerse-auctions-api-openapi.yml
- filename: deutsche-boerse-cloud-stream-asyncapi.yml
  format: yaml
  label: Deutsche Börse Cloud Stream Market Data API
  slug: cloud-stream-market-data-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/deutsche-boerse/asyncapi/deutsche-boerse-cloud-stream-asyncapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: are currently not available for offer, sale or trading in the United States nor may they be offered, sold or traded by persons to whom US tax laws apply.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Securities and derivatives restricted in US
    text: are currently not available for offer, sale or trading in the United States nor may they be offered, sold or traded by persons to whom US tax laws apply.
  - summary: XTF fund shares may be restricted in residence country
    text: sale of the fund shares listed in XTF Exchange Traded Funds may not be permitted in their country of residence.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Deutsche Börse
provenance_date: '2026-11-09'
provider_name: Deutsche Börse
provider_slug: deutsche-boerse
slug: deutsche-boerse-eligibility
source_date: '2026-11-09'
source_filename: deutsche-boerse-eligibility.yml
source_heading: Eligibility
source_page: https://www.deutsche-boerse.com/dbg-en/meta/disclaimer
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deutsche Börse\naid: deutsche-boerse\nurl: https://www.deutsche-boerse.com/dbg-en/meta/disclaimer\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  text: are currently not available for offer, sale or trading in the United States nor may they be offered, sold\n    or traded by persons to whom US tax laws apply.\nentity_types: []\nrestricted_uses:\n- summary: Securities and derivatives restricted in US\n  text: are currently not available for offer, sale or trading in the United States nor may they be offered, sold\n    or traded by persons to whom US tax laws apply.\n- summary: XTF\
  \ fund shares may be restricted in residence country\n  text: sale of the fund shares listed in XTF Exchange Traded Funds may not be permitted in their country of residence.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/deutsche-boerse/eligibility/deutsche-boerse-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Deutsche Börse's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Market Data
- Stocks
- Derivatives
- Trading
- Real-Time
- Order Book
- Reference Data
- Exchange
- Analytics
---
