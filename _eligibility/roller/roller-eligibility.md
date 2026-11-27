---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: for U.S. CUSTOMERS (AS DEFINED BELOW)
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Gift card use limited to Customer venues
    text: Gift Card value purchased and recorded through the ROLLER Services must be used solely to purchase goods and services at the Venues owned by Customer.
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
name: ROLLER
provenance_date: '2026-11-10'
provider_name: ROLLER
provider_slug: roller
slug: roller-eligibility
source_date: '2026-11-10'
source_filename: roller-eligibility.yml
source_heading: Eligibility
source_page: https://www.roller.software/master-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ROLLER\naid: roller\nurl: https://www.roller.software/master-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: for U.S. CUSTOMERS (AS DEFINED BELOW)\nentity_types: []\nrestricted_uses:\n- summary: Gift card use limited to Customer venues\n  text: Gift Card value purchased and recorded through the ROLLER Services must be used solely to purchase goods\n    and services at the Venues owned by Customer.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/roller/eligibility/roller-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from ROLLER's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Venue Management
- Attractions
- Ticketing
- Booking
- Point-of-Sale
- Payments
- Leisure
- Reservations
- Webhook
---
