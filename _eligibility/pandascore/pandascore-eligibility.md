---
api_specs:
- filename: pandascore-changes-api-openapi.yml
  format: yaml
  label: PandaScore Changes API
  slug: pandascore-changes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandascore/openapi/pandascore-changes-api-openapi.yml
- filename: pandascore-game-cs-go-api-openapi.yml
  format: yaml
  label: PandaScore Game - CS:GO API
  slug: pandascore-game-cs-go-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandascore/openapi/pandascore-game-cs-go-api-openapi.yml
- filename: pandascore-game-dota-2-api-openapi.yml
  format: yaml
  label: PandaScore Game - Dota 2 API
  slug: pandascore-game-dota-2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandascore/openapi/pandascore-game-dota-2-api-openapi.yml
- filename: pandascore-game-league-of-legends-api-openapi.yml
  format: yaml
  label: PandaScore Game - League of Legends API
  slug: pandascore-game-league-of-legends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandascore/openapi/pandascore-game-league-of-legends-api-openapi.yml
- filename: pandascore-game-valorant-api-openapi.yml
  format: yaml
  label: PandaScore Game - Valorant API
  slug: pandascore-game-valorant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandascore/openapi/pandascore-game-valorant-api-openapi.yml
- filename: pandascore-leagues-api-openapi.yml
  format: yaml
  label: PandaScore Leagues API
  slug: pandascore-leagues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandascore/openapi/pandascore-leagues-api-openapi.yml
- filename: pandascore-matches-api-openapi.yml
  format: yaml
  label: PandaScore Matches API
  slug: pandascore-matches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandascore/openapi/pandascore-matches-api-openapi.yml
- filename: pandascore-players-api-openapi.yml
  format: yaml
  label: PandaScore Players API
  slug: pandascore-players-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandascore/openapi/pandascore-players-api-openapi.yml
- filename: pandascore-series-api-openapi.yml
  format: yaml
  label: PandaScore Series API
  slug: pandascore-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandascore/openapi/pandascore-series-api-openapi.yml
- filename: pandascore-teams-api-openapi.yml
  format: yaml
  label: PandaScore Teams API
  slug: pandascore-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandascore/openapi/pandascore-teams-api-openapi.yml
- filename: pandascore-tournaments-api-openapi.yml
  format: yaml
  label: PandaScore Tournaments API
  slug: pandascore-tournaments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandascore/openapi/pandascore-tournaments-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Customer acknowledges and guarantees that he has the capacity and the required age (majority) to enter into a contract.
    value: null
  restricted_uses:
  - summary: Illegal or unlawful use
    text: The Customer guarantees PandaScore that its activity performed on and via the Site will not be contrary to any law or regulation in force.
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
name: PandaScore
provenance_date: '2026-11-10'
provider_name: PandaScore
provider_slug: pandascore
slug: pandascore-eligibility
source_date: '2026-11-10'
source_filename: pandascore-eligibility.yml
source_heading: Eligibility
source_page: https://www.pandascore.co/terms-and-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PandaScore\naid: pandascore\nurl: https://www.pandascore.co/terms-and-condition\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unlawful use\n  text: The Customer guarantees PandaScore that its activity performed on and via the Site will not be contrary\n    to any law or regulation in force.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: The Customer acknowledges and guarantees that he has the capacity and the required age (majority) to enter\n\
  \    into a contract.\n"
source_yaml_url: https://artifacts.apis.io/pandascore/eligibility/pandascore-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from PandaScore's own page on 2026-11-10.
synthetic: false
tags:
- Esports
- Odds
- Betting
- Live Data
- Stats
- Fantasy
- WebSocket
- REST
---
