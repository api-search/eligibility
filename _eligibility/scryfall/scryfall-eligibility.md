---
api_specs:
- filename: scryfall-bulk-data-api-openapi.yml
  format: yaml
  label: Scryfall Bulk Data API
  slug: scryfall-bulk-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-bulk-data-api-openapi.yml
- filename: scryfall-cards-api-openapi.yml
  format: yaml
  label: Scryfall Cards API
  slug: scryfall-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-cards-api-openapi.yml
- filename: scryfall-catalogs-api-openapi.yml
  format: yaml
  label: Scryfall Catalogs API
  slug: scryfall-catalogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-catalogs-api-openapi.yml
- filename: scryfall-migrations-api-openapi.yml
  format: yaml
  label: Scryfall Migrations API
  slug: scryfall-migrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-migrations-api-openapi.yml
- filename: scryfall-rulings-api-openapi.yml
  format: yaml
  label: Scryfall Rulings API
  slug: scryfall-rulings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-rulings-api-openapi.yml
- filename: scryfall-sets-api-openapi.yml
  format: yaml
  label: Scryfall Sets API
  slug: scryfall-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-sets-api-openapi.yml
- filename: scryfall-symbology-api-openapi.yml
  format: yaml
  label: Scryfall Symbology API
  slug: scryfall-symbology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-symbology-api-openapi.yml
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
  - summary: No new games from Scryfall data
    text: You may not use Scryfall data to create new games
  - summary: No implied Scryfall endorsement
    text: You may not use Scryfall logos or use the Scryfall name in a way that implies Scryfall has endorsed you, your work, or your product.
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
name: Scryfall
provenance_date: '2026-11-10'
provider_name: Scryfall
provider_slug: scryfall
slug: scryfall-eligibility
source_date: '2026-11-10'
source_filename: scryfall-eligibility.yml
source_heading: Eligibility
source_page: https://scryfall.com/docs/api
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scryfall\naid: scryfall\nurl: https://scryfall.com/docs/api\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No new games from Scryfall data\n  text: You may not use Scryfall data to create new games\n- summary: No implied Scryfall endorsement\n  text: You may not use Scryfall logos or use the Scryfall name in a way that implies Scryfall has endorsed you,\n    your work, or your product.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/scryfall/eligibility/scryfall-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Scryfall's own page on 2026-11-10.
synthetic: false
tags:
- Magic The Gathering
- Card Data
- Open Data
- Free
- Community Funded
- Public APIs
- Gaming
- Card Games
---
