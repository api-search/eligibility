---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: available for your personal or business use
    type: business
  minimum_age:
    text: You acknowledge that you are 18 years old and have the legal right to create a legal obligation.
    value: '18'
  restricted_uses:
  - summary: No fake or speculative bookings
    text: Not making any fake, speculative, or anticipatory bookings
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
name: Gathern
provenance_date: '2026-11-09'
provider_name: Gathern
provider_slug: gathern
slug: gathern-eligibility
source_date: '2026-11-09'
source_filename: gathern-eligibility.yml
source_heading: Eligibility
source_page: https://gathern.co/en/page/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gathern\naid: gathern\nurl: https://gathern.co/en/page/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: available for your personal or business use\nrestricted_uses:\n- summary: No fake or speculative bookings\n  text: Not making any fake, speculative, or anticipatory bookings\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You acknowledge that you are 18 years old and have the legal right to create a legal obligation.\n"
source_yaml_url: https://artifacts.apis.io/gathern/eligibility/gathern-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Gathern's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Hospitality
- Vacation Rentals
- Short-Term Rental
- Marketplace
- Booking
- Peer-to-Peer
- Saudi Arabia
---
