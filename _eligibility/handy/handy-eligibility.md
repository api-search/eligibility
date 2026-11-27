---
api_specs:
- filename: handy-bookings-api-openapi.yml
  format: yaml
  label: handy Bookings API
  slug: handy-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handy/openapi/handy-bookings-api-openapi.yml
- filename: handy-order-products-api-openapi.yml
  format: yaml
  label: handy Order Products API
  slug: handy-order-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handy/openapi/handy-order-products-api-openapi.yml
- filename: handy-orders-api-openapi.yml
  format: yaml
  label: handy Orders API
  slug: handy-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handy/openapi/handy-orders-api-openapi.yml
- filename: handy-testing-api-openapi.yml
  format: yaml
  label: handy Testing API
  slug: handy-testing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handy/openapi/handy-testing-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'you represent and warrant that: (i) you are at least 18 years old'
    type: individual
  - text: Where you enter into this Agreement on behalf of a company or other organization
    type: business
  minimum_age:
    text: you are at least 18 years old, are at least of the legally required age in the jurisdiction in which you reside
    value: '18'
  restricted_uses:
  - summary: Knowingly false information
    text: ACCORDINGLY, IF YOU KNOWINGLY INPUT FALSE INFORMATION IN A SERVICE REQUEST
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: FOR PROFESSIONALS THAT REGISTER TO USE THE HANDY PLATFORM IN THEIR INDIVIDUAL CAPACITY, HANDY CHECKS THE BACKGROUNDS OF PROFESSIONALS VIA THIRD PARTY BACKGROUND CHECK SERVICES.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: handy
provenance_date: '2026-11-09'
provider_name: handy
provider_slug: handy
slug: handy-eligibility
source_date: '2026-11-09'
source_filename: handy-eligibility.yml
source_heading: Eligibility
source_page: https://www.handy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: handy\naid: handy\nurl: https://www.handy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'you represent and warrant that: (i) you are at least 18 years old'\n- type: business\n  text: Where you enter into this Agreement on behalf of a company or other organization\nrestricted_uses:\n- summary: Knowingly false information\n  text: ACCORDINGLY, IF YOU KNOWINGLY INPUT FALSE INFORMATION IN A SERVICE REQUEST\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: FOR PROFESSIONALS THAT\
  \ REGISTER TO USE THE HANDY PLATFORM IN THEIR INDIVIDUAL CAPACITY, HANDY CHECKS THE\n    BACKGROUNDS OF PROFESSIONALS VIA THIRD PARTY BACKGROUND CHECK SERVICES.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old, are at least of the legally required age in the jurisdiction in which you\n    reside\n"
source_yaml_url: https://artifacts.apis.io/handy/eligibility/handy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from handy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Home Services
- Marketplace
- Cleaning
- Handyman
- Installations
- On-Demand
- Gig Economy
- Order
- Webhook
- Retail
- Angi
---
