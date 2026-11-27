---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our Services are currently not available in all US states and territories. We will inform you during the booking process if our Services are not yet available in the state or territory where you reside.
  entity_types:
  - text: you use our Services only for non-commercial, personal purposes
    type: individual
  minimum_age:
    text: you are of legal age in the jurisdiction in which you reside and have the legal capacity and authority to enter into contracts
    value: null
  restricted_uses:
  - summary: Non-commercial personal use only
    text: you use our Services only for non-commercial, personal purposes
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
name: Tourlane
provenance_date: '2026-11-10'
provider_name: Tourlane
provider_slug: tourlane
slug: tourlane-eligibility
source_date: '2026-11-10'
source_filename: tourlane-eligibility.yml
source_heading: Eligibility
source_page: https://www.tourlane.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tourlane\naid: tourlane\nurl: https://www.tourlane.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Our Services are currently not available in all US states and territories. We will inform you during the\n    booking process if our Services are not yet available in the state or territory where you reside.\nentity_types:\n- type: individual\n  text: you use our Services only for non-commercial, personal purposes\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: you use our Services only for non-commercial, personal\
  \ purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age in the jurisdiction in which you reside and have the legal capacity and authority to\n    enter into contracts\n"
source_yaml_url: https://artifacts.apis.io/tourlane/eligibility/tourlane-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tourlane's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Travel
- Trip Planning
- Tours
- Booking
- Tailor-Made Trips
---
