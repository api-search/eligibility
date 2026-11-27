---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Sign-in is by email.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ask Recipes
provenance_date: '2026-11-09'
provider_name: Ask Recipes
provider_slug: ask-recipes
slug: ask-recipes-eligibility
source_date: '2026-11-09'
source_filename: ask-recipes-eligibility.yml
source_heading: Eligibility
source_page: https://ask.recipes/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ask Recipes\naid: ask-recipes\nurl: https://ask.recipes/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Sign-in is by email.\nminimum_age:\n  value: '18'\n  text: You must be at least 18.\n"
source_yaml_url: https://artifacts.apis.io/ask-recipes/eligibility/ask-recipes-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from Ask Recipes's own page on 2026-11-09.
synthetic: false
tags:
- AI Cooking Assistant
- Recipe Search
---
