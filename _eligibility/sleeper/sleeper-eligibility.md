---
api_specs:
- filename: sleeper-drafts-api-openapi.yml
  format: yaml
  label: Sleeper Drafts API
  slug: sleeper-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-drafts-api-openapi.yml
- filename: sleeper-leagues-api-openapi.yml
  format: yaml
  label: Sleeper Leagues API
  slug: sleeper-leagues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-leagues-api-openapi.yml
- filename: sleeper-matchups-api-openapi.yml
  format: yaml
  label: Sleeper Matchups API
  slug: sleeper-matchups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-matchups-api-openapi.yml
- filename: sleeper-players-api-openapi.yml
  format: yaml
  label: Sleeper Players API
  slug: sleeper-players-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-players-api-openapi.yml
- filename: sleeper-playoffs-api-openapi.yml
  format: yaml
  label: Sleeper Playoffs API
  slug: sleeper-playoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-playoffs-api-openapi.yml
- filename: sleeper-state-api-openapi.yml
  format: yaml
  label: Sleeper State API
  slug: sleeper-state-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-state-api-openapi.yml
- filename: sleeper-transactions-api-openapi.yml
  format: yaml
  label: Sleeper Transactions API
  slug: sleeper-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-transactions-api-openapi.yml
- filename: sleeper-users-api-openapi.yml
  format: yaml
  label: Sleeper Users API
  slug: sleeper-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Be a legal resident of the United States or Canada
  entity_types:
  - text: Only one (1) account per verified person is permitted.
    type: individual
  minimum_age:
    text: must be at least 13 years of age and have parental consent (if under the age of 18) to use the Services
    value: '13'
  restricted_uses:
  - summary: Contests in Excluded States
    text: We limit access to the Contests in the Excluded States.
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
name: Sleeper
provenance_date: '2026-11-10'
provider_name: Sleeper
provider_slug: sleeper
slug: sleeper-eligibility
source_date: '2026-11-10'
source_filename: sleeper-eligibility.yml
source_heading: Eligibility
source_page: https://support.sleeper.com/en/articles/5486620-general-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sleeper\naid: sleeper\nurl: https://support.sleeper.com/en/articles/5486620-general-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Be a legal resident of the United States or Canada\nentity_types:\n- type: individual\n  text: Only one (1) account per verified person is permitted.\nrestricted_uses:\n- summary: Contests in Excluded States\n  text: We limit access to the Contests in the Excluded States.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: must be at least\
  \ 13 years of age and have parental consent (if under the age of 18) to use the Services\n"
source_yaml_url: https://artifacts.apis.io/sleeper/eligibility/sleeper-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Sleeper's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fantasy Sports
- Sports
- Fantasy Football
- Gaming
- Sports Data
- League
- Consumer
---
