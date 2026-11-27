---
api_specs:
- filename: foundplay-io-games-api-openapi.yml
  format: yaml
  label: foundplay-io Games API
  slug: foundplay-io-games-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foundplay-io/openapi/foundplay-io-games-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 to use Foundplay. If you're under 18, use it with a parent's or guardian's permission.
    value: '13'
  restricted_uses:
  - summary: Boost content restrictions
    text: Fan games and copies of big franchises, gambling, adult content, and token sales or similar promotions (crypto and NFTs included) aren't allowed
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Boosts are reviewed automatically, and if the review isn't sure, a person checks the game, usually within a day.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: foundplay-io
provenance_date: '2026-11-09'
provider_name: foundplay-io
provider_slug: foundplay-io
slug: foundplay-io-eligibility
source_date: '2026-11-09'
source_filename: foundplay-io-eligibility.yml
source_heading: Eligibility
source_page: https://foundplay.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: foundplay-io\naid: foundplay-io\nurl: https://foundplay.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Boost content restrictions\n  text: Fan games and copies of big franchises, gambling, adult content, and token sales or similar promotions (crypto\n    and NFTs included) aren't allowed\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Boosts are reviewed automatically, and if the review isn't sure, a person checks the game, usually within\n    a day.\nminimum_age:\n  value: '13'\n  text: You\
  \ must be at least 13 to use Foundplay. If you're under 18, use it with a parent's or guardian's permission.\n"
source_yaml_url: https://artifacts.apis.io/foundplay-io/eligibility/foundplay-io-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from foundplay-io's own page on 2026-11-09.
synthetic: false
tags:
- Games
- Browser
- Indie
- AI-Generated
- Free
---
