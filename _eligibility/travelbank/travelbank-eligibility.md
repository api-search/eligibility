---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you have the authority to enter into the TOU agreement personally or on behalf of the company you have named as the user
    type: business
  minimum_age:
    text: You represent that you are (1) at least sixteen years of age, or of legal age to form a binding contract in your jurisdiction
    value: '16'
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
name: TravelBank
provenance_date: '2026-11-10'
provider_name: TravelBank
provider_slug: travelbank
slug: travelbank-eligibility
source_date: '2026-11-10'
source_filename: travelbank-eligibility.yml
source_heading: Eligibility
source_page: https://travelbank.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TravelBank\naid: travelbank\nurl: https://travelbank.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you have the authority to enter into the TOU agreement personally or on behalf of the company you have named\n    as the user\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You represent that you are (1) at least sixteen years of age, or of legal age to form a binding contract\n    in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/travelbank/eligibility/travelbank-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from TravelBank's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Travel
- Expense Management
- Corporate Cards
- Fintech
- Travel Booking
---
