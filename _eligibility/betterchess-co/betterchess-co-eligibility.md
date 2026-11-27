---
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
  - summary: No chess cheating or outside help
    text: 'You must not use the Service, its coaching, analysis, or move suggestions to: receive assistance during a live or rated game, online or over-the-board tournament, or any competition where outside help is not allowed'
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
name: BetterChess
provenance_date: '2026-11-09'
provider_name: BetterChess
provider_slug: betterchess-co
slug: betterchess-co-eligibility
source_date: '2026-11-09'
source_filename: betterchess-co-eligibility.yml
source_heading: Eligibility
source_page: https://betterchess.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BetterChess\naid: betterchess-co\nurl: https://betterchess.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No chess cheating or outside help\n  text: 'You must not use the Service, its coaching, analysis, or move suggestions to: receive assistance during\n    a live or rated game, online or over-the-board tournament, or any competition where outside help is not allowed'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/betterchess-co/eligibility/betterchess-co-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from BetterChess's own page on 2026-11-09.
synthetic: false
tags:
- Chess
- Puzzles
- Cards
- E-Commerce
- Education
---
