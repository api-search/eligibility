---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You agree and confirm that: you are at least 18 years of age'
    type: individual
  - source: https://westjettravelagents.com/policy-library/ticketing-policy/
    text: Each Agent which engages in Ticketing or Booking agrees that each of its directors, officers, employees, agents, partners and contractors shall comply with this Policy
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unauthorized access or use
    text: Use of the WestJet website in any jurisdiction not giving effect to all provisions of these terms and conditions is unauthorized.
  - source: https://westjettravelagents.com/policy-library/ticketing-policy/
    summary: No speculative or fictitious bookings
    text: 'No Agent shall: (a) make any Fraudulent Booking; (b) withdraw any WestJet Inventory or make Booking unless the Agent has received a specific request from a potential Guest'
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
name: WestJet
provenance_date: '2026-11-10'
provider_name: WestJet
provider_slug: westjet
slug: westjet-eligibility
source_date: '2026-11-10'
source_filename: westjet-eligibility.yml
source_heading: Eligibility
source_page: https://www.westjet.com/en-ca/legal/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WestJet\naid: westjet\nurl: https://www.westjet.com/en-ca/legal/terms-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://westjettravelagents.com/policy-library/ticketing-policy/\n  - https://www.westjet.com/en-ca/legal/terms-use\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You agree and confirm that: you are at least 18 years of age'\n- type: business\n  text: Each Agent which engages in Ticketing or Booking agrees that each of its directors, officers, employees,\n    agents, partners and contractors shall comply with this Policy\n  source: https://westjettravelagents.com/policy-library/ticketing-policy/\n\
  restricted_uses:\n- summary: Unauthorized access or use\n  text: Use of the WestJet website in any jurisdiction not giving effect to all provisions of these terms and conditions\n    is unauthorized.\n- summary: No speculative or fictitious bookings\n  text: 'No Agent shall: (a) make any Fraudulent Booking; (b) withdraw any WestJet Inventory or make Booking unless\n    the Agent has received a specific request from a potential Guest'\n  source: https://westjettravelagents.com/policy-library/ticketing-policy/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/westjet/eligibility/westjet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from WestJet's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Canada
- Aviation
- Airlines
- Distribution
- NDC
- Booking
- Cargo
- Loyalty
---
