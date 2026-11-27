---
api_specs:
- filename: klook-availability-api-openapi.yml
  format: yaml
  label: Klook Availability API
  slug: klook-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klook/openapi/klook-availability-api-openapi.yml
- filename: klook-bookings-api-openapi.yml
  format: yaml
  label: Klook Bookings API
  slug: klook-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klook/openapi/klook-bookings-api-openapi.yml
- filename: klook-products-api-openapi.yml
  format: yaml
  label: Klook Products API
  slug: klook-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klook/openapi/klook-products-api-openapi.yml
- filename: klook-supplier-api-openapi.yml
  format: yaml
  label: Klook Supplier API
  slug: klook-supplier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klook/openapi/klook-supplier-api-openapi.yml
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
  - summary: Commercial activity without consent
    text: Involves commercial activities and/or sales without Klook’s prior written consent such as contests, sweepstakes, barter, advertising, or pyramid schemes
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
name: Klook
provenance_date: '2026-11-09'
provider_name: Klook
provider_slug: klook
slug: klook-eligibility
source_date: '2026-11-09'
source_filename: klook-eligibility.yml
source_heading: Eligibility
source_page: https://www.klook.com/conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Klook\naid: klook\nurl: https://www.klook.com/conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial activity without consent\n  text: Involves commercial activities and/or sales without Klook’s prior written consent such as contests, sweepstakes,\n    barter, advertising, or pyramid schemes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/klook/eligibility/klook-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Klook's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Travel
- Tours and Activities
- Booking
- Experience
- Distribution
- OCTO
- Hospitality
---
