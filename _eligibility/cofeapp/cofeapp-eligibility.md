---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'The user presents and warrants that: They are 18 years of age or older; They have the capacity to form a binding contract;'
    type: individual
  minimum_age:
    text: They are 18 years of age or older
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
name: Cofeapp
provenance_date: '2026-11-09'
provider_name: Cofeapp
provider_slug: cofeapp
slug: cofeapp-eligibility
source_date: '2026-11-09'
source_filename: cofeapp-eligibility.yml
source_heading: Eligibility
source_page: https://www.cofeapp.com/terms-and-conditions-users
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cofeapp\naid: cofeapp\nurl: https://www.cofeapp.com/terms-and-conditions-users\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'The user presents and warrants that: They are 18 years of age or older; They have the capacity to form\n    a binding contract;'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: They are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/cofeapp/eligibility/cofeapp-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Cofeapp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Platform
- Artificial Intelligence
- Commerce
- Procurement
- MENA
---
