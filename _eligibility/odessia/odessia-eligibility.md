---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Accounts and the Services, including the Travel Agency Services and Bookings, are intended for residents of the United States and Canada.
  entity_types:
  - text: The terms “you”, “user” or “traveler” refer to the person accessing or using the Services and/or booking a reservation through us
    type: individual
  minimum_age:
    text: you are of sufficient legal age to use the Services and to create a binding legal contract
    value: null
  restricted_uses:
  - summary: Actions without meaningful human review
    text: You must not use the Services to take Actions where acting without meaningful human review would be unlawful, unsafe or inappropriate.
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
name: Odessia
provenance_date: '2026-11-10'
provider_name: Odessia
provider_slug: odessia
slug: odessia-eligibility
source_date: '2026-11-10'
source_filename: odessia-eligibility.yml
source_heading: Eligibility
source_page: https://odessia.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Odessia\naid: odessia\nurl: https://odessia.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Accounts and the Services, including the Travel Agency Services and Bookings, are intended for residents\n    of the United States and Canada.\nentity_types:\n- type: individual\n  text: The terms “you”, “user” or “traveler” refer to the person accessing or using the Services and/or booking\n    a reservation through us\nrestricted_uses:\n- summary: Actions without meaningful human review\n  text: You must not use the Services to take Actions where\
  \ acting without meaningful human review would be unlawful,\n    unsafe or inappropriate.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of sufficient legal age to use the Services and to create a binding legal contract\n"
source_yaml_url: https://artifacts.apis.io/odessia/eligibility/odessia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Odessia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Artificial Intelligence
- Concierge
- Booking
---
