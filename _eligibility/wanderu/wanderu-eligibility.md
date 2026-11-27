---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Wanderu Service is intended for use by individuals who are 18 years of age or older, or the age of majority in their jurisdiction if higher.
    type: individual
  minimum_age:
    text: The Wanderu Service is intended for use by individuals who are 18 years of age or older, or the age of majority in their jurisdiction if higher.
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent reservations
    text: You may not use the Wanderu Service for any false, fraudulent reservations or reservations for commercial gain.
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
name: Wanderu
provenance_date: '2026-11-10'
provider_name: Wanderu
provider_slug: wanderu
slug: wanderu-eligibility
source_date: '2026-11-10'
source_filename: wanderu-eligibility.yml
source_heading: Eligibility
source_page: https://www.wanderu.com/en-us/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wanderu\naid: wanderu\nurl: https://www.wanderu.com/en-us/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Wanderu Service is intended for use by individuals who are 18 years of age or older, or the age of majority\n    in their jurisdiction if higher.\nrestricted_uses:\n- summary: Unlawful or fraudulent reservations\n  text: You may not use the Wanderu Service for any false, fraudulent reservations or reservations for commercial\n    gain.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: The Wanderu Service is intended for use by individuals who are 18 years of age or older, or the age of majority\n    in their jurisdiction if higher.\n"
source_yaml_url: https://artifacts.apis.io/wanderu/eligibility/wanderu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Wanderu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Transportation
- Bus
- Trains
- Booking
- Metasearch
- Ticketing
---
