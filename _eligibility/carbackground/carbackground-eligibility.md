---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) to create an account.
    type: individual
  - text: An individual or organizational profile created on CarBG.
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction) to create an account.
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing uploads
    text: Upload content that infringes intellectual property or privacy rights, is illegal, harmful or obscene.
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
name: Car Background AI
provenance_date: '2026-11-09'
provider_name: Car Background AI
provider_slug: carbackground
slug: carbackground-eligibility
source_date: '2026-11-09'
source_filename: carbackground-eligibility.yml
source_heading: Eligibility
source_page: https://carbackground.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Car Background AI\naid: carbackground\nurl: https://carbackground.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to create an account.\n- type: business\n  text: An individual or organizational profile created on CarBG.\nrestricted_uses:\n- summary: Unlawful or infringing uploads\n  text: Upload content that infringes intellectual property or privacy rights, is illegal, harmful or obscene.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to create an account.\n"
source_yaml_url: https://artifacts.apis.io/carbackground/eligibility/carbackground-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Car Background AI's own page on 2026-11-09.
synthetic: false
tags:
- Car Photo Editing
- Bulk Editing
- Dealership Branding
- Automotive Marketplace
- License Plate Blur
- Background Generation
---
