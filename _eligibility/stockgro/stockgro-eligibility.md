---
api_specs:
- filename: stockgro-health-api-openapi.yml
  format: yaml
  label: StockGro Health API
  slug: stockgro-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stockgro/openapi/stockgro-health-api-openapi.yml
- filename: stockgro-process-api-openapi.yml
  format: yaml
  label: StockGro Process API
  slug: stockgro-process-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stockgro/openapi/stockgro-process-api-openapi.yml
- filename: stockgro-tradeview-intraday-model-api-api-openapi.yml
  format: yaml
  label: StockGro TradeView Intraday Model API
  slug: stockgro-tradeview-intraday-model-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stockgro/openapi/stockgro-tradeview-intraday-model-api-api-openapi.yml
claim_count: 2
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
  - summary: Market data limited to personal non-commercial use
    text: Market data is made available for your own personal, non-commercial use only.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Live data is available to you if you have completed your KYC with StockGro
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: StockGro
provenance_date: '2026-11-10'
provider_name: StockGro
provider_slug: stockgro
slug: stockgro-eligibility
source_date: '2026-11-10'
source_filename: stockgro-eligibility.yml
source_heading: Eligibility
source_page: https://www.stockgro.club/tandc/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StockGro\naid: stockgro\nurl: https://www.stockgro.club/tandc/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Market data limited to personal non-commercial use\n  text: Market data is made available for your own personal, non-commercial use only.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Live data is available to you if you have completed your KYC with StockGro\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stockgro/eligibility/stockgro-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from StockGro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Stock Market
- Investing
- Market Data
- Financial Education
- Fintech
- India
- Advisory
- Social Investing
---
