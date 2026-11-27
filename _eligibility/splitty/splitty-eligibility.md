---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you may not use the Services if you are located in a country which is subject to Israel, UK, EU, or US sanctions or embargo
  entity_types:
  - text: at least 18 years of age
    type: individual
  - text: if you are acting on behalf of a corporation
    type: business
  minimum_age:
    text: at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Bookings only for actual stays
    text: any Booking must only be made for the purpose of actually staying in the Accommodation for which such Booking is made
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
name: Splitty
provenance_date: '2026-11-10'
provider_name: Splitty
provider_slug: splitty
slug: splitty-eligibility
source_date: '2026-11-10'
source_filename: splitty-eligibility.yml
source_heading: Eligibility
source_page: https://www.splitty.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Splitty\naid: splitty\nurl: https://www.splitty.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: you may not use the Services if you are located in a country which is subject to Israel, UK, EU, or US sanctions\n    or embargo\nentity_types:\n- type: individual\n  text: at least 18 years of age\n- type: business\n  text: if you are acting on behalf of a corporation\nrestricted_uses:\n- summary: Bookings only for actual stays\n  text: any Booking must only be made for the purpose of actually staying in the Accommodation for which such Booking\n\
  \    is made\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/splitty/eligibility/splitty-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Splitty's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Hotels
- Booking
- Consumer
- Techstars
- Trivago
---
