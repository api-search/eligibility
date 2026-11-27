---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The platform is controlled and offered by FabHotels from its facilities in India. FabHotels makes no representations that the FabHotels platform is appropriate or available for use in other locations.
  entity_types:
  - text: an individual subscriber, customer, member, or user of at least 18 years of age
    type: individual
  - text: or a single entity
    type: business
  minimum_age:
    text: The primary guest must be at least 18 years old to be able to check into the hotel.
    value: '18'
  restricted_uses:
  - summary: Restraints on conduct
    text: 'you hereby agree to refrain from the following: violating the rights of another individual or entity, including but not limited to any of such party''s intellectual property rights;'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: It is mandatory for guests to present valid photo identification at the time of check-in.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FabHotels
provenance_date: '2026-11-09'
provider_name: FabHotels
provider_slug: fabhotels
slug: fabhotels-eligibility
source_date: '2026-11-09'
source_filename: fabhotels-eligibility.yml
source_heading: Eligibility
source_page: https://www.fabhotels.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FabHotels\naid: fabhotels\nurl: https://www.fabhotels.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The platform is controlled and offered by FabHotels from its facilities in India. FabHotels makes no representations\n    that the FabHotels platform is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: an individual subscriber, customer, member, or user of at least 18 years of age\n- type: business\n  text: or a single entity\nrestricted_uses:\n- summary: Restraints on conduct\n  text: 'you hereby agree to refrain\
  \ from the following: violating the rights of another individual or entity, including\n    but not limited to any of such party''s intellectual property rights;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: It is mandatory for guests to present valid photo identification at the time of check-in.\nminimum_age:\n  value: '18'\n  text: The primary guest must be at least 18 years old to be able to check into the hotel.\n"
source_yaml_url: https://artifacts.apis.io/fabhotels/eligibility/fabhotels-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from FabHotels's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Travel
- Hospitality
- Hotels
- Booking
- India
---
