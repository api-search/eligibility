---
api_specs:
- filename: resolvedmarkets-com-account-api-openapi.yml
  format: yaml
  label: resolvedmarkets-com Account API
  slug: resolvedmarkets-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolvedmarkets-com/openapi/resolvedmarkets-com-account-api-openapi.yml
- filename: resolvedmarkets-com-admin-api-openapi.yml
  format: yaml
  label: resolvedmarkets-com Admin API
  slug: resolvedmarkets-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolvedmarkets-com/openapi/resolvedmarkets-com-admin-api-openapi.yml
- filename: resolvedmarkets-com-backtest-api-openapi.yml
  format: yaml
  label: resolvedmarkets-com Backtest API
  slug: resolvedmarkets-com-backtest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolvedmarkets-com/openapi/resolvedmarkets-com-backtest-api-openapi.yml
- filename: resolvedmarkets-com-exchange-api-openapi.yml
  format: yaml
  label: resolvedmarkets-com Exchange API
  slug: resolvedmarkets-com-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolvedmarkets-com/openapi/resolvedmarkets-com-exchange-api-openapi.yml
- filename: resolvedmarkets-com-markets-api-openapi.yml
  format: yaml
  label: resolvedmarkets-com Markets API
  slug: resolvedmarkets-com-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolvedmarkets-com/openapi/resolvedmarkets-com-markets-api-openapi.yml
- filename: resolvedmarkets-com-payments-api-openapi.yml
  format: yaml
  label: resolvedmarkets-com Payments API
  slug: resolvedmarkets-com-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolvedmarkets-com/openapi/resolvedmarkets-com-payments-api-openapi.yml
- filename: resolvedmarkets-com-public-api-openapi.yml
  format: yaml
  label: resolvedmarkets-com Public API
  slug: resolvedmarkets-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolvedmarkets-com/openapi/resolvedmarkets-com-public-api-openapi.yml
- filename: resolvedmarkets-com-snapshots-api-openapi.yml
  format: yaml
  label: resolvedmarkets-com Snapshots API
  slug: resolvedmarkets-com-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolvedmarkets-com/openapi/resolvedmarkets-com-snapshots-api-openapi.yml
- filename: resolvedmarkets-com-strategies-api-openapi.yml
  format: yaml
  label: resolvedmarkets-com Strategies API
  slug: resolvedmarkets-com-strategies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolvedmarkets-com/openapi/resolvedmarkets-com-strategies-api-openapi.yml
- filename: resolvedmarkets-com-system-api-openapi.yml
  format: yaml
  label: resolvedmarkets-com System API
  slug: resolvedmarkets-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolvedmarkets-com/openapi/resolvedmarkets-com-system-api-openapi.yml
- filename: resolvedmarkets-com-trades-api-openapi.yml
  format: yaml
  label: resolvedmarkets-com Trades API
  slug: resolvedmarkets-com-trades-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolvedmarkets-com/openapi/resolvedmarkets-com-trades-api-openapi.yml
- filename: resolvedmarkets-com-wallets-api-openapi.yml
  format: yaml
  label: resolvedmarkets-com Wallets API
  slug: resolvedmarkets-com-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolvedmarkets-com/openapi/resolvedmarkets-com-wallets-api-openapi.yml
- filename: resolvedmarkets-com-webhooks-api-openapi.yml
  format: yaml
  label: resolvedmarkets-com Webhooks API
  slug: resolvedmarkets-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolvedmarkets-com/openapi/resolvedmarkets-com-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 or older.
    type: individual
  - text: If you use the Service for an organisation, you confirm that you can bind it, and “you” includes it.
    type: business
  minimum_age:
    text: You must be 18 or older.
    value: '18'
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
name: resolvedmarkets-com
provenance_date: '2026-11-10'
provider_name: resolvedmarkets-com
provider_slug: resolvedmarkets-com
slug: resolvedmarkets-com-eligibility
source_date: '2026-11-10'
source_filename: resolvedmarkets-com-eligibility.yml
source_heading: Eligibility
source_page: https://resolvedmarkets.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: resolvedmarkets-com\naid: resolvedmarkets-com\nurl: https://resolvedmarkets.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 or older.\n- type: business\n  text: If you use the Service for an organisation, you confirm that you can bind it, and “you” includes it.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/resolvedmarkets-com/eligibility/resolvedmarkets-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from resolvedmarkets-com's own page on 2026-11-10.
synthetic: false
tags:
- Data
- Finance
- Prediction Markets
- Backtesting
---
