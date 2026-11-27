---
api_specs:
- filename: quandoo-availabilities-api-openapi.yml
  format: yaml
  label: Quandoo Availabilities API
  slug: quandoo-availabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quandoo/openapi/quandoo-availabilities-api-openapi.yml
- filename: quandoo-customers-api-openapi.yml
  format: yaml
  label: Quandoo Customers API
  slug: quandoo-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quandoo/openapi/quandoo-customers-api-openapi.yml
- filename: quandoo-merchants-api-openapi.yml
  format: yaml
  label: Quandoo Merchants API
  slug: quandoo-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quandoo/openapi/quandoo-merchants-api-openapi.yml
- filename: quandoo-reservation-enquiries-api-openapi.yml
  format: yaml
  label: Quandoo Reservation Enquiries API
  slug: quandoo-reservation-enquiries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quandoo/openapi/quandoo-reservation-enquiries-api-openapi.yml
- filename: quandoo-reservation-settings-api-openapi.yml
  format: yaml
  label: Quandoo Reservation Settings API
  slug: quandoo-reservation-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quandoo/openapi/quandoo-reservation-settings-api-openapi.yml
- filename: quandoo-reservations-api-openapi.yml
  format: yaml
  label: Quandoo Reservations API
  slug: quandoo-reservations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quandoo/openapi/quandoo-reservations-api-openapi.yml
- filename: quandoo-reservations-tags-api-openapi.yml
  format: yaml
  label: Quandoo Reservations Tags API
  slug: quandoo-reservations-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quandoo/openapi/quandoo-reservations-tags-api-openapi.yml
- filename: quandoo-reviews-api-openapi.yml
  format: yaml
  label: Quandoo Reviews API
  slug: quandoo-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quandoo/openapi/quandoo-reviews-api-openapi.yml
- filename: quandoo-status-api-openapi.yml
  format: yaml
  label: Quandoo Status API
  slug: quandoo-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quandoo/openapi/quandoo-status-api-openapi.yml
- filename: quandoo-validations-api-openapi.yml
  format: yaml
  label: Quandoo Validations API
  slug: quandoo-validations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quandoo/openapi/quandoo-validations-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only restaurant owners with full legal capacity may enter into these Terms and Conditions.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Quandoo
provenance_date: '2026-11-10'
provider_name: Quandoo
provider_slug: quandoo
slug: quandoo-eligibility
source_date: '2026-11-10'
source_filename: quandoo-eligibility.yml
source_heading: Eligibility
source_page: https://restaurants.quandoo.com/en-gb/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quandoo\naid: quandoo\nurl: https://restaurants.quandoo.com/en-gb/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Only restaurant owners with full legal capacity may enter into these Terms and Conditions.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/quandoo/eligibility/quandoo-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Quandoo's own page on 2026-11-10.
synthetic: false
tags:
- Restaurant
- Reservations
- Booking
- Availability
- Merchants
- Marketplace
---
