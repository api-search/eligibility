---
api_specs:
- filename: headout-booking-api-openapi.yml
  format: yaml
  label: HeadOut Booking API
  slug: headout-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/headout/openapi/headout-booking-api-openapi.yml
- filename: headout-categories-api-openapi.yml
  format: yaml
  label: HeadOut Categories API
  slug: headout-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/headout/openapi/headout-categories-api-openapi.yml
- filename: headout-collections-api-openapi.yml
  format: yaml
  label: HeadOut Collections API
  slug: headout-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/headout/openapi/headout-collections-api-openapi.yml
- filename: headout-inventory-api-openapi.yml
  format: yaml
  label: HeadOut Inventory API
  slug: headout-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/headout/openapi/headout-inventory-api-openapi.yml
- filename: headout-products-api-openapi.yml
  format: yaml
  label: HeadOut Products API
  slug: headout-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/headout/openapi/headout-products-api-openapi.yml
- filename: headout-subcategories-api-openapi.yml
  format: yaml
  label: HeadOut Subcategories API
  slug: headout-subcategories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/headout/openapi/headout-subcategories-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: Your use of the Website, Headout Services and carrying out Bookings is permitted only for personal, non-commercial use and/or to make legitimate requests to make a Booking of the Experiences offered on the Website.
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
name: HeadOut
provenance_date: '2026-11-09'
provider_name: HeadOut
provider_slug: headout
slug: headout-eligibility
source_date: '2026-11-09'
source_filename: headout-eligibility.yml
source_heading: Eligibility
source_page: https://www.headout.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HeadOut\naid: headout\nurl: https://www.headout.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: Your use of the Website, Headout Services and carrying out Bookings is permitted only for personal, non-commercial\n    use and/or to make legitimate requests to make a Booking of the Experiences offered on the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/headout/eligibility/headout-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from HeadOut's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Tours and Activities
- Experience
- Attractions
- Ticketing
- Booking
- Marketplace
- Partner API
- Affiliates
- Event
---
