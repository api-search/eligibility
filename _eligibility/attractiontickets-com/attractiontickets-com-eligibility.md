---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customers outside of the UK may be asked for additional proof of address before tickets can be sent.
  entity_types:
  - text: You must be 18 years old at the time of booking (21 years old if staying at a Universal Orlando Resort Hotel or booking an Orlando Villa) to book and possess the legal capacity and authority to act and travel as the lead name on the booking.
    type: individual
  minimum_age:
    text: You must be 18 years old at the time of booking (21 years old if staying at a Universal Orlando Resort Hotel or booking an Orlando Villa)
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
name: Attraction Tickets
provenance_date: '2026-11-09'
provider_name: Attraction Tickets
provider_slug: attractiontickets-com
slug: attractiontickets-com-eligibility
source_date: '2026-11-09'
source_filename: attractiontickets-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.attractiontickets.com/en/terms-and-conditions.htm
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Attraction Tickets\naid: attractiontickets-com\nurl: https://www.attractiontickets.com/en/terms-and-conditions.htm\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customers outside of the UK may be asked for additional proof of address before tickets can be sent.\nentity_types:\n- type: individual\n  text: You must be 18 years old at the time of booking (21 years old if staying at a Universal Orlando Resort Hotel\n    or booking an Orlando Villa) to book and possess the legal capacity and authority to act and travel as the lead\n    name on the booking.\nrestricted_uses:\
  \ []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years old at the time of booking (21 years old if staying at a Universal Orlando Resort Hotel\n    or booking an Orlando Villa)\n"
source_yaml_url: https://artifacts.apis.io/attractiontickets-com/eligibility/attractiontickets-com-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Attraction Tickets's own page on 2026-11-09.
synthetic: false
tags:
- Ticketing
- Travel
- Orlando
- Disney
- Universal
---
