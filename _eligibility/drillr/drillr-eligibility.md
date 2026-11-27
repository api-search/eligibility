---
api_specs:
- filename: drillr-analyst-api-openapi.yml
  format: yaml
  label: drillr Public Data API Analyst API
  slug: drillr-analyst-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-analyst-api-openapi.yml
- filename: drillr-company-api-openapi.yml
  format: yaml
  label: drillr Public Data API Company API
  slug: drillr-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-company-api-openapi.yml
- filename: drillr-contract-api-openapi.yml
  format: yaml
  label: drillr Public Data API Contract API
  slug: drillr-contract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-contract-api-openapi.yml
- filename: drillr-earnings-api-openapi.yml
  format: yaml
  label: drillr Public Data API Earnings API
  slug: drillr-earnings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-earnings-api-openapi.yml
- filename: drillr-events-api-openapi.yml
  format: yaml
  label: drillr Public Data API Events API
  slug: drillr-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-events-api-openapi.yml
- filename: drillr-executives-api-openapi.yml
  format: yaml
  label: drillr Public Data API Executives API
  slug: drillr-executives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-executives-api-openapi.yml
- filename: drillr-filings-api-openapi.yml
  format: yaml
  label: drillr Public Data API Filings API
  slug: drillr-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-filings-api-openapi.yml
- filename: drillr-financials-api-openapi.yml
  format: yaml
  label: drillr Public Data API Financials API
  slug: drillr-financials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-financials-api-openapi.yml
- filename: drillr-ownership-api-openapi.yml
  format: yaml
  label: drillr Public Data API Ownership API
  slug: drillr-ownership-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-ownership-api-openapi.yml
- filename: drillr-prices-api-openapi.yml
  format: yaml
  label: drillr Public Data API Prices API
  slug: drillr-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-prices-api-openapi.yml
- filename: drillr-signal-api-openapi.yml
  format: yaml
  label: drillr Public Data API Signal API
  slug: drillr-signal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-signal-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have authority to bind yourself or any entity you represent to these Terms.
    type: individual
  - text: If you use the Service on behalf of a regulated financial institution (registered investment adviser, hedge fund, asset manager, broker-dealer, bank, etc.), you additionally represent and undertake
    type: business
  minimum_age:
    text: You must be at least 18 years old and have authority to bind yourself or any entity you represent to these Terms.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons
    text: provide the Service to any sanctioned individual or entity
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
name: drillr
provenance_date: '2026-11-09'
provider_name: drillr
provider_slug: drillr
slug: drillr-eligibility
source_date: '2026-11-09'
source_filename: drillr-eligibility.yml
source_heading: Eligibility
source_page: https://drillr.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: drillr\naid: drillr\nurl: https://drillr.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have authority to bind yourself or any entity you represent to these\n    Terms.\n- type: business\n  text: If you use the Service on behalf of a regulated financial institution (registered investment adviser, hedge\n    fund, asset manager, broker-dealer, bank, etc.), you additionally represent and undertake\nrestricted_uses:\n- summary: Sanctioned persons\n  text: provide the Service to any\
  \ sanctioned individual or entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have authority to bind yourself or any entity you represent to these\n    Terms.\n"
source_yaml_url: https://artifacts.apis.io/drillr/eligibility/drillr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from drillr's own page on 2026-11-09.
synthetic: false
tags:
- Financial Data
- Stocks
- SEC Filings
- Fundamentals
- Earnings
- Ownership
- Corporate Events
- Analyst Ratings
- news-signals
- MCP
- Agent-Native
---
