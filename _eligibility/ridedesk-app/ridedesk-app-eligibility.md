---
api_specs:
- filename: ridedesk-app-openapi-generated.yml
  format: yaml
  label: ridedesk-app API
  slug: ridedesk-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ridedesk-app/openapi/_ae-authored/ridedesk-app-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: RideDesk is supplied to businesses
    type: business
  minimum_age:
    text: You must be at least 18 and authorised to bind the business you register.
    value: '18'
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
name: ridedesk-app
provenance_date: '2026-11-10'
provider_name: ridedesk-app
provider_slug: ridedesk-app
slug: ridedesk-app-eligibility
source_date: '2026-11-10'
source_filename: ridedesk-app-eligibility.yml
source_heading: Eligibility
source_page: https://ridedesk.app/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ridedesk-app\naid: ridedesk-app\nurl: https://ridedesk.app/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: RideDesk is supplied to businesses\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and authorised to bind the business you register.\n"
source_yaml_url: https://artifacts.apis.io/ridedesk-app/eligibility/ridedesk-app-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from ridedesk-app's own page on 2026-11-10.
synthetic: false
tags:
- Transportation
- Dispatch
- Booking
- Software-as-a-Service
---
