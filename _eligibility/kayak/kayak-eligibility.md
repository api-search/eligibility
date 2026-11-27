---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: You represent that you are not located in, ordinarily resident in, or organized under the laws of any country or region subject to U.S. or other applicable government embargoes (currently including Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions)
  entity_types:
  - text: If you're accessing our Site on behalf of a legal entity (like your employer), you agree that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be over 18 years old to create an account or use booking features; however, the minimum age required to create an account may vary depending on the state, province, or country in which you reside
    value: '18'
  restricted_uses:
  - summary: Unlawful or false reservations
    text: Make any false, fraudulent, or speculative reservation, or any reservation in anticipation of demand.
  - summary: Competing products
    text: Use our Site to develop competing products.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kayak
provenance_date: '2026-11-09'
provider_name: Kayak
provider_slug: kayak
slug: kayak-eligibility
source_date: '2026-11-09'
source_filename: kayak-eligibility.yml
source_heading: Eligibility
source_page: https://www.kayak.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kayak\naid: kayak\nurl: https://www.kayak.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: You represent that you are not located in, ordinarily resident in, or organized under the laws of any country\n    or region subject to U.S. or other applicable government embargoes (currently including Cuba, Iran, North Korea,\n    Syria, and the Crimea, Donetsk, and Luhansk regions)\nentity_types:\n- type: business\n  text: If you're accessing our Site on behalf of a legal entity (like your employer), you agree that you have the\n    authority\
  \ to bind that entity to these Terms\nrestricted_uses:\n- summary: Unlawful or false reservations\n  text: Make any false, fraudulent, or speculative reservation, or any reservation in anticipation of demand.\n- summary: Competing products\n  text: Use our Site to develop competing products.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be over 18 years old to create an account or use booking features; however, the minimum age required\n    to create an account may vary depending on the state, province, or country in which you reside\n"
source_yaml_url: https://artifacts.apis.io/kayak/eligibility/kayak-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Kayak's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Metasearch
- Flights
- Hotels
- Car Rental
- Travel Search
- Price Comparison
- Booking Holdings
- Artificial Intelligence
---
