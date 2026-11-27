---
api_specs:
- filename: tock-reservation-openapi.yml
  format: yaml
  label: Tock Reservation API
  slug: reservation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tock/openapi/_original/tock-reservation-openapi.yml
- filename: tock-guest-profile-openapi.yml
  format: yaml
  label: Tock Guest API
  slug: guest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tock/openapi/_original/tock-guest-profile-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are not intended for and may not be used by anyone under the age of 18.
    type: individual
  - text: If you're using the Services for or on behalf of an organization, you're agreeing to these Terms on behalf of that organization, and you represent and warrant that you can do so.
    type: business
  minimum_age:
    text: The Services are not intended for and may not be used by anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: No unauthorized automated access
    text: The use by you, or anyone authorized by you, of machines, computers, scripts or any automated system on the Site is strictly prohibited
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
name: Tock
provenance_date: '2026-11-10'
provider_name: Tock
provider_slug: tock
slug: tock-eligibility
source_date: '2026-11-10'
source_filename: tock-eligibility.yml
source_heading: Eligibility
source_page: https://www.exploretock.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tock\naid: tock\nurl: https://www.exploretock.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are not intended for and may not be used by anyone under the age of 18.\n- type: business\n  text: If you're using the Services for or on behalf of an organization, you're agreeing to these Terms on behalf\n    of that organization, and you represent and warrant that you can do so.\nrestricted_uses:\n- summary: No unauthorized automated access\n  text: The use by you, or anyone authorized by you, of\
  \ machines, computers, scripts or any automated system on\n    the Site is strictly prohibited\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not intended for and may not be used by anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/tock/eligibility/tock-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tock's own page on 2026-11-10.
synthetic: false
tags:
- Hospitality
- Reservations
- Restaurant
- Wineries
- Ticketed Events
- Takeout
- Delivery
- Experience
- Dining
- American Express
---
