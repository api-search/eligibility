---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old, and able to agree to these terms where you live.
    type: individual
  - text: If you're using Body Lab for an organization, you confirm you can agree on its behalf.
    type: business
  minimum_age:
    text: You must be at least 16 years old
    value: '16'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with a code sent to your email
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Body Lab
provenance_date: '2026-11-09'
provider_name: Body Lab
provider_slug: bodylab-lol
slug: bodylab-lol-eligibility
source_date: '2026-11-09'
source_filename: bodylab-lol-eligibility.yml
source_heading: Eligibility
source_page: https://bodylab.lol/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Body Lab\naid: bodylab-lol\nurl: https://bodylab.lol/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old, and able to agree to these terms where you live.\n- type: business\n  text: If you're using Body Lab for an organization, you confirm you can agree on its behalf.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with a code sent to your email\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old\n"
source_yaml_url: https://artifacts.apis.io/bodylab-lol/eligibility/bodylab-lol-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Body Lab's own page on 2026-11-09.
synthetic: false
tags:
- Fitness
- Health
- Training
- Free
- Company
---
