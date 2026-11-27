---
api_specs:
- filename: trading212-accounts-api-openapi.yml
  format: yaml
  label: Trading 212 Accounts API
  slug: trading212-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trading212/openapi/trading212-accounts-api-openapi.yml
- filename: trading212-historical-events-api-openapi.yml
  format: yaml
  label: Trading 212 Historical events API
  slug: trading212-historical-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trading212/openapi/trading212-historical-events-api-openapi.yml
- filename: trading212-instruments-api-openapi.yml
  format: yaml
  label: Trading 212 Instruments API
  slug: trading212-instruments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trading212/openapi/trading212-instruments-api-openapi.yml
- filename: trading212-orders-api-openapi.yml
  format: yaml
  label: Trading 212 Orders API
  slug: trading212-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trading212/openapi/trading212-orders-api-openapi.yml
- filename: trading212-pies-deprecated-api-openapi.yml
  format: yaml
  label: Trading 212 Pies (Deprecated) API
  slug: trading212-pies-deprecated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trading212/openapi/trading212-pies-deprecated-api-openapi.yml
- filename: trading212-positions-api-openapi.yml
  format: yaml
  label: Trading 212 Positions API
  slug: trading212-positions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trading212/openapi/trading212-positions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We provide you with access to our API solely for your personal use
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Algorithmic trading
    text: You are expressly prohibited from using our API for Algorithmic Trading purposes
  - summary: Providing commercial services
    text: or for providing any commercial services, such as agent, brokerage, and/or asset management services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must verify your identity using an API Key and API Secret Key to access our API.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Trading 212
provenance_date: '2026-11-10'
provider_name: Trading 212
provider_slug: trading212
slug: trading212-eligibility
source_date: '2026-11-10'
source_filename: trading212-eligibility.yml
source_heading: Eligibility
source_page: https://www.trading212.com/legal-documentation/API-Terms_EN.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trading 212\naid: trading212\nurl: https://www.trading212.com/legal-documentation/API-Terms_EN.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: We provide you with access to our API solely for your personal use\nrestricted_uses:\n- summary: Algorithmic trading\n  text: You are expressly prohibited from using our API for Algorithmic Trading purposes\n- summary: Providing commercial services\n  text: or for providing any commercial services, such as agent, brokerage, and/or asset management services\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: You must verify your identity using an API Key and API Secret Key to access our API.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trading212/eligibility/trading212-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Trading 212's own page on 2026-11-10.
synthetic: false
tags:
- Investing
- Finance
- Trading
- Stocks
- Portfolio
- Commission-Free
- ISA
---
