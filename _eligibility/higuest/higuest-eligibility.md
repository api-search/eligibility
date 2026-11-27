---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - AE
    text: United Arab Emirates is our country of domicile. Properties are in Dubai.
  minimum_age:
    text: Minors under the age of 18 shall are prohibited to register as a User of this website
    value: '18'
  restricted_uses:
  - summary: No wedding receptions, parties or similar events
    text: Hi Guests Vacation Homes Rental LLC do not accept bookings for Wedding receptions, parties or similar events.
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
name: HiGuest
provenance_date: '2026-11-09'
provider_name: HiGuest
provider_slug: higuest
slug: higuest-eligibility
source_date: '2026-11-09'
source_filename: higuest-eligibility.yml
source_heading: Eligibility
source_page: https://higuests.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HiGuest\naid: higuest\nurl: https://higuests.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AE\n  excluded: []\n  text: United Arab Emirates is our country of domicile. Properties are in Dubai.\nentity_types: []\nrestricted_uses:\n- summary: No wedding receptions, parties or similar events\n  text: Hi Guests Vacation Homes Rental LLC do not accept bookings for Wedding receptions, parties or similar events.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Minors under the age of 18 shall are prohibited to register\
  \ as a User of this website\n"
source_yaml_url: https://artifacts.apis.io/higuest/eligibility/higuest-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from HiGuest's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hospitality
- Property Management
- Short-Term Rental
- Vacation Rentals
- Travel
- Real Estate
- Dubai
---
