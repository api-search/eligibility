---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 16 or older.
    type: individual
  minimum_age:
    text: You must be 16 or older.
    value: '16'
  restricted_uses:
  - summary: Not medical advice
    text: Anatome is not medical advice.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A full account needs a working email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Anatome
provenance_date: '2026-11-09'
provider_name: Anatome
provider_slug: anatome-dev
slug: anatome-dev-eligibility
source_date: '2026-11-09'
source_filename: anatome-dev-eligibility.yml
source_heading: Eligibility
source_page: https://anatome.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anatome\naid: anatome-dev\nurl: https://anatome.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 16 or older.\nrestricted_uses:\n- summary: Not medical advice\n  text: Anatome is not medical advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A full account needs a working email address.\nminimum_age:\n  value: '16'\n  text: You must be 16 or older.\n"
source_yaml_url: https://artifacts.apis.io/anatome-dev/eligibility/anatome-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Anatome's own page on 2026-11-09.
synthetic: false
tags:
- Fitness
- Nutrition
- Artificial Intelligence
- Health
- Workout Tracking
---
