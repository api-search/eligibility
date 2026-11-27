---
api_specs:
- filename: 20885222-5fccfe6e-479a-429f-a497-d42a0bb859c9
  format: yaml
  label: Trip Ninja DataStream API
  slug: tripninja-datastream-api
  spec_type: Postman
  url: https://www.postman.com/tripninjadevteam/workspace/trip-ninja-public/collection/20885222-5fccfe6e-479a-429f-a497-d42a0bb859c9
- filename: webjet-book-api-openapi.yml
  format: yaml
  label: Webjet Book API
  slug: webjet-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-book-api-openapi.yml
- filename: webjet-booking-api-openapi.yml
  format: yaml
  label: Webjet Booking API
  slug: webjet-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-booking-api-openapi.yml
- filename: webjet-cancel-api-openapi.yml
  format: yaml
  label: Webjet Cancel API
  slug: webjet-cancel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-cancel-api-openapi.yml
- filename: webjet-details-api-openapi.yml
  format: yaml
  label: Webjet Details API
  slug: webjet-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-details-api-openapi.yml
- filename: webjet-generate-solutions-api-openapi.yml
  format: yaml
  label: Webjet Generate Solutions API
  slug: webjet-generate-solutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-generate-solutions-api-openapi.yml
- filename: webjet-get-searches-api-openapi.yml
  format: yaml
  label: Webjet Get Searches API
  slug: webjet-get-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-get-searches-api-openapi.yml
- filename: webjet-msdp-api-openapi.yml
  format: yaml
  label: Webjet Msdp API
  slug: webjet-msdp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-msdp-api-openapi.yml
- filename: webjet-pre-booking-api-openapi.yml
  format: yaml
  label: Webjet Pre Booking API
  slug: webjet-pre-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-pre-booking-api-openapi.yml
- filename: webjet-price-api-openapi.yml
  format: yaml
  label: Webjet Price API
  slug: webjet-price-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-price-api-openapi.yml
- filename: webjet-queue-api-openapi.yml
  format: yaml
  label: Webjet Queue API
  slug: webjet-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-queue-api-openapi.yml
- filename: webjet-report-api-openapi.yml
  format: yaml
  label: Webjet Report API
  slug: webjet-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-report-api-openapi.yml
- filename: webjet-results-api-openapi.yml
  format: yaml
  label: Webjet Results API
  slug: webjet-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-results-api-openapi.yml
- filename: webjet-rules-api-openapi.yml
  format: yaml
  label: Webjet Rules API
  slug: webjet-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-rules-api-openapi.yml
- filename: webjet-search-api-openapi.yml
  format: yaml
  label: Webjet Search API
  slug: webjet-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-search-api-openapi.yml
- filename: webjet-super-trip-api-openapi.yml
  format: yaml
  label: Webjet Super Trip API
  slug: webjet-super-trip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-super-trip-api-openapi.yml
- filename: webjet-ticket-api-openapi.yml
  format: yaml
  label: Webjet Ticket API
  slug: webjet-ticket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-ticket-api-openapi.yml
- filename: webjet-ticketing-api-openapi.yml
  format: yaml
  label: Webjet Ticketing API
  slug: webjet-ticketing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-ticketing-api-openapi.yml
- filename: webjet-admin-panel-api-openapi.yml
  format: yaml
  label: Webjet Admin panel API
  slug: webjet-admin-panel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webjet/openapi/webjet-admin-panel-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 18 years of age and have the legal capacity to enter into this agreement.
    type: individual
  - text: Company will provide a website application for Customer to carry out one-way, roundtrip, and multi-city bookings through.
    type: business
  minimum_age:
    text: You are at least 18 years of age and have the legal capacity to enter into this agreement.
    value: '18'
  restricted_uses:
  - summary: No fraud or impersonation
    text: Use the Services to misrepresent your identity, impersonate others, or engage in any fraudulent, illegal, or unauthorized activity.
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
name: Webjet
provenance_date: '2026-11-10'
provider_name: Webjet
provider_slug: webjet
slug: webjet-eligibility
source_date: '2026-11-10'
source_filename: webjet-eligibility.yml
source_heading: Eligibility
source_page: https://tripninja.io/legal/qt-tc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Webjet\naid: webjet\nurl: https://tripninja.io/legal/qt-tc\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 18 years of age and have the legal capacity to enter into this agreement.\n- type: business\n  text: Company will provide a website application for Customer to carry out one-way, roundtrip, and multi-city\n    bookings through.\nrestricted_uses:\n- summary: No fraud or impersonation\n  text: Use the Services to misrepresent your identity, impersonate others, or engage in any fraudulent, illegal,\n    or unauthorized\
  \ activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age and have the legal capacity to enter into this agreement.\n"
source_yaml_url: https://artifacts.apis.io/webjet/eligibility/webjet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Webjet's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Australia
- OTA
- Aviation
- Booking
- Distribution
- Flight Search
- Car Rental
- New Zealand
- Travel Technology
---
