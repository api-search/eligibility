---
api_specs:
- filename: tickerall-com-accounts-api-openapi.yml
  format: yaml
  label: tickerall-com Accounts API
  slug: tickerall-com-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-accounts-api-openapi.yml
- filename: tickerall-com-bulk-api-openapi.yml
  format: yaml
  label: tickerall-com Bulk API
  slug: tickerall-com-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-bulk-api-openapi.yml
- filename: tickerall-com-candles-history-api-openapi.yml
  format: yaml
  label: tickerall-com Candles & History API
  slug: tickerall-com-candles-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-candles-history-api-openapi.yml
- filename: tickerall-com-copy-trading-api-openapi.yml
  format: yaml
  label: tickerall-com Copy Trading API
  slug: tickerall-com-copy-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-copy-trading-api-openapi.yml
- filename: tickerall-com-orders-api-openapi.yml
  format: yaml
  label: tickerall-com Orders API
  slug: tickerall-com-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-orders-api-openapi.yml
- filename: tickerall-com-sessions-api-openapi.yml
  format: yaml
  label: tickerall-com Sessions API
  slug: tickerall-com-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-sessions-api-openapi.yml
- filename: tickerall-com-symbols-api-openapi.yml
  format: yaml
  label: tickerall-com Symbols API
  slug: tickerall-com-symbols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-symbols-api-openapi.yml
- filename: tickerall-com-trade-history-api-openapi.yml
  format: yaml
  label: tickerall-com Trade History API
  slug: tickerall-com-trade-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-trade-history-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use TickerAll on behalf of a company, you confirm you may bind that company.
    type: business
  minimum_age:
    text: You must be at least 18 and legally able to trade with your broker where you live.
    value: '18'
  restricted_uses:
  - summary: Prop-firm or funded-trader programmes
    text: you need an Enterprise plan, whether those accounts are demo or live.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Contact [email protected] to set one up.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: tickerall-com
provenance_date: '2026-11-10'
provider_name: tickerall-com
provider_slug: tickerall-com
slug: tickerall-com-eligibility
source_date: '2026-11-10'
source_filename: tickerall-com-eligibility.yml
source_heading: Eligibility
source_page: https://tickerall.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tickerall-com\naid: tickerall-com\nurl: https://tickerall.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use TickerAll on behalf of a company, you confirm you may bind that company.\nrestricted_uses:\n- summary: Prop-firm or funded-trader programmes\n  text: you need an Enterprise plan, whether those accounts are demo or live.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Contact [email protected] to set one up.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally\
  \ able to trade with your broker where you live.\n"
source_yaml_url: https://artifacts.apis.io/tickerall-com/eligibility/tickerall-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from tickerall-com's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Trading
- Foreign Exchange
- MT5
- MT4
---
