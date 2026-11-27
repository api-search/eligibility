---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: is provided for residents of Australia only.
  entity_types:
  - text: The term "you" as used in these Terms refers to all individuals and/or entities accessing this Site for any reason.
    type: individual
  minimum_age:
    text: you are of sufficient legal age to use this Site
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: You must only use this Site for lawful purposes and in a responsible and co-operative manner.
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
name: Flight Centre Travel Group
provenance_date: '2026-11-09'
provider_name: Flight Centre Travel Group
provider_slug: flight-centre
slug: flight-centre-eligibility
source_date: '2026-11-09'
source_filename: flight-centre-eligibility.yml
source_heading: Eligibility
source_page: https://help.flightcentre.com.au/article/terms-of-use-au
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flight Centre Travel Group\naid: flight-centre\nurl: https://help.flightcentre.com.au/article/terms-of-use-au\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://help.flightcentre.com.au/article/booking-terms-conditions-au\n  - https://help.flightcentre.com.au/article/terms-of-use-au\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: is provided for residents of Australia only.\nentity_types:\n- type: individual\n  text: The term \"you\" as used in these Terms refers to all individuals and/or entities accessing this Site for\n    any reason.\nrestricted_uses:\n- summary: Lawful use only\n  text: You must\
  \ only use this Site for lawful purposes and in a responsible and co-operative manner.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of sufficient legal age to use this Site\n"
source_yaml_url: https://artifacts.apis.io/flight-centre/eligibility/flight-centre-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Flight Centre Travel Group's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Australia
- Corporate Travel
- Travel Agency
- Distribution
- NDC
- Aviation
- Booking
- Hotels
- Aggregator
---
