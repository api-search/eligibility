---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Corporate Flightfox charges a fee for searching, building, booking, amending and supporting travel itineraries.
    type: business
  - text: Personal Flightfox charges a fee for searching and building travel itineraries.
    type: individual
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
name: Flightfox
provenance_date: '2026-11-09'
provider_name: Flightfox
provider_slug: flightfox
slug: flightfox-eligibility
source_date: '2026-11-09'
source_filename: flightfox-eligibility.yml
source_heading: Eligibility
source_page: https://www.flightfox.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flightfox\naid: flightfox\nurl: https://www.flightfox.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Corporate Flightfox charges a fee for searching, building, booking, amending and supporting travel itineraries.\n- type: individual\n  text: Personal Flightfox charges a fee for searching and building travel itineraries.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flightfox/eligibility/flightfox-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Flightfox's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Flights
- Booking
- Group Travel
- Corporate Travel
- Travel Management
---
