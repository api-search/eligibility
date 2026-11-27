---
api_specs:
- filename: epic-games-achievements-api-openapi.yml
  format: yaml
  label: Epic Games Achievements API
  slug: epic-games-achievements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epic-games/openapi/epic-games-achievements-api-openapi.yml
- filename: epic-games-auth-api-openapi.yml
  format: yaml
  label: Epic Games Auth API
  slug: epic-games-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epic-games/openapi/epic-games-auth-api-openapi.yml
- filename: epic-games-connect-api-openapi.yml
  format: yaml
  label: Epic Games Connect API
  slug: epic-games-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epic-games/openapi/epic-games-connect-api-openapi.yml
- filename: epic-games-ecom-api-openapi.yml
  format: yaml
  label: Epic Games Ecom API
  slug: epic-games-ecom-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epic-games/openapi/epic-games-ecom-api-openapi.yml
- filename: epic-games-leaderboards-api-openapi.yml
  format: yaml
  label: Epic Games Leaderboards API
  slug: epic-games-leaderboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epic-games/openapi/epic-games-leaderboards-api-openapi.yml
- filename: epic-games-playerdatastorage-api-openapi.yml
  format: yaml
  label: Epic Games PlayerDataStorage API
  slug: epic-games-playerdatastorage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epic-games/openapi/epic-games-playerdatastorage-api-openapi.yml
- filename: epic-games-sanctions-api-openapi.yml
  format: yaml
  label: Epic Games Sanctions API
  slug: epic-games-sanctions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epic-games/openapi/epic-games-sanctions-api-openapi.yml
- filename: epic-games-stats-api-openapi.yml
  format: yaml
  label: Epic Games Stats API
  slug: epic-games-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epic-games/openapi/epic-games-stats-api-openapi.yml
- filename: epic-games-titlestorage-api-openapi.yml
  format: yaml
  label: Epic Games TitleStorage API
  slug: epic-games-titlestorage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epic-games/openapi/epic-games-titlestorage-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you reside in the United States of America, the Epic entity entering into this Agreement with you is Epic Games, Inc. If you reside outside the United States of America, the Epic entity entering into this Agreement with you is Epic Games Commerce GmbH.
  entity_types:
  - text: TO ENTER INTO THIS AGREEMENT, YOU MUST BE AN ADULT OF THE LEGAL AGE OF MAJORITY IN YOUR COUNTRY OF RESIDENCE.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial or promotional use
    text: use it commercially or for a promotional purpose
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
name: Epic Games
provenance_date: '2026-11-09'
provider_name: Epic Games
provider_slug: epic-games
slug: epic-games-eligibility
source_date: '2026-11-09'
source_filename: epic-games-eligibility.yml
source_heading: Eligibility
source_page: https://legal.epicgames.com/store/eula
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Epic Games\naid: epic-games\nurl: https://legal.epicgames.com/store/eula\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you reside in the United States of America, the Epic entity entering into this Agreement with you is\n    Epic Games, Inc. If you reside outside the United States of America, the Epic entity entering into this Agreement\n    with you is Epic Games Commerce GmbH.\nentity_types:\n- type: individual\n  text: TO ENTER INTO THIS AGREEMENT, YOU MUST BE AN ADULT OF THE LEGAL AGE OF MAJORITY IN YOUR COUNTRY OF RESIDENCE.\nrestricted_uses:\n- summary: Commercial or promotional\
  \ use\n  text: use it commercially or for a promotional purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/epic-games/eligibility/epic-games-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Epic Games's own page on 2026-11-09.
synthetic: false
tags:
- Achievements
- Anti-Cheat
- Cross-Platform
- EOS
- Epic Online Services
- Game Backend
- Game Development
- Games
- Identity
- Lobby
- Matchmaking
- Multiplayer
- Sessions
- Unreal Engine
- Voice
- Video Games
- Gaming
---
