---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age and act in your role as a private consumer to make a booking on the Portal.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age and act in your role as a private consumer to make a booking on the Portal.
    value: '18'
  restricted_uses:
  - summary: No unaccompanied minor bookings
    text: We do not mediate the booking of any tickets for unaccompanied minors.
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
name: Flight Network
provenance_date: '2026-11-09'
provider_name: Flight Network
provider_slug: flight-network
slug: flight-network-eligibility
source_date: '2026-11-09'
source_filename: flight-network-eligibility.yml
source_heading: Eligibility
source_page: https://ca.flightnetwork.com/rf/travel-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flight Network\naid: flight-network\nurl: https://ca.flightnetwork.com/rf/travel-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age and act in your role as a private consumer to make a booking on the\n    Portal.\nrestricted_uses:\n- summary: No unaccompanied minor bookings\n  text: We do not mediate the booking of any tickets for unaccompanied minors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least\
  \ 18 years of age and act in your role as a private consumer to make a booking on the\n    Portal.\n"
source_yaml_url: https://artifacts.apis.io/flight-network/eligibility/flight-network-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Flight Network's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Canada
- Aviation
- Airlines
- OTA
- Booking
- Distribution
- Flights
- Hotels
- Car Rental
- GDS
---
