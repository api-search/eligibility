---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Imported recipes for personal use only
    text: Imported recipes are for personal, non-commercial use only
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must create an account to use the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Chewable
provenance_date: '2026-11-09'
provider_name: Chewable
provider_slug: chewable-fit
slug: chewable-fit-eligibility
source_date: '2026-11-09'
source_filename: chewable-fit-eligibility.yml
source_heading: Eligibility
source_page: https://foodie.chewable.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chewable\naid: chewable-fit\nurl: https://foodie.chewable.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://foodie.chewable.app/terms\n  - https://thraed.chewable.app/terms\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service.\nrestricted_uses:\n- summary: Imported recipes for personal use only\n  text: Imported recipes are for personal, non-commercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must create an account to use the Service.\nminimum_age:\n\
  \  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/chewable-fit/eligibility/chewable-fit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Chewable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobile App
- iOS
- Recipes
- Meal Planning
- Fitness
- Strength Training
- Fashion
- Virtual Try-On
- Artificial Intelligence
- MCP
---
