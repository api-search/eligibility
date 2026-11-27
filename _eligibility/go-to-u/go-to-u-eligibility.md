---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer - an individual and/or legal entity that uses the Services.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No duplicate accounts
    text: The Customer may maintain only one account/profile per individual (or, for entities, per authorized user) unless expressly authorized by the Company.
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
name: Go To-U
provenance_date: '2026-11-09'
provider_name: Go To-U
provider_slug: go-to-u
slug: go-to-u-eligibility
source_date: '2026-11-09'
source_filename: go-to-u-eligibility.yml
source_heading: Eligibility
source_page: https://goto-u.com/en/public-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Go To-U\naid: go-to-u\nurl: https://goto-u.com/en/public-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer - an individual and/or legal entity that uses the Services.\nrestricted_uses:\n- summary: No duplicate accounts\n  text: The Customer may maintain only one account/profile per individual (or, for entities, per authorized user)\n    unless expressly authorized by the Company.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/go-to-u/eligibility/go-to-u-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Go To-U's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EV Charging
- Electric Vehicles
- Energy
- Mobility
- Charge Point Operator
- Sustainability
- Payments
---
