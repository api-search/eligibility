---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'For anything other people use: an app, site, bot or channel, paid or free'
    type: business
  - text: 'Personal use: trying the API, your own projects'
    type: individual
  - text: Academic access · free (institutions)
    type: nonprofit
  minimum_age:
    text: 18+ · Statistics, not betting advice
    value: '18'
  restricted_uses:
  - summary: Free key not for apps/sites/bots
    text: For trying the API and your own projects; an app, site, bot or channel that other people use needs the Commercial plan .
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
name: Football Charts
provenance_date: '2026-11-09'
provider_name: Football Charts
provider_slug: football-charts
slug: football-charts-eligibility
source_date: '2026-11-09'
source_filename: football-charts-eligibility.yml
source_heading: Eligibility
source_page: https://www.football-charts.com/developers
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Football Charts\naid: football-charts\nurl: https://www.football-charts.com/developers\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'For anything other people use: an app, site, bot or channel, paid or free'\n- type: individual\n  text: 'Personal use: trying the API, your own projects'\n- type: nonprofit\n  text: Academic access · free (institutions)\nrestricted_uses:\n- summary: Free key not for apps/sites/bots\n  text: For trying the API and your own projects; an app, site, bot or channel that other people use needs the Commercial\n\
  \    plan .\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 18+ · Statistics, not betting advice\n"
source_yaml_url: https://artifacts.apis.io/football-charts/eligibility/football-charts-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Football Charts's own page on 2026-11-09.
synthetic: false
tags:
- Football
- Soccer
- Sports
- Sports Data
- Statistics
- Results
- Standings
- Fixtures
- Predictions
- probability-models
- MonteCarlo
- MCP
- Agent-Native
---
