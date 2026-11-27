---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Russian card payments are for individuals and sole proprietors
    type: individual
  - text: companies can ask support for an invoice under a contract
    type: business
  minimum_age:
    text: null
    value: null
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
name: Car Dealer Tracker
provenance_date: '2026-11-09'
provider_name: Car Dealer Tracker
provider_slug: cardealertracker-app
slug: cardealertracker-app-eligibility
source_date: '2026-11-09'
source_filename: cardealertracker-app-eligibility.yml
source_heading: Eligibility
source_page: https://cardealertracker.app/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Car Dealer Tracker\naid: cardealertracker-app\nurl: https://cardealertracker.app/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Russian card payments are for individuals and sole proprietors\n- type: business\n  text: companies can ask support for an invoice under a contract\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cardealertracker-app/eligibility/cardealertracker-app-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Car Dealer Tracker's own page on 2026-11-09.
synthetic: false
tags:
- Dealership Software
- Inventory
- Vehicle Expenses
- Profit Tracking
- CRM
- Mobile App
- Voice Input
- Accounting
---
