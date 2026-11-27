---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Web Services can be accessed from all 50 U.S. states, as well as from other countries around the world.
  entity_types:
  - text: you represent that you are at least eighteen (18) years of age or the legal age of majority in your jurisdiction (whichever is greater)
    type: individual
  - text: If you access the Web Services on behalf of any organization, your organization shall be bound to these Terms and be liable for any breach by you.
    type: business
  minimum_age:
    text: you represent that you are at least eighteen (18) years of age or the legal age of majority in your jurisdiction (whichever is greater)
    value: '18'
  restricted_uses:
  - summary: Reservations of more than nine rooms
    text: Reservations made by one or more individuals or by an agency on the Web Services, on behalf of one or more proposed guests, and involving more than nine (9) rooms at the same hotel for the same period of stay, must be made directly through the hotel.
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
name: Wyndham Hotels & Resorts
provenance_date: '2026-11-10'
provider_name: Wyndham Hotels & Resorts
provider_slug: wyndham-hotels
slug: wyndham-hotels-eligibility
source_date: '2026-11-10'
source_filename: wyndham-hotels-eligibility.yml
source_heading: Eligibility
source_page: https://www.wyndhamhotels.com/about-us/terms-of-use-more-info
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wyndham Hotels & Resorts\naid: wyndham-hotels\nurl: https://www.wyndhamhotels.com/about-us/terms-of-use-more-info\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Web Services can be accessed from all 50 U.S. states, as well as from other countries around the world.\nentity_types:\n- type: individual\n  text: you represent that you are at least eighteen (18) years of age or the legal age of majority in your jurisdiction\n    (whichever is greater)\n- type: business\n  text: If you access the Web Services on behalf of any organization, your organization shall\
  \ be bound to these\n    Terms and be liable for any breach by you.\nrestricted_uses:\n- summary: Reservations of more than nine rooms\n  text: Reservations made by one or more individuals or by an agency on the Web Services, on behalf of one or more\n    proposed guests, and involving more than nine (9) rooms at the same hotel for the same period of stay, must\n    be made directly through the hotel.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you are at least eighteen (18) years of age or the legal age of majority in your jurisdiction\n    (whichever is greater)\n"
source_yaml_url: https://artifacts.apis.io/wyndham-hotels/eligibility/wyndham-hotels-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Wyndham Hotels & Resorts's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- United States
- Hospitality
- Hotels
- Booking
- Franchising
- Distribution
- Loyalty
- GDS
---
