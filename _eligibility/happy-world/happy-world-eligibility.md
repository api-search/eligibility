---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must meet the minimum legal age in your country to use the App.
    type: individual
  minimum_age:
    text: You must meet the minimum legal age in your country to use the App.
    value: null
  restricted_uses:
  - summary: Illegal or fraudulent activities
    text: Use the App for illegal or fraudulent activities.
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
name: Happy World
provenance_date: '2026-11-09'
provider_name: Happy World
provider_slug: happy-world
slug: happy-world-eligibility
source_date: '2026-11-09'
source_filename: happy-world-eligibility.yml
source_heading: Eligibility
source_page: https://www.getspice.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Happy World\naid: happy-world\nurl: https://www.getspice.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must meet the minimum legal age in your country to use the App.\nrestricted_uses:\n- summary: Illegal or fraudulent activities\n  text: Use the App for illegal or fraudulent activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must meet the minimum legal age in your country to use the App.\n"
source_yaml_url: https://artifacts.apis.io/happy-world/eligibility/happy-world-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Happy World's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Dining
- Restaurant
- Payments
- Rewards
- Loyalty
- Cashback
- Mobile App
- Fintech
- Saudi Arabia
---
