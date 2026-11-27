---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to register an Account.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to register an Account.
    value: '18'
  restricted_uses:
  - summary: Export and sanctions compliance
    text: You must adhere to the applicable export and customs laws and regulations.
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
name: SeeChange
provenance_date: '2026-11-10'
provider_name: SeeChange
provider_slug: seechange
slug: seechange-eligibility
source_date: '2026-11-10'
source_filename: seechange-eligibility.yml
source_heading: Eligibility
source_page: https://seechange.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SeeChange\naid: seechange\nurl: https://seechange.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to register an Account.\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: You must adhere to the applicable export and customs laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to register an Account.\n"
source_yaml_url: https://artifacts.apis.io/seechange/eligibility/seechange-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SeeChange's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- Computer Vision
- Artificial Intelligence
- Loss Prevention
- Inventory
---
