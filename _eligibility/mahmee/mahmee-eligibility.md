---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: When you create an account with us, you guarantee that you are above the age of 18
    type: individual
  minimum_age:
    text: you guarantee that you are above the age of 18
    value: '18'
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
name: Mahmee
provenance_date: '2026-11-10'
provider_name: Mahmee
provider_slug: mahmee
slug: mahmee-eligibility
source_date: '2026-11-10'
source_filename: mahmee-eligibility.yml
source_heading: Eligibility
source_page: https://www.mahmee.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mahmee\naid: mahmee\nurl: https://www.mahmee.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: When you create an account with us, you guarantee that you are above the age of 18\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you guarantee that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/mahmee/eligibility/mahmee-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Mahmee's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Maternal Health
- Healthcare
- Postpartum Care
- Lactation
- Telehealth
- Femtech
---
