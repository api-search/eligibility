---
api_specs:
- filename: cardmind-app-openapi-generated.yml
  format: yaml
  label: CardMind API
  slug: cardmind-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cardmind-app/openapi/_ae-authored/cardmind-app-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 13 or older. Under 18 you need a parent or guardian to agree on your behalf.
    type: individual
  minimum_age:
    text: You must be 13 or older.
    value: '13'
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
name: CardMind
provenance_date: '2026-11-09'
provider_name: CardMind
provider_slug: cardmind-app
slug: cardmind-app-eligibility
source_date: '2026-11-09'
source_filename: cardmind-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.cardmind.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CardMind\naid: cardmind-app\nurl: https://www.cardmind.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 13 or older. Under 18 you need a parent or guardian to agree on your behalf.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 or older.\n"
source_yaml_url: https://artifacts.apis.io/cardmind-app/eligibility/cardmind-app-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from CardMind's own page on 2026-11-09.
synthetic: false
tags:
- Market Intelligence
- Price Data
- Signals
- Ban Watch
- Deck Intelligence
---
