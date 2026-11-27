---
api_specs:
- filename: chess-com-clubs-api-openapi.yml
  format: yaml
  label: Chess.com Clubs API
  slug: chess-com-clubs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chess-com/openapi/chess-com-clubs-api-openapi.yml
- filename: chess-com-countries-api-openapi.yml
  format: yaml
  label: Chess.com Countries API
  slug: chess-com-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chess-com/openapi/chess-com-countries-api-openapi.yml
- filename: chess-com-games-api-openapi.yml
  format: yaml
  label: Chess.com Games API
  slug: chess-com-games-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chess-com/openapi/chess-com-games-api-openapi.yml
- filename: chess-com-leaderboards-api-openapi.yml
  format: yaml
  label: Chess.com Leaderboards API
  slug: chess-com-leaderboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chess-com/openapi/chess-com-leaderboards-api-openapi.yml
- filename: chess-com-matches-api-openapi.yml
  format: yaml
  label: Chess.com Matches API
  slug: chess-com-matches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chess-com/openapi/chess-com-matches-api-openapi.yml
- filename: chess-com-players-api-openapi.yml
  format: yaml
  label: Chess.com Players API
  slug: chess-com-players-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chess-com/openapi/chess-com-players-api-openapi.yml
- filename: chess-com-puzzles-api-openapi.yml
  format: yaml
  label: Chess.com Puzzles API
  slug: chess-com-puzzles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chess-com/openapi/chess-com-puzzles-api-openapi.yml
- filename: chess-com-streamers-api-openapi.yml
  format: yaml
  label: Chess.com Streamers API
  slug: chess-com-streamers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chess-com/openapi/chess-com-streamers-api-openapi.yml
- filename: chess-com-titled-players-api-openapi.yml
  format: yaml
  label: Chess.com Titled Players API
  slug: chess-com-titled-players-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chess-com/openapi/chess-com-titled-players-api-openapi.yml
- filename: chess-com-tournaments-api-openapi.yml
  format: yaml
  label: Chess.com Tournaments API
  slug: chess-com-tournaments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chess-com/openapi/chess-com-tournaments-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: These Services are provided by Chess.com from its offices in the United States of America. We make no representation that the Services are appropriate or available in other locations.
  entity_types:
  - text: Each account is assigned to a single User, and it is intended solely for personal, non-commercial use.
    type: individual
  minimum_age:
    text: To enter into this Agreement, use the Services, and/or create an account with us, you must be at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: AI model training and dataset creation
    text: You may not use automated or artificial intelligence (AI) tools to access, scan, scrape, data mine, copy, or use the materials or content in the Services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We do not ask you for your birth date, if you use the Service or create an account with us, then you are affirming that you meet these requirements
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Chess.com
provenance_date: '2026-11-09'
provider_name: Chess.com
provider_slug: chess-com
slug: chess-com-eligibility
source_date: '2026-11-09'
source_filename: chess-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.chess.com/legal/user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chess.com\naid: chess-com\nurl: https://www.chess.com/legal/user-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: These Services are provided by Chess.com from its offices in the United States of America. We make no representation\n    that the Services are appropriate or available in other locations.\nentity_types:\n- type: individual\n  text: Each account is assigned to a single User, and it is intended solely for personal, non-commercial use.\nrestricted_uses:\n- summary: AI model training and dataset creation\n  text: You may not use automated or artificial\
  \ intelligence (AI) tools to access, scan, scrape, data mine, copy,\n    or use the materials or content in the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We do not ask you for your birth date, if you use the Service or create an account with us, then you are\n    affirming that you meet these requirements\nminimum_age:\n  value: '13'\n  text: To enter into this Agreement, use the Services, and/or create an account with us, you must be at least 13\n    years of age.\n"
source_yaml_url: https://artifacts.apis.io/chess-com/eligibility/chess-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Chess.com's own page on 2026-11-09.
synthetic: false
tags:
- Chess
- Gaming
- Online Games
- Sports
- Community
- Education
---
