---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be the age of majority in your province or territory to hold a NoshUp account.
    type: individual
  minimum_age:
    text: You must be the age of majority in your province or territory to hold a NoshUp account.
    value: age of majority in province or territory
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
name: noshup-ca
provenance_date: '2026-11-10'
provider_name: noshup-ca
provider_slug: noshup-ca
slug: noshup-ca-eligibility
source_date: '2026-11-10'
source_filename: noshup-ca-eligibility.yml
source_heading: Eligibility
source_page: https://noshup.ca/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: noshup-ca\naid: noshup-ca\nurl: https://noshup.ca/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be the age of majority in your province or territory to hold a NoshUp account.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in province or territory\n  text: You must be the age of majority in your province or territory to hold a NoshUp account.\n"
source_yaml_url: https://artifacts.apis.io/noshup-ca/eligibility/noshup-ca-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from noshup-ca's own page on 2026-11-10.
synthetic: false
tags:
- Meal Planning
- Recipes
- Grocery
- Canadian
- AI Integration
---
