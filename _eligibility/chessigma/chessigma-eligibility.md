---
api_specs:
- filename: chessigma-daily-puzzle-api-openapi.yml
  format: yaml
  label: Chessigma Daily Puzzle API
  slug: chessigma-daily-puzzle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chessigma/openapi/chessigma-daily-puzzle-api-openapi.yml
- filename: chessigma-elo-calculator-api-openapi.yml
  format: yaml
  label: Chessigma Elo Calculator API
  slug: chessigma-elo-calculator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chessigma/openapi/chessigma-elo-calculator-api-openapi.yml
- filename: chessigma-game-api-openapi.yml
  format: yaml
  label: Chessigma Game API
  slug: chessigma-game-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chessigma/openapi/chessigma-game-api-openapi.yml
claim_count: 1
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
  - summary: Illegal use and spam
    text: Upload malware, engage in spam, or use the Service for illegal purposes.
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
name: Chessigma
provenance_date: '2026-11-09'
provider_name: Chessigma
provider_slug: chessigma
slug: chessigma-eligibility
source_date: '2026-11-09'
source_filename: chessigma-eligibility.yml
source_heading: Eligibility
source_page: https://www.chessigma.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chessigma\naid: chessigma\nurl: https://www.chessigma.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal use and spam\n  text: Upload malware, engage in spam, or use the Service for illegal purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chessigma/eligibility/chessigma-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Chessigma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Chess
- Free
- No Auth
---
