---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You represent to Glambot that you: 1) have full power and authority to enter into this Agreement, 2) have full power and authority to engage in your billing and other activities in connection with the Services provided by Glambot, and 3) you are eighteen (18) years of age or older.'
    type: individual
  minimum_age:
    text: you are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: No use beyond shopping and beauty information
    text: you may not use the Site for any other purpose.
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
name: Glambot
provenance_date: '2026-11-09'
provider_name: Glambot
provider_slug: glambot
slug: glambot-eligibility
source_date: '2026-11-09'
source_filename: glambot-eligibility.yml
source_heading: Eligibility
source_page: https://www.glambot.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Glambot\naid: glambot\nurl: https://www.glambot.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You represent to Glambot that you: 1) have full power and authority to enter into this Agreement, 2) have\n    full power and authority to engage in your billing and other activities in connection with the Services provided\n    by Glambot, and 3) you are eighteen (18) years of age or older.'\nrestricted_uses:\n- summary: No use beyond shopping and beauty information\n  text: you may not use the Site for any other purpose.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/glambot/eligibility/glambot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Glambot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Beauty
- Cosmetics
- Makeup
- Marketplace
- E-Commerce
- Resale
- Consumer
---
