---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: These terms (the "Rating Terms") apply when you submit a rating in connection with a Venue reservation made through SevenRooms in the United Kingdom.
  entity_types:
  - text: Certain aspects of the Service are only available to Venues and their authorized representatives ( “Registered Users” )
    type: business
  - text: certain aspects of the Service are only available to users who register for an account with SevenRooms for booking purposes
    type: individual
  minimum_age:
    text: you must be at least 18 years old (or the age of majority in the jurisdiction in which you reside)
    value: '18'
  restricted_uses:
  - summary: No resale of reservations
    text: Resale or attempted resale of any reservation is prohibited.
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
name: SevenRooms
provenance_date: '2026-11-10'
provider_name: SevenRooms
provider_slug: sevenrooms
slug: sevenrooms-eligibility
source_date: '2026-11-10'
source_filename: sevenrooms-eligibility.yml
source_heading: Eligibility
source_page: https://sevenrooms.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SevenRooms\naid: sevenrooms\nurl: https://sevenrooms.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: These terms (the \"Rating Terms\") apply when you submit a rating in connection with a Venue reservation made\n    through SevenRooms in the United Kingdom.\nentity_types:\n- type: business\n  text: Certain aspects of the Service are only available to Venues and their authorized representatives ( “Registered\n    Users” )\n- type: individual\n  text: certain aspects of the Service are only available to users who register for an account with SevenRooms for\n\
  \    booking purposes\nrestricted_uses:\n- summary: No resale of reservations\n  text: Resale or attempted resale of any reservation is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old (or the age of majority in the jurisdiction in which you reside)\n"
source_yaml_url: https://artifacts.apis.io/sevenrooms/eligibility/sevenrooms-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from SevenRooms's own page on 2026-11-10.
synthetic: false
tags:
- Restaurant
- Reservations
- Waitlist
- CRM
- Marketing
- Hospitality
- Guest Experience
---
