---
api_specs:
- filename: postman.yaml
  format: yaml
  label: Sportmonks Cricket API
  slug: cricket-api
  spec_type: Postman
  url: https://cricket-postman.sportmonks.com/
- filename: sportmonks-fixtures-api-openapi.yml
  format: yaml
  label: Sportmonks Fixtures API
  slug: sportmonks-fixtures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sportmonks/openapi/sportmonks-fixtures-api-openapi.yml
- filename: sportmonks-leagues-api-openapi.yml
  format: yaml
  label: Sportmonks Leagues API
  slug: sportmonks-leagues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sportmonks/openapi/sportmonks-leagues-api-openapi.yml
- filename: sportmonks-livescores-api-openapi.yml
  format: yaml
  label: Sportmonks Livescores API
  slug: sportmonks-livescores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sportmonks/openapi/sportmonks-livescores-api-openapi.yml
- filename: sportmonks-odds-api-openapi.yml
  format: yaml
  label: Sportmonks Odds API
  slug: sportmonks-odds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sportmonks/openapi/sportmonks-odds-api-openapi.yml
- filename: sportmonks-players-api-openapi.yml
  format: yaml
  label: Sportmonks Players API
  slug: sportmonks-players-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sportmonks/openapi/sportmonks-players-api-openapi.yml
- filename: sportmonks-predictions-api-openapi.yml
  format: yaml
  label: Sportmonks Predictions API
  slug: sportmonks-predictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sportmonks/openapi/sportmonks-predictions-api-openapi.yml
- filename: sportmonks-schedules-api-openapi.yml
  format: yaml
  label: Sportmonks Schedules API
  slug: sportmonks-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sportmonks/openapi/sportmonks-schedules-api-openapi.yml
- filename: sportmonks-seasons-api-openapi.yml
  format: yaml
  label: Sportmonks Seasons API
  slug: sportmonks-seasons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sportmonks/openapi/sportmonks-seasons-api-openapi.yml
- filename: sportmonks-standings-api-openapi.yml
  format: yaml
  label: Sportmonks Standings API
  slug: sportmonks-standings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sportmonks/openapi/sportmonks-standings-api-openapi.yml
- filename: sportmonks-teams-api-openapi.yml
  format: yaml
  label: Sportmonks Teams API
  slug: sportmonks-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sportmonks/openapi/sportmonks-teams-api-openapi.yml
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
  - summary: Personal, non-commercial use of site material
    text: Usage of material from Sportmonks is strictly for personal and non-commercial use.
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
name: Sportmonks
provenance_date: '2026-11-10'
provider_name: Sportmonks
provider_slug: sportmonks
slug: sportmonks-eligibility
source_date: '2026-11-10'
source_filename: sportmonks-eligibility.yml
source_heading: Eligibility
source_page: https://www.sportmonks.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sportmonks\naid: sportmonks\nurl: https://www.sportmonks.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal, non-commercial use of site material\n  text: Usage of material from Sportmonks is strictly for personal and non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sportmonks/eligibility/sportmonks-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Sportmonks's own page on 2026-11-10.
synthetic: false
tags:
- Cricket
- Data
- Football
- Formula 1
- Live Scores
- Motorsports
- Real-Time
- Soccer
- Sports
- Sports Data
- Statistics
---
