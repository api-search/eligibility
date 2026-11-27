---
api_specs:
- filename: flashodds-live-api-openapi.json
  format: json
  label: Sorqen API API
  slug: sorqen-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flashodds-live/openapi/_original/flashodds-live-api-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 or older to hold an account, and old enough to gamble legally where you live if you intend to.
    type: individual
  minimum_age:
    text: You must be 18 or older to hold an account
    value: '18'
  restricted_uses:
  - summary: Gambling legality
    text: Sports betting is restricted or illegal in many places. Complying with the law where you are is your responsibility.
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
name: flashodds-live
provenance_date: '2026-11-09'
provider_name: flashodds-live
provider_slug: flashodds-live
slug: flashodds-live-eligibility
source_date: '2026-11-09'
source_filename: flashodds-live-eligibility.yml
source_heading: Eligibility
source_page: https://flashodds.live/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: flashodds-live\naid: flashodds-live\nurl: https://flashodds.live/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 or older to hold an account, and old enough to gamble legally where you live if you intend\n    to.\nrestricted_uses:\n- summary: Gambling legality\n  text: Sports betting is restricted or illegal in many places. Complying with the law where you are is your responsibility.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must\
  \ be 18 or older to hold an account\n"
source_yaml_url: https://artifacts.apis.io/flashodds-live/eligibility/flashodds-live-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from flashodds-live's own page on 2026-11-09.
synthetic: false
tags:
- Sports
- Betting
- Odds
- Real-Time
- Analytics
---
