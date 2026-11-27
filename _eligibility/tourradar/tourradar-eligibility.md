---
api_specs:
- filename: tourradar-bookings-api-openapi.yml
  format: yaml
  label: TourRadar Bookings API
  slug: tourradar-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourradar/openapi/tourradar-bookings-api-openapi.yml
- filename: tourradar-bulk-api-openapi.yml
  format: yaml
  label: TourRadar Bulk API
  slug: tourradar-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourradar/openapi/tourradar-bulk-api-openapi.yml
- filename: tourradar-operators-api-openapi.yml
  format: yaml
  label: TourRadar Operators API
  slug: tourradar-operators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourradar/openapi/tourradar-operators-api-openapi.yml
- filename: tourradar-pricing-availability-api-openapi.yml
  format: yaml
  label: TourRadar Pricing & Availability API
  slug: tourradar-pricing-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourradar/openapi/tourradar-pricing-availability-api-openapi.yml
- filename: tourradar-taxonomy-api-openapi.yml
  format: yaml
  label: TourRadar Taxonomy API
  slug: tourradar-taxonomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourradar/openapi/tourradar-taxonomy-api-openapi.yml
- filename: tourradar-tours-api-openapi.yml
  format: yaml
  label: TourRadar Tours API
  slug: tourradar-tours-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourradar/openapi/tourradar-tours-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The TourRadar Services are solely for persons who are aged 18 years or older.
    type: individual
  - text: If you are acting on behalf of a company or another legal entity you guarantee that you are legally entitled to accept these terms and conditions in their name.
    type: business
  minimum_age:
    text: The TourRadar Services are solely for persons who are aged 18 years or older.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: TourRadar+ benefits are made available solely for private, non-commercial use; they may not be sold, purchased, brokered, bartered, or otherwise commercialized.
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
name: TourRadar
provenance_date: '2026-11-10'
provider_name: TourRadar
provider_slug: tourradar
slug: tourradar-eligibility
source_date: '2026-11-10'
source_filename: tourradar-eligibility.yml
source_heading: Eligibility
source_page: https://www.tourradar.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TourRadar\naid: tourradar\nurl: https://www.tourradar.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The TourRadar Services are solely for persons who are aged 18 years or older.\n- type: business\n  text: If you are acting on behalf of a company or another legal entity you guarantee that you are legally entitled\n    to accept these terms and conditions in their name.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: TourRadar+ benefits are made available solely for private, non-commercial use; they\
  \ may not be sold, purchased,\n    brokered, bartered, or otherwise commercialized.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The TourRadar Services are solely for persons who are aged 18 years or older.\n"
source_yaml_url: https://artifacts.apis.io/tourradar/eligibility/tourradar-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from TourRadar's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Tours
- Booking
- Marketplace
- Adventure Travel
- Distribution
- Affiliates
---
