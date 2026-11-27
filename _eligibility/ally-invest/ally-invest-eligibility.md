---
api_specs:
- filename: ally-invest-accounts-api-openapi.yml
  format: yaml
  label: Ally Invest Accounts API
  slug: ally-invest-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ally-invest/openapi/ally-invest-accounts-api-openapi.yml
- filename: ally-invest-market-data-api-openapi.yml
  format: yaml
  label: Ally Invest Market Data API
  slug: ally-invest-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ally-invest/openapi/ally-invest-market-data-api-openapi.yml
- filename: ally-invest-member-api-openapi.yml
  format: yaml
  label: Ally Invest Member API
  slug: ally-invest-member-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ally-invest/openapi/ally-invest-member-api-openapi.yml
- filename: ally-invest-orders-api-openapi.yml
  format: yaml
  label: Ally Invest Orders API
  slug: ally-invest-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ally-invest/openapi/ally-invest-orders-api-openapi.yml
- filename: ally-invest-utilities-api-openapi.yml
  format: yaml
  label: Ally Invest Utilities API
  slug: ally-invest-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ally-invest/openapi/ally-invest-utilities-api-openapi.yml
- filename: ally-invest-watchlists-api-openapi.yml
  format: yaml
  label: Ally Invest Watchlists API
  slug: ally-invest-watchlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ally-invest/openapi/ally-invest-watchlists-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You are a permanent resident of the United States, excluding any territory other than the District of Columbia and Puerto Rico
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No automated order entry
    text: must not incorporate any functionality that permits algorithmic trading, automated order entry
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
name: Ally Invest
provenance_date: '2026-11-09'
provider_name: Ally Invest
provider_slug: ally-invest
slug: ally-invest-eligibility
source_date: '2026-11-09'
source_filename: ally-invest-eligibility.yml
source_heading: Eligibility
source_page: https://www.ally.com/content/dam/pdf/invest/api-agreement.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ally Invest\naid: ally-invest\nurl: https://www.ally.com/content/dam/pdf/invest/api-agreement.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You are a permanent resident of the United States, excluding any territory other than the District of Columbia\n    and Puerto Rico\nentity_types: []\nrestricted_uses:\n- summary: No automated order entry\n  text: must not incorporate any functionality that permits algorithmic trading, automated order entry\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ally-invest/eligibility/ally-invest-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Ally Invest's own page on 2026-11-09.
synthetic: false
tags:
- Brokerage
- Investing
- Trading
- Finance
- Stocks
- Options
- Market Data
- Self-Directed
- Financial Services
---
