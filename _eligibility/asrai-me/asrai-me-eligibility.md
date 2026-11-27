---
api_specs:
- filename: asrai-me-ai-api-openapi.yml
  format: yaml
  label: Asrai AI API
  slug: asrai-me-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asrai-me/openapi/asrai-me-ai-api-openapi.yml
- filename: asrai-me-cashflow-api-openapi.yml
  format: yaml
  label: Asrai Cashflow API
  slug: asrai-me-cashflow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asrai-me/openapi/asrai-me-cashflow-api-openapi.yml
- filename: asrai-me-market-data-api-openapi.yml
  format: yaml
  label: Asrai Market Data API
  slug: asrai-me-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asrai-me/openapi/asrai-me-market-data-api-openapi.yml
- filename: asrai-me-screeners-api-openapi.yml
  format: yaml
  label: Asrai Screeners API
  slug: asrai-me-screeners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asrai-me/openapi/asrai-me-screeners-api-openapi.yml
- filename: asrai-me-technical-api-openapi.yml
  format: yaml
  label: Asrai Technical API
  slug: asrai-me-technical-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asrai-me/openapi/asrai-me-technical-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18.
    type: individual
  minimum_age:
    text: You must be at least 18.
    value: '18'
  restricted_uses:
  - summary: Illegal use, market manipulation or fraud
    text: use it for anything illegal, including market manipulation or fraud;
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
name: Asrai
provenance_date: '2026-11-09'
provider_name: Asrai
provider_slug: asrai-me
slug: asrai-me-eligibility
source_date: '2026-11-09'
source_filename: asrai-me-eligibility.yml
source_heading: Eligibility
source_page: https://asrai.me/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Asrai\naid: asrai-me\nurl: https://asrai.me/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18.\nrestricted_uses:\n- summary: Illegal use, market manipulation or fraud\n  text: use it for anything illegal, including market manipulation or fraud;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18.\n"
source_yaml_url: https://artifacts.apis.io/asrai-me/eligibility/asrai-me-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Asrai's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Artificial Intelligence
- Trading
- Signals
- Telegram
- Analytics
---
