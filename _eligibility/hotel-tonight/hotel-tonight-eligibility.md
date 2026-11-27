---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 18 years of age and the age of majority in your jurisdiction of residence
    type: individual
  - text: 'If you access or use the Service for a company, organization, or other entity: (i) you are authorized to grant all permissions and licenses provided in these Terms and bind the entity to these Terms'
    type: business
  minimum_age:
    text: You are at least 18 years of age and the age of majority in your jurisdiction of residence
    value: '18'
  restricted_uses:
  - summary: Fraud, abuse, or impersonation prohibited
    text: Attempt to impersonate another person, account, or entity, including a representative of HotelTonight
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
name: Hotel Tonight
provenance_date: '2026-11-09'
provider_name: Hotel Tonight
provider_slug: hotel-tonight
slug: hotel-tonight-eligibility
source_date: '2026-11-09'
source_filename: hotel-tonight-eligibility.yml
source_heading: Eligibility
source_page: https://www.hoteltonight.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hotel Tonight\naid: hotel-tonight\nurl: https://www.hoteltonight.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 18 years of age and the age of majority in your jurisdiction of residence\n- type: business\n  text: 'If you access or use the Service for a company, organization, or other entity: (i) you are authorized to\n    grant all permissions and licenses provided in these Terms and bind the entity to these Terms'\nrestricted_uses:\n- summary: Fraud, abuse, or impersonation prohibited\n  text: Attempt\
  \ to impersonate another person, account, or entity, including a representative of HotelTonight\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age and the age of majority in your jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/hotel-tonight/eligibility/hotel-tonight-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Hotel Tonight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Travel
- Hotels
- Booking
- Hospitality
- Mobile
- Airbnb
---
