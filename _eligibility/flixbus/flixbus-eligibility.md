---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-private or commercial use
    text: Non-private or commercial use of the Flix web portal is not permitted.
  - summary: Resale of tickets and vouchers
    text: The commercial use and, in particular, the resale of tickets, is not permitted
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
name: FlixBus
provenance_date: '2026-11-09'
provider_name: FlixBus
provider_slug: flixbus
slug: flixbus-eligibility
source_date: '2026-11-09'
source_filename: flixbus-eligibility.yml
source_heading: Eligibility
source_page: https://global.flixbus.com/general-terms-business-and-booking-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FlixBus\naid: flixbus\nurl: https://global.flixbus.com/general-terms-business-and-booking-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-private or commercial use\n  text: Non-private or commercial use of the Flix web portal is not permitted.\n- summary: Resale of tickets and vouchers\n  text: The commercial use and, in particular, the resale of tickets, is not permitted\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flixbus/eligibility/flixbus-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from FlixBus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Transportation
- Travel
- Mobility
- Bus
- Rail
- Ticketing
- GTFS
- Open Data
- Distribution
---
